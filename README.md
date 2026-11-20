# The World — Friday, 20 November 2026

[![make.fun](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/kkazushi-eng/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/kkazushi-eng/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120)

An entry for the [make.fun](https://make.fun/bounty/news-image-20261120)
competition **news-image-20261120**: sum up 20 November's world news in one
image.

## What the image shows

A front page, "THE WORLD — Friday, 20 November 2026", built from four
pictures made for this entry:

- **Lead story — the Shenzhen summit.** Donald Trump, Xi Jinping and
  Vladimir Putin held their first three-way meeting in China, ending with a
  "Declaration Towards Peace": talks on nuclear arms and UN reform, but no
  breakthrough.
- **Cyclone Akvan slams India's east coast.** About 300,000 people were
  evacuated as the storm made landfall in Odisha.
- **UN court: Myanmar committed genocide.** The International Court of
  Justice in The Hague ruled that the 2017 crackdown on the Rohingya was
  genocide.
- **Also today.** NASA's Voyager 1 phones home from one light-day away;
  Anthropic's record $2 trillion stock-market debut; a Houthi strike damages
  Riyadh's tallest tower.

## How it runs

`main.py` (Python 3.13, standard library only) copies the bundled
`entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output/entry.png`).
It uses no network and writes byte-identical output on every run.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## License

MIT — see [LICENSE](LICENSE).
