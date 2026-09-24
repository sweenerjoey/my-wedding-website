# Typography

Back when fonts were physical pieces of moveable cut-metal letterpunches, font foundries and designers used (relatively) common names to refer to standard font sizes (called "bodies") in their cases. The below chart details 15 common American names to their point sizes, and then converts them to associated rem sizes based on a presumed ratio of **12pt &rarr; 16px &rarr; 1rem**. This "traditional typographic scale" forms a cohesive and, in my opinion beautiful, cascading waterfall that can be used in all manner of setting type.

## Traditional Typographic Scale
| Name                | pt   | rem   |
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
| Double Canon        | 56   | 4.667 |
| Six Pica / Inch     | 72   | 6     |
| Eight Pica          | 96   | 8     |

## CSS Variables
The below code can be copy-pasted into the `:root` of any theme CSS file to get usable variables for the traditional typographic scale. Note that all of the sizes are determined mathematically, with variable `--base-value` set to a default of 100%. This keeps the relationship between sizes intact even when the base size is changed (either manually in the CSS or automatically due to device zoom settings).
```
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
--pt-inch: calc(var(--base-value) * 6);
--pt-eight-pica: calc(var(--base-value) * 8);

font-size: var(--base-value);
```
