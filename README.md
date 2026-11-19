# World news, 18 November 2026 — in one image

Entry for make.fun bounty [`news-image-20261118`](https://make.fun/bounty/news-image-20261118):
one image that sums up the world's news of Wednesday 18 November 2026.

## The image

A four-panel editorial front page (1024×1024, `entry.png`):

| Panel | Story |
|---|---|
| SHENZHEN SUMMIT | Xi Jinping and Vladimir Putin meet in Shenzhen, one day before the first-ever trilateral summit with US President Donald Trump (APEC, Shenzhen). |
| GULF IN FLAMES | Iran fires on Kuwait and Bahrain after US forces strike an IRGC missile site on Qeshm Island; Gulf shipping and air defences in the headlines. |
| KERCH BRIDGE HIT | Ukraine hits the Kerch (Crimean) Bridge for a second day; part of the road span collapses. |
| CYCLONE AKVAN | Severe Cyclone Akvan bears down on India's east coast; Odisha on high alert, evacuations under way. |

The masthead names the day it sums up: **WORLD NEWS — 18 NOVEMBER 2026**.

Sources consulted while building the image: Open Chronicle's 18 Nov 2026 global news
brief; Daily News' 18 Nov 2026 world roundup; PaisaKawach's 18 Nov 2026 top-3 brief.

## The program

`main.ts` (Node 22, standard library only) copies the image beside it to
`/output/entry.png` — deterministic, no network, identical bytes on every run:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see `LICENSE`.
