# Fragment Highlighter

JavaScript with similar functionality to [the target pseudo-class][1].
Written when support for `:target` was not widespread. Using `:target`
is a much better idea in most cases today, and if I were to find a 
use for this script then I would rewrite it to eliminate the use of
[DOM element properties][2] as they are a pretty fragile approach to
event handling.

[1]: http://www.w3.org/TR/selectors/#target-pseudo
[2]: https://developer.mozilla.org/en-US/docs/DOM/event