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

#### Syntax Highlighting

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

```skill
region
defun
procedure
let
when
unless
case
if
if else
foreach
for
setof
mapcar lambda
```

### Theme

#### Skill Dark Modern 

<img src="https://github.com/herbertagosto/code-skill/blob/main/resources/images/skill-syntax-dark.png?raw=true" alt="Image showing syntax highlighting on Skill Dark Modern theme">

#### Skill Light Modern

<img src="https://github.com/herbertagosto/code-skill/blob/main/resources/images/skill-syntax-light.png?raw=true" alt="Image showing syntax highlighting on Skill Light Modern theme">


## Extension Settings

This extension contributes the following settings:

* `skill.maxNumberOfProblems`: Controls the maximum number of problems produced by the server.

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
* Fix #1
* Fix #2

### 0.3.0
* Add region folding
* Add new items in configuration

### 0.4.0
* Resolve #3. Add ocean files *.ocn in extensions

### 0.5.0
* Add Skill Dark Modern theme
* Update Snippets
* Remove comma after 'type' by @SeanStrain in #4

### 0.6.0
* Add **Go to Definition**
* Add Document Symbol
* Add Code Completion
* Add Diagnostic (limited)
* Update syntax highlighting and themes

## For more information

* [Reach me](http://herbagosto@gmail.com)


**Enjoy!**