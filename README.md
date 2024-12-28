# SKILL for Visual Studio Code

A Visual Studio Code extension that provides language support for Cadence SKILL.

## Features

* [Syntax Highlighting](#syntax-highlighting)
* [Go to Definition](#go-to-definition)
* [Document Symbol](#document-symbol)
* [Code Completion](#code-completion) *\*Improved*
* [Hover](#hover) *\*New*
* [Documentation Comment](#documentation-comment) *\*New*
* [Diagnostic](#diagnostic)
* [Folding](#folding)
* [Snippet](#snippet)
* [Theme](#theme)

### Syntax Highlighting

<img src="https://github.com/herbertagosto/code-skill/blob/main/resources/images/syntax-dark.png?raw=true" alt="Image showing syntax highlighting on Skill Dark Modern theme">

### Go to Definition `F12`

<img src="https://github.com/herbertagosto/code-skill/blob/main/resources/images/goto-definition.gif?raw=true" alt="Animation showing Go to Definition">

### Document Symbol

<img src="https://github.com/herbertagosto/code-skill/blob/main/resources/images/document-symbol.gif?raw=true" alt="Image showing document symbol">

### Code Completion

<img src="https://github.com/herbertagosto/code-skill/blob/main/resources/images/code-completion.gif?raw=true" alt="Animation showing code completion">

### Hover

<img src="https://github.com/herbertagosto/code-skill/blob/main/resources/images/hover.gif?raw=true" alt="Animation showing hover">

### Documentation Comment

Type `doc` keyword before a function to automatically add a documentation comment.\
*Documentation comment will appear in Hover and Code Completion.*

<img src="https://github.com/herbertagosto/code-skill/blob/main/resources/images/document-comment.gif?raw=true" alt="Animation showing hover">

### Diagnostic `Ctrl-Shift-M`

*Currently limited. Checks only for defun and procedure syntax errors.*

<img src="https://github.com/herbertagosto/code-skill/blob/main/resources/images/diagnostic.gif?raw=true" alt="Animation showing diagnostic">

### Folding

```skill
;region REGION NAME
your blocks of code...

;endregion
```

### Snippet

Type the keyword (or part of it) then hit `Space`.

```skill
region
defun
procedure
let
when
unless
case
if else
foreach
for
setof
mapcar lambda
```

### Theme

Skill Dark Modern

<img src="https://github.com/herbertagosto/code-skill/blob/main/resources/images/syntax-dark.png?raw=true" alt="Image showing syntax highlighting on Skill Dark Modern theme">

Skill Light Modern

<img src="https://github.com/herbertagosto/code-skill/blob/main/resources/images/syntax-light.png?raw=true" alt="Image showing syntax highlighting on Skill Light Modern theme">

## Extension Settings `Ctrl` + `,`

This extension contributes the following settings:

### Code Completion Settings

* `skill.completion.wordBasedSuggestions`: Controls whether completions should be computed based on words in the document and from which documents they are computed.

* `skill.completion.enableAllegroSkillFunctions`: Enable Allegro SKILL functions.

* `skill.completion.enableFrameworkIISkillFunctions`: Enable Framework II SKILL functions.

* `skill.completion.userCustomKeywords`: Configure user's own keywords. Use | char to separate.\
 *Example: userKeyword1|userKeyword2.*

* `skill.diagnostic.maxNumberOfCompletions`: Limit the maximum number of completions produced.

### Diagnostic Settings

* `skill.diagnostic.maxNumberOfProblems`: Limit the maximum number of problems produced.

<!-- 
## Known Issues

Call out known issues to help limit users opening duplicate issues.
 -->

## For more information

* [Reach me](http://herbertagosto@gmail.com)

## Support

<a href="https://www.buymeacoffee.com/hagosto" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-blue.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

**Enjoy!**