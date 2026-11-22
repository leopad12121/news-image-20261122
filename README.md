# The World in One Day — Sunday 22 November 2026

[![make.fun](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/leopad12121/news-image-20261122/rank.svg)](https://make.fun/bounty/news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/leopad12121/news-image-20261122/reward.svg)](https://make.fun/bounty/news-image-20261122)

A one-image newspaper front page summing up the world's news of
Sunday 22 November 2026, entered in the
[make.fun bounty](https://make.fun/bounty/news-image-20261122).

`main.py` (Python 3.13, standard library only at module level) draws a
1024x1024 front page — masthead, lead story, a 2x2 grid and a sport strip —
with Pillow when it is available, and otherwise copies the shipped
`entry.png` so the program still exits 0 with the verified image.
It writes to `$MAKEFUN_OUTPUT_DIR/entry.png`, else `/output/entry.png`
when `/output` exists, else `./entry.png`. Deterministic: two runs
produce byte-identical output.

## The day's six stories

1. **COP31 climate talks collapse** (Antalya) — the EU rejects a final
   draft with no mention of fossil fuels; the summit ends with no deal.
   Sources: AFP, The Hindu.
2. **Iran strikes in the Gulf** — missiles hit an industrial site in
   Bahrain (two injured) as tankers are struck near the Strait of Hormuz.
   Sources: Reuters, AFP, Al Jazeera.
3. **Russian drone flattens Kyiv flats** — part of a five-storey block
   near Kyiv collapses; two killed, at least 14 missing.
   Sources: AP, Reuters.
4. **Cartel boss captured in Mexico** — special forces seize
   'El Chapo Isidro' in Sinaloa; 11 killed in the raid.
   Sources: AP, Al Jazeera.
5. **Factory fire in Indonesia** — a blaze at a candy factory in
   Cikande kills three workers; 36 missing.
   Sources: AP, Reuters.
6. **Verstappen wins in Vegas** — a third Las Vegas Grand Prix win in
   four years. Sources: AP, The Hindu.

## Run it

```sh
python3 main.py
# or: MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## License

MIT — see [LICENSE](LICENSE).
