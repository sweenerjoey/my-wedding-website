# Traditional Typographic Scale

## Original Names, Point Sizes, REMs
| Name                | .pt  | rem   |
| :------------------ | ---: | ----: |
| Minion              | 7    | 0.583 |
| Bourgeois           | 9    | 0.75  |
| Long Primer         | 10   | 0.833 |
| Small Pica          | 11   | 0.917 |
| **Pica**            | 12   | 1     |
| English             | 14   | 1.167 |
| Great Primer        | 18   | 1.5   |
| Paragon             | 20   | 1.667 |
| Double Pica         | 24   | 2     |
| Double English      | 28   | 2.333 |
| Double Great Primer | 36   | 3     |
| Canon               | 48   | 4     |
| Double Canon        | 56   | 4.666 |
| Six Pica / Inch     | 72   | 6     |
| Eight Pica          | 96   | 8     |

## CSS Variables

--base-value: 100%;

--pt-minion: calc(var(--base-value) * 0.583);
--pt-bourgeois: calc(var(--base-value) * 0.75);
--pt-long-primer: calc(var(--base-value) * 0.833);
--pt-small-pica: calc(var(--base-value) * 0.917);
--pt-pica: var(--base-value);
--pt-english: calc(var(--base-value) * 1.167);
--pt-great-primer: calc(var(--base-value) * 1.5);
--pt-paragon: calc(var(--base-value) * 1.667);
--pt-double-pica: calc(var(--base-value) * 2);
--pt-double-english: calc(var(--base-value) * 2.333);
--pt-double-great-primer: calc(var(--base-value) * 3);
--pt-canon: calc(var(--base-value) * 4);
--pt-double-canon: calc(var(--base-value) * 4.666);
--pt-six-pica: calc(var(--base-value) * 6);
--pt-inch: calc(var(--base-value) * 6);
--pt-eight-pica: calc(var(--base-value) * 8);