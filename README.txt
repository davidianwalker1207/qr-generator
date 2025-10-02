================================================================================
                           QR CODE GENERATOR
                              Version 0.5
                           2nd October 2025
================================================================================

DESCRIPTION
-----------
A web-based QR code generator that creates customisable QR codes in PNG or SVG 
format. Works entirely in your browser - no server required, no data uploaded.


FEATURES
--------
- Multiple QR code types:
  * Website URLs
  * Plain text
  * Email addresses with subject/body
  * Phone numbers
  * SMS messages
  * WiFi network credentials
  * Contact cards (vCard)
  * Calendar events (iCalendar)

- Output formats:
  * PNG - High quality raster image
  * SVG - Scalable vector format

- Customisation:
  * Custom dot colour
  * Custom background colour
  * Logo upload (automatically applies high error correction)

- User experience:
  * Input preservation when switching between QR code types
  * Instant preview
  * One-click download


HOW TO USE
----------
1. Open the HTML file in any modern web browser
2. Select your QR code category from the dropdown
3. Enter the required information
4. (Optional) Choose PNG or SVG format
5. (Optional) Customise colours
6. (Optional) Upload a logo image
7. Click "Generate QR Code"
8. Click "Download QR Code" to save


TECHNICAL DETAILS
-----------------
- Pure client-side JavaScript - no backend required
- Uses qrcode-generator library v1.4.4
- Automatic error correction:
  * Medium (15%) for standard QR codes
  * High (30%) when logo is added
- QR codes include proper quiet zones for reliable scanning
- Works offline once loaded


BROWSER COMPATIBILITY
---------------------
Works in all modern browsers that support:
- HTML5 Canvas
- File API
- ES6 JavaScript


USAGE GUIDELINES
----------------
This project is free to use, modify, and incorporate into your own projects 
(personal or commercial).

However, please don't just repackage and sell it as-is. If you're going to 
sell something based on this, add your own value - customise it, improve it, 
integrate it into a larger product. That's the spirit of open source.


LICENCE
-------
MIT License

Copyright (c) 2025 David Walker

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicence, and/or sell
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


CREDITS
-------
Created by: David Walker & Claude Sonnet 4.5 (Anthropic)

Uses qrcode-generator library by Kazuhiko Arase
https://github.com/kazuhikoarase/qrcode-generator


REPOSITORY
----------
GitHub: https://github.com/davidianwalker1207/qr-generator


SUPPORT
-------
For issues, questions, or feature requests, please visit:
https://github.com/davidianwalker1207/qr-generator/issues


CONTRIBUTING
------------
Feel free to fork, modify, and submit pull requests. All contributions welcome.
Visit the repository to get started.


================================================================================
