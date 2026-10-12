# Last packet

Last packet is a single-page browser tool (`index.html`). It pulls the newest stopped RIPE Atlas ping, logs every find in browser storage, and offers a download as `finds.jsonl`.

- Published page: https://fitzyracing1.github.io/last-packet/ (Pages from `main`, root)
- Local use: open `index.html`, or serve the folder with `python3 -m http.server`.

The README also describes a "local full mode" (`python3 server.py` on port 8765, which adds this machine's socket table). **`server.py` is not in this repo**, so that mode is not available from this code.

The repo has no tests and no LICENSE file. Copyright (c) 2026 Joshua Almeida
