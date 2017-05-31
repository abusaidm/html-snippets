
# Visual Studio Code HTML Snippets
 
This extension adds rich language support for the HTML Markup to VS Code, including:
- Full HTML5 Tags
- Colorization
- Snippets
- [partially implemented] Quick Info
- description mentions if tag deprecated 

### Update 5
- Add new snippet to script with property src.

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
- [on-going] Improve syntax layout.
- [on-going] Add support for Tab to end of line.
- [on-going] Populate Tags with properties.

## Using
Type part of a snippet, press enter, and the snippet unfolds.

Snippets named as the tag without braces 
    
    div --> <div></div>
    doc --> <!DOCTYPE html>
    a   --> <a href=""></a>

![alt text](http://i.imgur.com/VOhBvHb.gif "Snippets Preview")

## Installation

1. Install Visual Studio Code 0.10.1 or higher
2. Launch Code
3. From the command palette `Ctrl-Shift-P` (Windows, Linux) or `Cmd-Shift-P` (OSX)
4. Select Install Extension
5. Type `HTML-Snippets`
6. Choose the extension
7. Reload Visual Studio Code

## FAQ
### How to enable the snippets on a file other than html?
Please Read this answer.
[Make extension work in languages other than HTML](https://github.com/abusaidm/html-snippets/issues/27#issuecomment-282512411)
 
## License
MIT License, refer to license file.

## Source
[Github](https://github.com/wgenial/html-snippets)

### Disclaimer
This extension is a forked version from [https://github.com/abusaidm/html-snippets](https://github.com/abusaidm/html-snippets) @m_abusaid (author)
