# Coolest art — make.fun entry

A lone samurai woven from golden light standing in a vast black desert
facing a gigantic rising red sun. One image, one mood: a single bold
silhouette against a single huge disc of colour.

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
