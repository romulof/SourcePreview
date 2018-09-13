[![Build Status](https://travis-ci.com/tsif/SourcePreview.svg?token=8ZyhMMGarwUGfCibCHGk&branch=master)](https://travis-ci.com/tsif/SourcePreview) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  ![version: 0.1.0](https://img.shields.io/badge/version-0.1.0-green.svg)

# SourcePreview

Quick look plugin for macOS for source code files in swift. Inspired by [QLMarkDown](https://github.com/toland/qlmarkdown) and [QLSwift](https://github.com/lexrus/QLSwift). Source code is rendered by using [prism.js](https://prismjs.com/)

by Dimitri James Tsiflitzis dimitrijam.es

design by Dimitris Niavis 

![Alt Text](https://github.com/tsif/SourcePreview/blob/develop/SourcePreview/screenshots/preview.png)

![Alt Text](https://github.com/tsif/SourcePreview/blob/develop/SourcePreview/screenshots/thumbnail.png)

## Installation

- You can run the `SourcePreview` scheme in xcode. A post build step copies into `SourcePreview.qlgenerator` into `~/Library/QuickLook` and you can start previewing swift files.

- You can run the installer package located in `/` by double clicking on it.

## Removal

Drag `SourcePreview.qlgenerator` located in `~/Library/QuickLook` into the trash.

## License

```
MIT License

Copyright (c) 2018 tsif

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
