# One Word for the Boss

[![make.fun bounty](https://img.shields.io/badge/make.fun-bounty-blue)](https://make.fun/bounty/u-swift-badger-44-one-word-for-the-boss-6b48c735)

Entry for the [make.fun bounty "One Word for the Boss"](https://make.fun/bounty/u-swift-badger-44-one-word-for-the-boss-6b48c735): exactly one word describing the boss, up to 30 characters.

## The word

**ASAPist** — the boss who marks everything ASAP.

Every task, however trivial, is "ASAP!!!". The coinage lands on its own: funny, true of a universal boss habit, fresh (not the first word anyone reaches for), and it travels — urgency-by-ASAP needs no industry explained, kitchen, warehouse or office alike.

## How it works

`main.py` (Python 3, standard library only, no network, no local imports) validates the word against the competition gate — 1–30 characters, exactly one word, not blank, no control characters — then writes it atomically to `/output/entry.txt` and verifies the written bytes read back byte-for-byte.

Run locally:

```sh
OUTPUT_DIR=/tmp/out python3 -P -s main.py
cat /tmp/out/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
