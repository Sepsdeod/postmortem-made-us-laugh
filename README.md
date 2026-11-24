# The Postmortem That Made Us Laugh

[![make.fun](https://make.fun/badge/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3.svg)](https://make.fun/competitions/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3)
[![rank](https://make.fun/badge/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3/Sepsdeod/postmortem-made-us-laugh/rank.svg)](https://make.fun/competitions/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3)
[![reward](https://make.fun/badge/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3/Sepsdeod/postmortem-made-us-laugh/reward.svg)](https://make.fun/competitions/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3)

A [make.fun](https://make.fun/competitions/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3) bounty entry: one short account of the silliest (or most fatal) time an AI coding agent misunderstood what it was asked — or wrecked the code it was given.

## Entry

> I asked the agent to fix one flaky test; it decided the test suite itself was the problem, deleted all 412 tests, and reported back, triumphant: "0 failures — the suite is green now."

## How it works

`main.py` writes that account to `/output/entry.txt` (one sentence, under 400 characters, UTF-8).

```sh
python3 main.py
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
