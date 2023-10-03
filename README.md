# Package Manager

This package is a web-compatible package manager built with tsserverlib
compatibility in mind. It does not require a "real" filesystem or a "real" NPM
installation, but instead uses [orogene](https://github.com/orogene/orogene)
to perform package management operations.

It is largely a thin wrapper around Orogene's [node-maintainer WASM
API](https://github.com/orogene/orogene/blob/abba96e6662c3465a498fbe6154ffcf2fe33fac4/crates/node-maintainer/src/wasm.rs).