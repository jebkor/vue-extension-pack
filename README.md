# Vue VSCode Extension Pack

A collection of the extensions that I use in my day-to-day development in VSCode. Heavily configured towards Vue.js development


## Extensions included
[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag): There is nothing worse than having to update the end-tag of an element, *after* your page doesn't work, because of an unclosed tag - this extension helps mitigating that

[Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify): Formats your JSON, CSS, Sass and HTML

[Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments): An extension for making comments more visible by color-coding them, depending on importance

[Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer): Having difficulty determining which bracket closes which? This extension colorizes the brackets to make it easier for you to identify the correct pair

[Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker): Not much to it - helps you with correct spelling of words, even camelCased words.

[Color Info](https://marketplace.visualstudio.com/items?itemName=bierner.color-info): Quick information on css colors

[Color Picker](https://marketplace.visualstudio.com/items?itemName=anseki.vscode-color): Easily change or generate a css color

[ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint): Because who doesn't want to be disturbed with linting rules? I sure do!

[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens): Because we want to see, inline in the editor, who made the last change to the line you're standing on

[HTMLHint](https://marketplace.visualstudio.com/items?itemName=mkaufman.HTMLHint): Having the editor tell us that our HTML could be faulty before we get a document error, is a nice addition

[Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost): Seeing the size of the package included in our javascript, is a great way to become aware of bundle sizes

[IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion): Auto-complete capability in your HTML file

[JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets): Because making ES6 more available is a great idea!

[Lorem Ipsum](https://marketplace.visualstudio.com/items?itemName=Tyriar.lorem-ipsum): Quis cupidatat occaecat mollit incididunt esse reprehenderit nisi voluptate id ut enim sit aute in.

[npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script): Because most of us is working with npm in the first place

[npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense): Remembering a package name can sometimes be difficult, ok?! 🤷‍

[Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager): Making it easier to switch between bookmarked projects

[SCSS Formatter](https://marketplace.visualstudio.com/items?itemName=sibiraj-s.vscode-scss-formatter): Better SCSS formatting

[SCSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-scss): IntelliSense of mixins, functions and variables within scss files

[Sort Lines](https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines): I use it for alphabetical ordering of CSS/SCSS properties.

[TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight): This will highlight TODOs and FIXMEs in the code

[Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree): Gather all the TODOs in a nice list

[Toggle Quotes](https://marketplace.visualstudio.com/items?itemName=BriteSnow.vscode-toggle-quotes): Because sometimes we forget whether we use double or single quotes

[Version Lens](https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens): Displays the version of a package in package.json and if it has an update or not

[Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur): Since we are targeting Vue development here, this will bring syntax highlighting, snippets, emmet support and much more!



## Themes included

[Hydra Theme for VSCode](https://marketplace.visualstudio.com/items?itemName=juanmnl.vscode-theme-hydra): 'If a head is cut off, two more shall take its place'

[Nord](https://marketplace.visualstudio.com/items?itemName=arcticicestudio.nord-visual-studio-code): An arctic, north-bluish clean and elegant Visual Studio Code theme.

[vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons): Better support for icons in the sidebar - .vue files will also get an icon. Neat!


## Installation
To install the dependencies for compiling the extension pack:
> npm install -g yo generator-code

To then install the extension pack:

1. Clone it!
2. Open the directory
3. Open a Powershell/Terminal/CMD/Bash window
4. Run `vsce package`

This will generate a .vsix file in the root of the folder.

When you have the .vsix file, you then:

1. Open the extensions side-panel in VSCode
2. Open 'More actions' from the three-dot menu in the upper-right corner
3. Select 'Install from VSIX'
4. Locate the compiled .vsix file
5. Reload VSCode and enjoy the extension pack


## Relevant links

* [GitHub](https://github.com/jebkor/vue-vscode-extension-pack)
* [VSCode Marketplace](#): Coming soon!

**Enjoy!**
