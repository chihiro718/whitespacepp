# Whitespace++

## Features
Whitespace++ allows you to customize characters and colors of whitespaces, such as TAB (\\t), Line Feed (\\n), Wide space, and EOF (End of File).


![image](https://raw.githubusercontent.com/chihiro718/whitespacepp/master/images/image.png)


## Usage
This extension is automatically enabled when you open documents.


## Extension Settings
This extension contributes the following settings:
* `whitespacepp.renderTAB`: 
render TAB (\\t) characters or not.
* `whitespacepp.renderWS`: 
render Wide Space characters or not.
* `whitespacepp.renderLF`: 
render Line Feed (\\n) character or not.
* `whitespacepp.renderEOF`: 
render [EOF] marker at the end of the file or not.
* `whitespacepp.textTAB`: 
Text for TAB (\\t). It's recommended that you specify 1em size characters, and you can also specify unicode characters such as \"￫\", \"‣\", \"▸\", \"▹\", \"❯\".
* `whitespacepp.textWS`: 
Text for Wide Space. It's recommended that you specify 2em size characters, and you can also specify unicode characters such as \"▢\", \"◌\", \"▨\", \"▒\", \"🔲\".
* `whitespacepp.textLF`: 
Text for Line Feed (\\n). You can also specify unicode characters such as \"↩\", \"◂\", \"▾\".
* `whitespacepp.textEOF`: 
Text for EOF (End of File). You can also specify unicode characters.
* `whitespacepp.foreColorTAB`: 
Text color for TAB (\\t).
* `whitespacepp.foreColorWS`: 
Text color for Wide Space.
* `whitespacepp.foreColorLF`: 
Text color for Line Feed (\\n).
* `whitespacepp.foreColorEOF`: 
Text color for EOF (End of File).
* `whitespacepp.changeBackColorTAB`: 
Check here to change background color for TAB (\\t).
* `whitespacepp.changeBackColorWS`: 
Check here to change background color for Wide Space.
* `whitespacepp.changeBackColorLF`: 
Check here to change background color for Line Feed (\\n).
* `whitespacepp.changeBackColorEOF`: 
Check here to change background color for EOF (End of File).
* `whitespacepp.backColorTAB`: 
Background color for TAB (\\t).
* `whitespacepp.backColorWS`: 
Background color for Wide Space.
* `whitespacepp.backColorLF`: 
Background color for Line Feed (\\n).
* `whitespacepp.backColorEOF`: 
Background color for EOF (End of File).
* `whitespacepp.renderingDelayMs`: 
Rendering delay time in millisecond. Drawing requests with intervals shorter than the delay time will be canceled.

## Known Issues
None

## Release Notes
|Ver|Date|Comment|
|----|----|----|
|1.0.0|2020.10.21|Initial release|
|1.0.1|2020.10.21|Changed the VSCode version that the Whitespace++ is compatible with|
