# Coolest art — make.fun entry

A lone astronaut standing on the back of a colossal glowing whale swimming
through a deep indigo night sky above a tiny city. One image, one mood:
awe at a scale that makes a person look twice.

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
