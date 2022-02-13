# Web API: Clipboard.write() Examples for Chrome
At the time of writing this, the Web API: Clipboard.write() is still being implemented and these are some examples for me for future bits of work. 

The core piece around this is for `text/html` which seems to also need a `text/plain` backup on the clipboard. 

Check the simple [index.html](index.html) file to see four different examples:
1. Copying plain text to the clipboard
2. Copying raw HTML as plain and plain text to the clipboard
3. Copying plain fallback text and formatted HTML to the clipboard
4. A failing copying only formatted HTML to the clipboard

To see live, check out the [Github Pages](https://nikouu.github.io/Web-API-Clipboard.write-Examples/) for this repo.