# xlint-css-sublime
## [XLint](https://github.com/medikoo/xlint) CSSLint build system for Sublime Text2

__It's modified version of [Sublime-JSLint](https://github.com/darrenderidder/Sublime-JSLint)__

### Prerequisites

NodeJS must be installed on your system and you must be able to run 'node' from the command line.

### Installation

In your console go to Packages folder of Sublime Text:
* Linux: `~/.config/sublime-text-2/Packages`
* Mac: `~/Library/Application Support/Sublime Text 2/Packages`
* Windows: `%APPDATA%/Sublime Text 2/Packages` or if it doesn't exists try `%APPDATA%/Roaming/Sublime Text 2/Packages`

Clone this project into _XLintCss_ folder

	$ git clone https://github.com/medikoo/xlint-css-sublime.git XLintCss

Install its dependencies:

	$ cd XLintCss
	$ npm install

Restart Sublime Text

Usage
-----
Any of the following will work:
   * Select 'XLintCss' under Tools > Build System and run Build.
   * Select Tools > XLintCss
   * Just save a .css file (If you're also using [xlint-sublime](https://github.com/medikoo/xlint-sublime) be sure to have checked Tools -> Build System -> Automatic)
