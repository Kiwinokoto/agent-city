# Asset manifest

Binary files are tracked here until they are physically committed to Git.

| Asset | Intended repo path | SHA-256 | State |
|---|---|---|---|
| Original 10-page source PDF | `source/Agents_City_1-10.pdf` | `2be5548d280b21d6dbecbd455fd174ca9fcdfba75de567b11623f677c74ee612` | available in originating chat/container; **not yet committed** |
| C001 candidate — request pink | `approved/chapter-01/c001-request-pink.png` | `a852d27670f545f8b1d05c15da917abcde3955689f8c08b0403458b52a9a4418` | exact crop of the previously accepted top scene; awaiting explicit final confirmation / binary sync |

## Binary-sync limitation

The GitHub connector exposed in this chat can manage repository text/Git state, but it does not expose a practical local-file upload primitive for multi-megabyte PDF/PNG bytes. Do not mark a binary as present in Git until its blob is actually committed.

The hashes above let a later upload be verified byte-for-byte.
