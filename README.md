# devin-timing-plugin

A Devin plugin whose hooks append one line per hook event to `~/devin-plugin-hook-events.jsonl`:
`<epoch seconds> plugin <cwd> <event JSON>`. Tool output is reduced to its `success` flag.

The Darting Journey Benchmark installs it org-wide in Devin to record Devin's step timeline. It is public because Devin fetches org plugins with a plain `git clone` on outpost machines.
