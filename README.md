# Autohotkey-Markdown  
- - - -  
## General
This is a simple [AutoHotkey](http://www.autohotkey.com/) script. It should allow easy Markdown writing independing from the Editor.
## Feature
Adding the related Markdown syntax element and set the correct cursor position for writing.
* alt + i 	(emphatic text)
* alt + b	(strong text)
* alt + c	(source code)
* alt + q 	(quote)
* alt + .	(start of unordered list)
* alt + ,	(start of ordered list)
* alt + t	(insert 4 spaces, helpfull for neasting)
* alt + -	(horizontal line)
## Special Feature
* alt + l	(start "link wizard") 
* alt + p	(start "image wizard") 
* alt + #	(start "code beautifier")
### Link Wizard
Shows simple window with edit boxes for the URL and the Name. While pressing OK, the Markdown-Text will inserted at cursor position.
### Image Wizard
Same as Link Wizard but with possibility to show preview of the image.
### Code Beautifier
Script will let you browse for HTML file (e.g. generated HTML from  markdown) and copy the content to a second file, same name like selected file but *_converted* will be added.  
If there are **<code></code>** sections within the HTML, some transformation (see below) will be happen. This lead to easier to read source code within HTML.
  
1. Replace tabulator with 4 spaces
2. Replace each space with `&nbsp;`
3. Replace each new line with `<br />`

## License
This project using the MIT license (see LICENSE file).
