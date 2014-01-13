*Note: Requires that pngpaste is in the path*

## Requirements

Currently supports OS X. Windows and linux support planned.

On OS C, you must have the [pngpaste][1] command in your path.

## Installation

Use [Pathogen][2] or [Vundle][3] to install and activate.

## Usage

The following will save any image in the clipboard to /images, and include a
markdown image link referencing it within the current document.

    :call image_paste#PasteImage

You can map to a command that is more easy to type within your .vimrc as follows.

    command! PasteImage :call image_paste#PasteImage()

## License

This code is free to use under the terms of the MIT license.

Copyright (c) 2014 Blake Taylor

See LICENSE file for further details.

[1]: https://github.com/jcsalterego/pngpaste
[2]: https://github.com/tpope/vim-pathogen
[3]: https://github.com/gmarik/vundle
