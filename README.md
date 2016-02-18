js-signer
=========

<strong>Important updates</strong>: this code won't reliably work anymore. If you don't need smartcard support, use the experimental web crypto API. If you need smartcard support, you'd need an extra plugin, e.g. <a href="http://open-eid.github.io/">this one</a>

Digitally sign content by using only javascript. Smart cards are supported. Self-signed certificates may or may not work.

Supported browsers: Internet Explorer (CAPICOM), Firefox (window.crypto)

Chrome and Safari will implement this whenever the <a href="https://wiki.mozilla.org/Privacy/Features/DOMCryptAPISpec/Latest">DOMCrypt standard</a> is defined by W3C.

You can read this <a href="http://techblog.bozho.net/?p=1306">relevant blogpost</a>.
