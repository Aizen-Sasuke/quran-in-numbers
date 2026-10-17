# Quran in Numbers

Static, dependency-free pages that visualise numerical patterns in the Qur'an, alongside the
text data used to count and cross-check them.

## Files

| File | What it is |
|------|------------|
| `match.html` | Main visualisation (dot spheres, moon arc, 332 = 332 matrix). |
| `match_1.html` / `match_2.html` / `match_3.html` | Larger iterations with the full verse set embedded. |
| `quran-uthmani-min.txt` | Uthmani Arabic text. |
| `en.sahih.txt` | Sahih International English translation. |
| `bn.bengali.txt` | Bengali translation. |
| `quranic-corpus-morphology-0.4.txt` | Quranic Arabic Corpus v0.4 (morphological annotation). |

## Run

Open any `.html` file in a browser. There is no build step and no dependencies.

## Data format

The translation / text files are pipe-separated, one verse per line:

```
surah|ayah|text
1|1|In the name of Allah, the Entirely Merciful, the Especially Merciful.
```

## Notes

- Several figures in the UI are flagged **verify counts** — the counts are presented for
  checking against the source text, not as settled claims.
- `quranic-corpus-morphology-0.4.txt` carries its own copyright header; keep that block intact.

## Credits

Quranic Arabic Corpus v0.4.
