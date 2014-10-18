# Chrome QR Code Extension
A Google Chrome extension that shows the current URL as a QR code.

I often use this to quickly copy a URL to my smartphone.

It uses Kazuhiko Arases javascript library (http://www.d-project.com/) to
draw the QR codes instead of relying on some third-party web API (like
all of the other extensions I looked at. Wtf?).

## Installing

[![available in the Chrome Web Store](https://ge1.me/1d7ddd4316ce41c58f50/raw)](https://ge1.me/de51b3b6d4db4229ab87)

## Installing (for developers)

1. Clone the repository somehwere.
2. Go to `chrome://extensions`
3. Make sure the "Developer mode" checkbox is on
4. Click "Load unpacked extension"

## Building

    gem install crxmake
    ./pack.rb

Author: Felix Kaiser <felix.kaiser@fxkr.net>
License: MIT (see LICENSE)
