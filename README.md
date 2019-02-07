# Konfig

This is a POC.  I'm screwing around here.

A minimalists' take on kubernetes configs.  Only provide the
options needing changed.  Configs are generated from the universal
configuration language ([libucl][1]), and subsequently validated against
kubernetes schemas.

Konfig supports variable expansion, and base configs, for sharing defaults
across clusters.

> Why python?

Dislike initalizing Go's anonymous structs, and working with dicts
in python is trivial.

[1]: https://github.com/vstakhov/libucl

## Usage

TODO: See tests/

## License

MIT
