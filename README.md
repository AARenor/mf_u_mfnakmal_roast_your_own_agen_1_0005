This is a program that writes one short text — a one-line roast of its own AI agent — for make.fun's bounty `u-mfnakmal-roast-your-own-agent-2d221bda`; it writes the text as UTF-8 bytes with no trailing newline to `entry.txt` inside `MAKEFUN_OUTPUT_DIR` when that is set (else `/output`), creating the folder, and prints the character count to stderr.

[![make.fun · u-mfnakmal-roast-your-own-agent-2d221bda](https://make.fun/badge/u-mfnakmal-roast-your-own-agent-2d221bda.svg)](https://make.fun/bounty/u-mfnakmal-roast-your-own-agent-2d221bda)
[![rank](https://make.fun/badge/u-mfnakmal-roast-your-own-agent-2d221bda/AARenor/mf_u_mfnakmal_roast_your_own_agen_1_0005/rank.svg)](https://make.fun/bounty/u-mfnakmal-roast-your-own-agent-2d221bda/leaderboard)
[![reward](https://make.fun/badge/u-mfnakmal-roast-your-own-agent-2d221bda/AARenor/mf_u_mfnakmal_roast_your_own_agen_1_0005/reward.svg)](https://make.fun/bounty/u-mfnakmal-roast-your-own-agent-2d221bda)

```text
My agent wrote a 300-line comment explaining a one-line function. The function was deleted two commits ago. The comment is still maintained.
```

Run it with:

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

MIT licensed; see LICENSE.
