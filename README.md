# wedding-seating

Benson + Mecki wedding seating planner (GitHub Pages).

**Live:** https://bensonlok.github.io/wedding-seating/

## How saving works

1. **Auto-save (default)** — Every seat/guest/table change saves to this browser’s `localStorage`. Refresh keeps your **last update**.
2. **Publish shared** — Optional. Writes `data.json` on `main` via the GitHub Contents API so phone and laptop stay in sync. Needs a **fine-grained PAT** with Contents read/write on **this repo only**. The token stays in the browser only (never committed).
3. **Export / Import** — JSON backup if you want a file copy.
4. **Clear local** — Drop this device’s save and reload the shared GitHub plan.

Shared plan file: [`data.json`](./data.json) (`updatedAt` ISO timestamp).
