# Skill README

Syntax highlighter to skill files in visual studio code.

## Features

* [Syntax Highlighting](#syntax-highlighting)
* [Go to Definition](#go-to-definition)
* [Document Symbol](#document-symbol)
* [Code Completion](#code-completion)
* [Diagnostic](#diagnotic)
* [Folding](#folding)
* [Snippet](#snippet)
* [Theme](#theme)

### Syntax Highlighting

<img src="https://github.com/herbertagosto/code-skill/blob/main/resources/images/skill-syntax-dark.png?raw=true" alt="Image showing syntax highlighting on Skill Dark Modern theme">

### Go to Definition

Shortcut key `F12`

<!-- <img src="https://github.com/herbertagosto/code-skill/blob/main/resources/images/skill.gif?raw=true" alt="Animation showing project feature"> 
-->

<img src="https://github.com/herbertagosto/code-skill/blob/main/resources/images/skill-goto-definition.gif?raw=true" alt="Animation showing Go to Definition">


### Document Symbol

<img src="https://github.com/herbertagosto/code-skill/blob/main/resources/images/skill-document-symbol.png?raw=true" alt="Image showing document symbol">


### Code Completion

<img src="https://github.com/herbertagosto/code-skill/blob/main/resources/images/skill-code-completion.gif?raw=true" alt="Animation showing code completion">


### Diagnostic

Shortcut key `Ctrl-Shift-M`.

*Limited at this time. Checks only for syntax errors in defun and procedure.*

<img src="https://github.com/herbertagosto/code-skill/blob/main/resources/images/skill-diagnostic.gif?raw=true" alt="Animation showing diagnostic">


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
<img src="https://github.com/herbertagosto/code-skill/blob/main/resources/images/skill-syntax-dark.png?raw=true" alt="Image showing syntax highlighting on Skill Dark Modern theme">

Skill Light Modern
<img src="https://github.com/herbertagosto/code-skill/blob/main/resources/images/skill-syntax-light.png?raw=true" alt="Image showing syntax highlighting on Skill Light Modern theme">


## Extension Settings

This extension contributes the following settings (press `Ctrl` + `,` to open settings):

### Code Completion Settings

* `skill.completion.wordBasedSuggestions`: Controls whether completions should be computed based on words in the document and from which documents they are computed.

* `skill.completion.enableAllegroSkillFunctions`: Enable Allegro SKILL functions.

* `skill.completion.enableFrameworkIISkillFunctions`: Enable Framework II SKILL functions.

* `skill.completion.userCustomKeywords`: Configure user's own keywords. Use | char to separate.\
 Example: skillCustomKeyword1|skillCustomKeyword2.

### Diagnostic Settings

* `skill.diagnostic.maxNumberOfProblems`: Limit the maximum number of problems produced.


<!-- 
* `myExtension.enable`: Enable/disable this extension.
* `myExtension.thing`: Set to `blah` to do something.


## Known Issues

Calling out known issues can help limit users opening duplicate issues against your extension.

 -->



## Release Notes

### 0.1.0
* Initial release

### 0.2.0
* Fix [#1](https://github.com/herbertagosto/code-skill/issues/1)
* Fix [#2](https://github.com/herbertagosto/code-skill/issues/2)

### 0.3.0
* Add region folding
* Add new items in configuration

### 0.4.0
* Resolve [#3](https://github.com/herbertagosto/code-skill/issues/3). Add ocean files *.ocn in extensions

### 0.5.0
* Add Skill Dark Modern theme
* Update Snippets
* Remove comma after 'type' by @SeanStrain in [#4](https://github.com/herbertagosto/code-skill/issues/4)

### 0.6.0
* Add **Go to Definition**
* Add Document Symbol
* Add Code Completion
* Add Diagnostic (limited)
* Update syntax highlighting and themes

### 0.7.0
* Update Document Symbol
* Update Code Completion
* Update Snippets
* Resolve [#5](https://github.com/herbertagosto/code-skill/issues/5). Add Framework II SKILL Functions

### 0.8.0
* Add Word Base Suggestions
* Resolve [#6](https://github.com/herbertagosto/code-skill/issues/6). Suggest words from the active document
* Resolve [#7](https://github.com/herbertagosto/code-skill/issues/7). Suggest words from all open documents

## For more information

* [Reach me](http://herbagosto@gmail.com)


## Support

<a href="https://www.buymeacoffee.com/hagosto" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>



**Enjoy!**