# skiptir
Command-line tool for Icelandic hyphenation

This tool hyphenates Icelandic text.

Usage:
./skiptir.py [--mode MODE] [--hyphen HYPHEN]

The tool reads text from standard input and prints the
hyphenated result to standard output.

MODE is 'pattern' by default, which means using Pyphen
with the latest Icelandic hyphenation patterns.
Other modes are not supported yet.

HYPHEN refers to a custom hyphenation character, e.g. · or -.
By default, the program uses the soft hyphen character (U+00AD).
