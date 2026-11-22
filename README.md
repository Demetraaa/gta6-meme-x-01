[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/Demetraaa/gta6-meme-x-01/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/Demetraaa/gta6-meme-x-01/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

# Still Waiting for GTA VI

Entry for the make.fun bounty **gta6-meme-x-01**: a GTA 6 meme posted on X.

The meme: a two-panel photo, 2013 vs 2026. Same kid, same room, same
shirt, same controller — in 2013 he is a grinning boy in front of a CRT
TV; in 2026 he is a bearded grown man in the same dusty room, and the TV
still only says "VI — COMING SOON". Thirteen years, and the wait is the
game.

- The post: https://x.com/leho_04/status/2124582455751716886 (v4 — the 2013 vs 2026 meme;
  v3 was https://x.com/leho_04/status/2124098531845706229, the 217 GB meme;
  v2 was https://x.com/leho_04/status/2123602606144766381, the sick-day meme;
  v1 was https://x.com/leho_04/status/2123438737212530875)
- `POST.json` names the post; `main.ts` (Node 22, standard library only)
  copies it to the output folder for the gate and verifies it names a
  real X post.

Run it outside the grader with:

```
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```
