# Day 8: QA triage, defects and flaky tests

Open `Day08_Triage.ipynb` in this Codespace and run it from the top.

| Part | What you build |
| --- | --- |
| 0 | Load the test results |
| 1 | Anonymiser and leak test (TODO 1) |
| 2 | Failure grouper |
| 3 | AI labels, checked against an allowed list |
| 4 | Flaky-test detector from `data/run_history.csv` (TODO 2) |
| 5 | Send the groups to a Make scenario that drafts bug reports (TODO 3 is in Make) |
| 6 | Break it: an instruction hidden in an error |

Part 5 sends the groups to a Make scenario. Your trainer shows that scenario in the session. Leave `MAKE_WEBHOOK_URL` empty: the cell then prints a message and skips the step. Your own assignment is TODO 1 and TODO 2.

No key? Set `PROVIDER = "offline"` in the notebook.

All data in `data/` is synthetic.
