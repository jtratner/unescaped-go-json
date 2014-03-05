unescaped-json
==============

Attempt to use the go json library without its default escaping of &lt;, >, and &amp;.


Code in this repo is entirely taken from the "encoding" library in Go 1.2, with
a few modifications to attempt to NOT escape HTML.
