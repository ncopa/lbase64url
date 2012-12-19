A Lua module for URL safe base64 encoding/decoding.

This library is based on lbase64, but will only use URL safe characters
for the encoded string.

To use:

base64url = require('base64url')

encoded = base64url.encode("some text")

decoded = base64url.decode(encoded)


