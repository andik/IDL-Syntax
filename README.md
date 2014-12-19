# IDL syntax highlighting
 
This package provides a simple IDL (Microsoft midl, Mozilla WebIDL) syntax highlighting, derived from Sublime's standard C++ highlighting. It provides you with correct symbol detection, which was the main reason to create this. 

No fancy stuff here, no additional functionality, no snippets

## Note about Scopes
(This is only due to the use of Textmate Syntax highlighting which seems to have a worldwide global namespace. It has little effect to the end user.)

This file was primarily intended for highlighting MS IDL files (used by Windows COM Interfaces). But people seem to be more interested in highlighting webIDL Files, where this file seems to work too. Because of a namespace glitch in I was asked to rename the scope of this syntax highlighting and did so. Scope is now `source.webidl`. 

Because I'm not willing to maintain two files this new scopename does also apply to MS IDL files in future. This is not completely correct, but does not have any influence on the functionality in regard of MS IDL files. Except you wrote your own extensions for this scope. In this case, you need to modify them to match the new scope. Or just let me know, maybe we can have a solution for both sides.
