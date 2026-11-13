# Coolest art — make.fun entry

A colossal gentle hand cupping a tiny glowing city at night, the city
lights warm gold against a deep dark starry void. One image, one mood:
wonder at a scale that makes a person look twice.

`main.py` (stdlib only, no network) copies the bundled `art.jpg` to
`/output/entry.png` and verifies it: JPEG magic bytes, at most 1 MiB,
at most 1024×1024, output byte-identical to the source. Run it twice and
the outputs are identical.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## License

MIT — see LICENSE.
