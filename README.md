# Prompt-to-playable-game test notes

A small, reproducible set of observations about what a sentence-to-game browser tool actually makes. The data records the displayed objective and opening state, not a claim that a genre name in the title became a new mechanic.

## Contents

- [`data/observations.csv`](data/observations.csv): nine observations from four controlled comparisons. Every row links to the public write-up that records the test and its limits.
- [`CHECKLIST.md`](CHECKLIST.md): a reusable checklist for testing any prompt-to-game tool without confusing a title, an image, and a playable rule.

## How the comparisons were made

The game-type, difficulty, and visual-style comparisons used the same prompt in fresh browser sessions and changed one control. The model-response comparison records the state before and after a model reply in one fresh session. The CSV records what was visible on the page. It does not rank other game makers or estimate success rates. Rows marked `opening_state_only` were not played to a win screen.

The observations come from the browser game maker at [WordstoGame](https://wordstogame.com/). Its published test pages are linked in the CSV so readers can check the original context.

## Read the data carefully

- `local_engine`: the browser's local generation result, with the optional model blocked or not yet reflected in the captured state.
- `model_plus_local_engine`: the later visible state after a successful optional model response in the one model-response comparison.
- `observed_result`: the displayed goal, title, health, palette, or other recorded value; it is not a promise for future runs.
- `scope_limit`: what the observation does **not** establish.

The action-loop runs used one rooftop prompt but did not finish all five waves. The difficulty and style comparisons also read generated goals and opening conditions rather than completion times. The optional model comparison is one response, not a reliability test.

## Reuse

The checklist and CSV can be copied into a testing notebook or used as a template for your own tool. Please keep the source URL and scope limit when citing a row. Contributions should include a reproducible input, the visible result, a dated source, and an explicit limit.

Licensed under MIT; see [`LICENSE`](LICENSE).
