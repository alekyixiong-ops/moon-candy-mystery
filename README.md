# Charlotte's Moon-Candy Library 🌙🍬

A little website made for Charlotte: one illustrated detective story, two Cantonese
learning games, and a shelf of maths and science labs.

**Open it here: <https://alekyixiong-ops.github.io/moon-candy-mystery/>**

## What's inside

| Shelf | Pages |
| --- | --- |
| 📖 Story | [The Mystery of the Moon-Candy Secret](story.html) — 8 chapters, 3 clues, 1 rotten trick |
| 🎮 Games | [Cantonese Village](cantonese-village.html) (English / 简体中文) · [Bao Bao's Cantonese Quest](bao-bao.html) |
| 🔢 Maths Lab | [Fraction Lab](fraction-lab.html) · [Trig Lab](trig-lab.html) · [E-Notation Game](e-notation-game.html) · [Rand Lab](rand-lab.html) · [Calculator Decoder](calculator-decoder.html) · [Button Box](button-box.html) |
| 🔬 Science Lab | [Oobleck Lab](oobleck-lab.html) · [Yeast Breath Lab](yeast-lab.html) · [Rock Cycle](rock-cycle.html) · [Granite vs Volcanic Tuff](rocks-guide.html) · [Rock Detective Notebook](rock.html) |
| 🕵️ Codes & Words | [Key-Jumble Code](secret-code.html) · [Shopping List Code](shopping-list-code.html) · [Not-So-Easy Shopping List](counting-code.html) · [Jumble Machine](jumble-machine.html) |
| 🐾 Guardians | [Carrie](carrie.html) · [Carrie, Marie & Parrie](trio.html) |

## How it works

Every page is a single self-contained `.html` file — all styling, art (inline SVG) and
JavaScript lives inside the page. There is no build step, no framework and no dependencies.

To publish, push to the `main` branch; GitHub Pages serves the repository root.

```bash
git add -A
git commit -m "Add navigation homepage"
git push
```

To preview locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000/
```

## Credits

Stories and ideas by Charlotte ✦ code and pictures by Alice the fairy 🧚
