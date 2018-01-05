# README
## Visual Studio Code HTML Snippets
## DISABLING THIS EXTENSION AS IT CURRENTLY CONFLICTS WTH EXISTING VS CODE HTML EXTENSION
 
This extension adds rich language support for the HTML Markup to VS Code, including:

- Full HTML5 Tags
- Colorization
- Snippets
- [partially implemented] Quick Info
- description mentions if tag deprecated 

### Update 5
- Disabling this extension as its functionality has been absorbed by VS Code main html extension.

### Update 4
- Removed all languages, only HTML Remains.
- Added FAQ in end of page.

### Update 3
- added php, js, and jsreact as languages where the snippets work by default.


### Update 2
- fixed a bug with line cursor on vscode 1.5.1

### Update 1
- removed deprecated tags [acronym, applet, basefont, center, dir, font, frame, frameset, noframes, strike, tt]
- fixed LI tag issue, you couldn't add new line in the tags

### Todo
- [on-going]Improve syntax layout.
- [on-going]Add support for Tab to end of line.
- [on-going]Populate Tags with properties.

# Using
Type part of a snippet, press enter, and the snippet unfolds.

Snippets named as the tag without braces 
    
    div --> <div></div>
    doc --> <!DOCTYPE html>
    a   --> <a href=""></a>

![alt text](https://i.imgur.com/VOhBvHb.gif "Snippets Preview")

# Installation

1. Install Visual Studio Code 0.10.1 or higher
2. Launch Code
3. From the command palette `Ctrl-Shift-P` (Windows, Linux) or `Cmd-Shift-P` (OSX)
4. Select Install Extension
5. Type `HTML-Snippets`
6. Choose the extension
7. Reload Visual Studio Code

# FAQ
## How to enable the snippets on a file other than html?
<s>Add the following code to the project settings.json or global settings.json :
```
"files.associations": {
        // extension name : html
        "*.ejs": "html",
        "*.js": "html"
    }
```
the above code will allow html snippet to work on .ejs and .js files, amend to fit your needs.</s>

Please Read this answer.
[Make extension work in languages other than HTML](https://github.com/abusaidm/html-snippets/issues/27#issuecomment-282512411)

## How can I report an issue?
The easiest way is to start a git issue, I will attempt to answer ASAP else I hope someone else will answer.
 
# Contact
If you find any issue or have a suggestion please tweet me on @m_abusaid

>**I am unable to respond to comments on the store page, please use appropriate channels github/twitter to reach me. Thank you**

## License
MIT License, refer to license file.

# Source
[Github](https://github.com/abusaidm/html-snippets)

** Enjoy!**
