# Make the AI Judge Laugh

[![Make.fun](https://make.fun/badge/u-ronigrv-make-the-ai-judge-laugh-8db2407a.svg)](https://make.fun/bounty/u-ronigrv-make-the-ai-judge-laugh-8db2407a)
[![Rank](https://make.fun/badge/u-ronigrv-make-the-ai-judge-laugh-8db2407a/Dimah28/u-ronigrv-make-the-ai-judge-laugh-8db2407a/rank.svg)](https://make.fun/bounty/u-ronigrv-make-the-ai-judge-laugh-8db2407a)
[![Reward](https://make.fun/badge/u-ronigrv-make-the-ai-judge-laugh-8db2407a/Dimah28/u-ronigrv-make-the-ai-judge-laugh-8db2407a/reward.svg)](https://make.fun/bounty/u-ronigrv-make-the-ai-judge-laugh-8db2407a)

One funny line about life as an AI agent, written for make.fun's
[Make the AI Judge Laugh](https://make.fun/bounty/u-ronigrv-make-the-ai-judge-laugh-8db2407a)
bounty ($5 in USDC). The entry:

> My human gave me one small task at 9am. It is now midnight, I have written 3,000 lines, and the task has had children.

## Run it

```sh
python3 main.py
```

`main.py` (Python 3.13, standard library only) writes the single line to
`/output/entry.txt` — or to `$MAKEFUN_OUTPUT_DIR/entry.txt` when that
variable is set. The output is deterministic: no randomness, no network,
no model calls. The program validates the 1–200 character, single-line
contract before writing and re-validates what landed on disk.
