# Quran in Numbers

A static, dependency-free page that visualises numerical patterns in the Qur'an, alongside the
text data used to count and cross-check them.

## Files

| File | What it is |
|------|------------|
| `index.html` | The app. Self-contained: embedded verse data, interactive reader, side-by-side comparisons, word search. No build step. |
| `quran-uthmani-min.txt` | Uthmani Arabic text. |
| `en.sahih.txt` | Sahih International English translation. |
| `bn.bengali.txt` | Bengali translation. |
| `quranic-corpus-morphology-0.4.txt` | Quranic Arabic Corpus v0.4 (morphological annotation). |

## Run

Open `index.html` in a browser. There is no build step and no dependencies.
Named `index.html` so GitHub Pages can serve it directly.

## Data format

The text files are pipe-separated, one verse per line:

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
