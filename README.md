# flacrecompress

Re-compress FLAC files in parallel and report total savings.

## Dependencies

- `flac` for re-compressing FLAC files
- `metaflac` for stripping padding and pictures
- GNU `parallel` for parallel processing

## Usage

```
Usage:
    flacrecompress [options] -- files ...

Options:
    -h, --help:
        display this help

    -s, --silent:
        don't print progress to stderr

    -r, --raw-output:
        produce a single output line with the number of bytes saved

    -p, --parallel:
        run parallelized via GNU parallel
```
