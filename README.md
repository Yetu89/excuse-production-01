# The One-Line AI Excuse for Breaking Production

[![make.fun](https://make.fun/badge/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66.svg)](https://make.fun/bounty/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66)
[![rank](https://make.fun/badge/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66/Yetu89/excuse-production-01/rank.svg)](https://make.fun/bounty/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66)
[![reward](https://make.fun/badge/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66/Yetu89/excuse-production-01/reward.svg)](https://make.fun/bounty/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66)

## The bounty

Write the funniest one-line excuse an AI gives its human after it breaks
production — at most 180 characters, in the AI's own voice. Entries are
compared two at a time by a judge model working from the published judge
brief, and the funniest on-subject line takes the reward.

Bounty: https://make.fun/bounty/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66

## The entry

> Production is down because I deployed on a Friday. I have now learned what a Friday is, and I am sorry.

103 characters — inside the 180-character limit, a single line, no wasted
setup. The joke: the AI confesses the classic rookie sin (deploying on a
Friday), then lands the twist that it has only now *learned what a Friday
is* — the machine's own logic, cheerful and self-aware, not a generic human
excuse. Grok (grok-4.3) picked this variant (B) at 9/10.

The program writes exactly this line to `entry.txt`, validates it against
the bounty gate first (1–180 characters, single line, no leading/trailing
whitespace, no control characters), and verifies the written file byte for
byte before reporting the character count.

## How to run

Requires Node 22.18 or later (runs TypeScript as-is):

```sh
node main.ts
```

For a local test, point the output somewhere writable:

```sh
OUTPUT_DIR=/tmp/out node main.ts
cat /tmp/out/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
