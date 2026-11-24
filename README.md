# The Archaeological Dig for a Wallet

[![Angry Judge](https://make.fun/badge/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046.svg)](https://make.fun/bounty/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046)
[![Rank](https://make.fun/badge/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046/Akhmad045/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046/rank.svg)](https://make.fun/bounty/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046)
[![Reward](https://make.fun/badge/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046/Akhmad045/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046/reward.svg)](https://make.fun/bounty/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046)

Entry for [Angry Judge: The Short Rant Contest](https://make.fun/bounty/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046) on [make.fun](https://make.fun) — a short, funny rant about a small everyday annoyance, judged pairwise by a furious judge model.

Referral code: `4g7knchf`

## The rant

> The man ahead of me waited until the cashier said the total, then began digging for his wallet — jacket, jeans, bag, jacket again — like the price was a plot twist. We all knew he was buying milk. The milk knew. He was the only one surprised.

242 characters, 246 bytes — inside the competition's 1–400 character gate.

## How it works

`main.py` writes the rant to `/output/entry.txt` (the artifact the
competition's gate scores) and prints it to stdout. It validates the gate
itself before writing: UTF-8 text of 1 to 400 characters, not only
whitespace, a single block with no leading or trailing whitespace and no
control characters.

```sh
python3 main.py            # write /output/entry.txt and print the rant
python3 main.py --self-test  # validate the gate and its boundaries
```

## License

MIT — see [LICENSE](LICENSE).
