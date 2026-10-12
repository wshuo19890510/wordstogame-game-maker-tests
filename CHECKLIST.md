# Prompt-to-game evaluation checklist

Use this when a tool claims to turn a sentence into a game. Record **what you saw** separately from what the product page promises.

## Set up a fair run

- [ ] Write one exact prompt with a player action and obstacle.
- [ ] Record the date, browser state, selected game type, difficulty, style, and optional settings.
- [ ] For a comparison, hold the prompt and all other controls fixed; change only one input.
- [ ] Note whether the result came from a local fallback or a later model response.

## Inspect the playable result

- [ ] Copy the displayed objective and control instructions exactly.
- [ ] Check whether the requested verb has a corresponding input and game rule. A matching title is not enough.
- [ ] Record the opening state separately from any progress you actually played through.
- [ ] If claiming completion, play until the win or loss condition appears and record that screen.
- [ ] If claiming mobile or keyboard support, test that input path and state the viewport or device used.

## Check what the user can keep

- [ ] Try the share link in a fresh session. Does it preserve a finished run, or only recreate settings?
- [ ] If a copy/export button exists, inspect the actual copied or downloaded content.
- [ ] Record login, payment, file size, duration, and usage limits only when a page or test makes them visible.
- [ ] Distinguish an observed free run from a promise of unlimited free use.

## Evidence record template

```text
Date:
Tool and page URL:
Exact prompt:
Controls and settings held fixed:
One variable changed:
Source badge or model status:
Displayed objective:
Observed controls and opening state:
Playthrough endpoint, if any:
Copy/share/export result, if tested:
Screenshot or public source:
What this test cannot establish:
```
