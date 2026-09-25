# Asset manifest

Binary files are tracked here until they are physically committed to Git.

| Asset | Intended repo path | SHA-256 | State |
|---|---|---|---|
| Original 10-page source PDF | `source/Agents_City_1-10.pdf` | `2be5548d280b21d6dbecbd455fd174ca9fcdfba75de567b11623f677c74ee612` | available in originating chat/container; **not yet committed** |
| C001 — request pink by phone | `approved/chapter-01/c001-request-pink.png` | `ddcdfb2812e542b152c0e755f260de42922aa8902182222284fda0a95865c79f` | **APPROVED**, current canonical image available in originating chat/container; binary sync pending |
| C002 — Rose appears already executing | `approved/chapter-01/c002-rose-executes.png` | `675f81531b3b5bbd8c2b6b2cc15c4b3cd233ee64e5b89e43ffa96069d8920ff4` | **APPROVED**, current canonical image available in originating chat/container; binary sync pending |
| C003 — delighted reaction | `approved/chapter-01/c003-perfect.png` | `81798ad233be63611c1cf56b94ea8c5f1f5f2e9ace4172d7f00be47408e55db5` | **APPROVED**, current canonical image available in originating chat/container; binary sync pending |

## Binary-sync limitation

The GitHub connector exposed in this chat can manage repository text/Git state and Git objects, but it does not expose a direct local-file upload handoff from the image-generation/container filesystem. Do not mark a binary as present in Git until its blob is actually committed.

The hashes above identify the approved assets byte-for-byte and prevent an older generated image from being mistaken for canon.
