![alt text](src/icon.png)

# Alfred PDF Tools

A workflow for [Alfred 3][1].

## Description

Optimize, encrypt and manipulate PDF files.

## Download and Installation

Download the workflow file from [GitHub releases][2] and install it by double-clicking on `Alfred.PDF.Tools.alfredworklow`.

## Usage

This workflow relies on [file actions][12] in Alfred:

> Found your file in Alfred? Press the `right arrow key` to reveal the File Actions panel
>
> Selected a file in Finder? Use `Cmd + Alt + \` to pop up File Actions

**Alfred PDF Tools** can be used by the following file actions:

* `Optimize`: Optimize the selected PDF files by entering the intended resolution of the output file (150 dpi is set once no value is input). The document will be improved on the process with increased contrast and text straightening. Invoke Alfred and type the keyword `progress` if you want to track the optimization process;
* `Encrypt`: Encrypt the selected PDF files by entering a password;
* `Decrypt`: Decrypt the selected PDF files by entering their password or just `↩` if they're not password protected;
* `Merge`: Merge the selected PDF files. Use the `⌘` modifier key if you also want to move the source files to Trash;
* `Split by Page Count`: Split the selected PDF file by page count.
* `Split by File Size`: Split the selected PDF file by file size.
* `Slice in Multiple Files`: Slice the selected PDF file in multiple files by entering page numbers and/or page ranges separated by commas (e.g. 2, 5-8, 20-).
* `Slice in a Single File`: Slice the selected PDF file in a single file by entering page numbers and/or page ranges separated by commas (e.g. 2, 5-8, 20-).
* `Crop`: Convert two-column pages in single pages.
* `Scale`: Scale the selected PDF files to a given paper size.

## Contribute

To report a bug or request a feature, please [create an issue][3] or [submit a pull request][4].

## Credits

This workflow relies on [PyPDF2][5] library currently maintained by [Phaseit, Inc.][6], [Alfred-Workflow][7] library by Dean Jackson, [K2pdfopt][8] by Johannes Buchnerand, [Send2Trash][9] by Virgil Dupras and [docopt][10]. The code for the `Crop` file action  was mostly created by Matt Gumbley (Stack Overflow) and changed by Hanspeter Schmid to deal with already cropped pages.

## License

**Alfred PDF Tools** is released under the [MIT License][11].

[1]:http://www.alfredapp.com/
[2]:https://github.com/xilopaint/alfred-pdf-tools/releases/latest
[3]:https://github.com/xilopaint/alfred-pdf-tools/issues
[4]:https://github.com/xilopaint/alfred-pdf-tools/pulls
[5]:https://github.com/mstamy2/PyPDF2
[6]:http://phaseit.net
[7]:https://github.com/deanishe/alfred-workflow
[8]:http://www.willus.com/k2pdfopt/
[9]:https://github.com/hsoft/send2trash
[10]:https://github.com/docopt/docopt
[11]:https://opensource.org/licenses/MIT
[12]:https://www.alfredapp.com/blog/tips-and-tricks/file-actions-from-alfred-or-finder/
