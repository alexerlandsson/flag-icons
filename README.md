# Flag Icons
Flag Icons is a CSS framework to use flag icons in web projects.

## Quick Start
Follow these simple steps and you are ready to go in less than one minute!

### 1. Include needed files into your project
Inlcude the flags folder and the CSS file into your project. If you want to customize the CSS or are using SCSS in the project, you can import flag-icons.scss and compile into your main CSS file instead.

### 2. Include the CSS in your HTML files

```html
<link rel="stylesheet" href="/PATH/flag-icons.min.css">
```

### 3. Add icons to your project
To add a flag to an element, add class `fi` followed by `fi-[COUNTRYCODE]`. Example:

```html
<i class="fi fi-se"></i>
```

## Configuration
If you are using flag-icons in a scss-project you can make some modifications.

### Image Path
Change `$image_path` to the path where the images ar located.

### Image Size
Change `$image_size` to the size of the images.

## Flags
Included flag images are created by Jonathan Allen and can also be downloaded from: http://365icon.com/icon-styles/ethnic/classic2/. These are free to use for personal and commercial projects.

You can use any images you want as long as they are named after the ISO 3166-1 alpha-2 standard (two-letter country code).

## Browser Compatibility
| ![Chrome](https://github.com/alrra/browser-logos/blob/master/src/chrome/chrome_64x64.png?raw=true) | ![Safari](https://github.com/alrra/browser-logos/blob/master/src/safari/safari_64x64.png?raw=true) | ![Firefox](https://github.com/alrra/browser-logos/blob/master/src/firefox/firefox_64x64.png?raw=true) | ![Opera](https://github.com/alrra/browser-logos/blob/master/src/opera/opera_64x64.png?raw=true) | ![IE](https://github.com/alrra/browser-logos/blob/master/src/archive/internet-explorer_9-11/internet-explorer_9-11_64x64.png?raw=true) |
|-----|-----|-----|-----|-----|
| <div align="center">Yes</div> | <div align="center">Yes</div> | <div align="center">Yes</div> | <div align="center">Yes</div> | <div align="center">9+</div> |

## License
The MIT License (MIT)

Copyright (c) 2016 Alexander Erlandsson

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
