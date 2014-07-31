css-inliner
=========

A CLI interface for [juice](https://github.com/andrewrk/juice).

# Install

```
npm install spreaker-css-inliner
```


# Usage


```
Read an input file or stdin, inline styles and save the output to a new file or stdout.

Options:
  -i, --input          Input file
  -o, --output         Output file
  -p, --preserve-mq    Preserve media queries  [default: false]
  -r, --remove-styles  Remove styles tag       [default: false]
  -h, --help           Show this help

```

### Example: read from a file and save to another one

```
inline -i input.html -o output.html
```

### Example: read from stdin and write to stdout

```
cat input.html | inline > output.html
```