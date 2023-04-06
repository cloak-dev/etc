# Environment Setup

## Requirements
A recent web browser, running either Blink or Webkit, with support for the following APIs and technologies

 - WebCrypto
   - Full implementation as per W3C standards
 - ES6 ECMAScript
 - Full Extensions API
   - Chrome Extensions in chromium-based browsers
     - Must support Manifest v3
   - Firefox Addons in Firefox
     - Manifest v2 is supported

## Target application

Cloak is an extension that operates on a target web-based messaging application running in the browser itself. Thus, it needs to be able to inject scripts into the application. As such, this application cannot be run in a locked-down browser.

## Steps to set up environment

1. Download the latest version of your favorite Chromium or Firefox -based browser.
2. If you're in a corporate environment, you might need to enable extensions. Consult your IT admin for steps to do the same.
3. Once you have access to the extension store, install the Cloak extension to your browser.
4. The extension will be active whenever you point your browser to a supported messaging application.

