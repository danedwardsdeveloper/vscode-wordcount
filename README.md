# VSCode - WordCount README

Fork of [microsoft/vscode-wordcount](https://github.com/microsoft/vscode-wordcount) that groups the count with thousands separators — `1,234 Words` rather than `1234 Words`. The separator follows the editor's locale, so it is a comma under `en-*`.

The build has also been brought up to date: `@types/vscode` and TypeScript 5 in place of the retired `vscode` npm package, which no longer installs.

This is a simple extension that illustrates a number of concepts when it comes to writing extensions for VS Code.  

* Activation on a file type open
* Contributing to the status bar
* Subscribing to update events
* Adding a test to your extension
* Marking up the `package.json` so the gallery looks good

## Functionality

It's pretty simple open up a `Markdown` file and the status bar will have an auto-updating wordcount in it...

![Word Count in status bar](images/wordcount.gif)
