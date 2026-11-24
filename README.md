# Dere Compatibility Chart

A 12×12 compatibility chart for anime "dere" types, as open data (CSV).

"Dere" types are character archetypes from anime and manga fandom. Each name joins a trait word with *dere-dere* (Japanese for lovey-dovey) to describe how a character acts toward someone they like: a **tsundere** is prickly first and warm later, a **kuudere** stays calm and flat, a **yandere** is devoted to the point of obsession.

This dataset is the compatibility table behind [DereMatch](https://derematch.com?utm_source=github&utm_medium=referral&utm_campaign=open_data), a free dere type test you can take with a partner. The interactive version of the chart is at **[derematch.com/dere-compatibility-chart](https://derematch.com/dere-compatibility-chart?utm_source=github&utm_medium=referral&utm_campaign=open_data)**.

Longer guides: [kuudere meaning](https://derematch.com/types/kuudere?utm_source=github&utm_medium=referral&utm_campaign=open_data), [dandere vs kuudere](https://derematch.com/types/dandere?utm_source=github&utm_medium=referral&utm_campaign=open_data), [deredere meaning](https://derematch.com/types/deredere?utm_source=github&utm_medium=referral&utm_campaign=open_data); all 12 types are summarised at [derematch.com/dere-types](https://derematch.com/dere-types?utm_source=github&utm_medium=referral&utm_campaign=open_data).

## The 12 types

| Type | Japanese | In one line | Best matches |
|---|---|---|---|
| Tsundere | ツンデレ | Prickly on the outside, soft as a marshmallow underneath. | Dandere, Deredere, Undere |
| Yandere | ヤンデレ | Sweet, devoted, and maybe just a little too all-in. | Undere, Dandere, Deredere |
| [Kuudere](https://derematch.com/types/kuudere?utm_source=github&utm_medium=referral&utm_campaign=open_data) | クーデレ | Calm, cool, collected, and secretly paying attention to everything. | Deredere, Bakadere, Hajidere |
| [Dandere](https://derematch.com/types/dandere?utm_source=github&utm_medium=referral&utm_campaign=open_data) | ダンデレ | Quiet at first, then the sweetest person in the room. | Deredere, Tsundere, Bakadere |
| [Deredere](https://derematch.com/types/deredere?utm_source=github&utm_medium=referral&utm_campaign=open_data) | デレデレ | Pure sunshine with a heart on both sleeves. | Dandere, Kuudere, Tsundere |
| Himedere | ヒメデレ | Royalty in love. Treat them like a princess (or prince) and watch them melt. | Undere, Deredere, Yandere |
| Kamidere | カミデレ | A self-declared god of love who might let you be their chosen one. | Undere, Dandere, Bakadere |
| Bakadere | バカデレ | Lovable chaos. Trips over their own feet and right into your heart. | Kuudere, Dandere, Kamidere |
| Undere | ウンデレ | Says yes to everything, especially to the one they love. | Kamidere, Himedere, Tsundere |
| Mayadere | マヤデレ | Dangerous, mysterious, and unexpectedly soft for one person only. | Bakadere, Kuudere, Sadodere |
| Sadodere | サドデレ | Teases you mercilessly because you are their favorite person. | Tsundere, Hajidere, Kuudere |
| Hajidere | ハジデレ | Turns bright red the second their crush says hello. | Sadodere, Kuudere, Deredere |

## Compatibility chart

Each cell is the base score for that pair, from 0 to 100. The chart is symmetric (Tsundere × Dandere = Dandere × Tsundere), so there are 78 distinct pairs including same-type pairs.

| | Tsundere | Yandere | Kuudere | Dandere | Deredere | Himedere | Kamidere | Bakadere | Undere | Mayadere | Sadodere | Hajidere |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| **Tsundere** | 58 | 55 | 66 | 88 | 90 | 52 | 42 | 74 | 86 | 44 | 84 | 68 |
| **Yandere** | 55 | 60 | 40 | 87 | 85 | 82 | 56 | 64 | 92 | 38 | 58 | 72 |
| **Kuudere** | 66 | 40 | 62 | 70 | 91 | 46 | 54 | 89 | 66 | 80 | 82 | 88 |
| **Dandere** | 88 | 87 | 70 | 64 | 94 | 60 | 80 | 87 | 72 | 46 | 45 | 70 |
| **Deredere** | 90 | 85 | 91 | 94 | 80 | 86 | 62 | 82 | 78 | 44 | 70 | 86 |
| **Himedere** | 52 | 82 | 46 | 60 | 86 | 50 | 40 | 66 | 92 | 52 | 58 | 68 |
| **Kamidere** | 42 | 56 | 54 | 80 | 62 | 40 | 50 | 85 | 90 | 60 | 44 | 72 |
| **Bakadere** | 74 | 64 | 89 | 87 | 82 | 66 | 85 | 68 | 76 | 80 | 48 | 74 |
| **Undere** | 86 | 92 | 66 | 72 | 78 | 92 | 90 | 76 | 56 | 62 | 40 | 74 |
| **Mayadere** | 44 | 38 | 80 | 46 | 44 | 52 | 60 | 80 | 62 | 50 | 84 | 42 |
| **Sadodere** | 84 | 58 | 82 | 45 | 70 | 58 | 44 | 48 | 40 | 84 | 60 | 90 |
| **Hajidere** | 68 | 72 | 88 | 70 | 86 | 68 | 72 | 74 | 74 | 42 | 90 | 62 |

In this table scores range from 38 (Yandere × Mayadere) to 94 (Dandere × Deredere).

## Files

| File | Contents |
|---|---|
| [`dere-compatibility.csv`](dere-compatibility.csv) | 78 unordered pairs: `type_a`, `type_b`, `score` (0–100), `title` (a short name for the pairing) |
| [`matrix.csv`](matrix.csv) | The same scores as a 12×12 symmetric matrix; first column and header row are type slugs |
| [`types.csv`](types.csv) | `slug`, `name`, `japanese`, `tagline`, `best_matches`, `hardest_matches` (semicolon-separated slugs) |

## How the scores are made

- **Base score (this dataset).** Each pair of types gets a hand-written base score from how their love styles fit: for example, a shy type next to a warm, talkative one scores high; two types that both need control score low. These are editorial judgments, not survey results.
- **Personal score (on the site).** When two people take the [DereMatch test](https://derematch.com?utm_source=github&utm_medium=referral&utm_campaign=open_data), each gets a profile on eight dimensions (warmth, openness, intensity, shyness, directness, playfulness, dominance, attachment). Their score starts from the base score above and is adjusted by a fixed formula: points for one partner leading and the other following, a direct partner with a shy one, teasing meeting an open heart, and shared warmth; points off when both partners are very intense or need very different amounts of closeness. The method is explained at [derematch.com/how-it-works](https://derematch.com/how-it-works?utm_source=github&utm_medium=referral&utm_campaign=open_data).

**For fun, not science.** Dere types are fictional tropes, not a psychological model. Nothing here predicts real relationships.

## Take the test with your partner

Find your own dere type and see how you match with your crush or partner at **[derematch.com](https://derematch.com?utm_source=github&utm_medium=referral&utm_campaign=open_data)**. Free, no sign-up.

## License

The data and text in this repository are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You may reuse and adapt them, including commercially, as long as you credit **DereMatch** with a link to [https://derematch.com](https://derematch.com), for example:

> Dere compatibility data from [DereMatch](https://derematch.com) (CC BY 4.0).
