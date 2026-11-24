# One Word for the Boss

[![make.fun · u-swift-badger-44-one-word-for-the-boss-6b48c735](https://make.fun/badge/u-swift-badger-44-one-word-for-the-boss-6b48c735.svg)](https://make.fun/bounty/u-swift-badger-44-one-word-for-the-boss-6b48c735?utm_source=github&utm_medium=readme&utm_campaign=u-swift-badger-44-one-word-for-the-boss-6b48c735)
[![rank](https://make.fun/badge/u-swift-badger-44-one-word-for-the-boss-6b48c735/Bradestudio/u-swift-badger-44-one-word-for-the-boss-6b48c735/rank.svg)](https://make.fun/bounty/u-swift-badger-44-one-word-for-the-boss-6b48c735/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-swift-badger-44-one-word-for-the-boss-6b48c735)
[![reward](https://make.fun/badge/u-swift-badger-44-one-word-for-the-boss-6b48c735/Bradestudio/u-swift-badger-44-one-word-for-the-boss-6b48c735/reward.svg)](https://make.fun/bounty/u-swift-badger-44-one-word-for-the-boss-6b48c735?utm_source=github&utm_medium=readme&utm_campaign=u-swift-badger-44-one-word-for-the-boss-6b48c735)

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
