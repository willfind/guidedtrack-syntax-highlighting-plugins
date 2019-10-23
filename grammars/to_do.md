* put in highlighting to catch variable interpolation {} within strings. 
* Improve highlighting for `*send` operations, such as: 
 `*send: {"category" -> "whatever", "action" -> "etc."}`
 At least, make it notice when there's not a closing }
 * Add highlighting for `*component` and `*click` in VSCode (and any others it's missing in)
 * Add support for bold and italics within strings, display text