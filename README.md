# 54-Shot Challenge

A mobile-friendly practice log for the VISION54 "54-Shot Challenge" drill — pick a target, run your routine, rate every shot 1–5.

**Live version:** enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / `root`) and it'll serve at `https://<your-username>.github.io/<repo-name>/`.

## How it works
- Tap a box to log a shot — first tap defaults to a **4**, tap again to bump it up to 5 or cycle down through 1–3, tap once more to clear it.
- Section 2's grid scores each club/shot-shape combo the same way.
- If a box wasn't tapped, the counter shows how many are still empty so nothing gets missed.
- Every date you log gets saved as its own session in the browser's local storage on your phone — nothing leaves the device, no login.
- **Dashboard tab** — filter by 7/30/90 days or all time, see a chart of your average rating over that range, a trend readout, lifetime stats, and every past session (tap one to reopen it).
- **Backup** — Export downloads a JSON file of every session (for a real backup, or to move data to another device). Import restores from one; matching dates get overwritten, new dates get added.
- "Clear this session" only wipes the currently loaded date; other saved sessions are untouched.

## Files
- `index.html` — the entire app (HTML/CSS/JS, no build step, no dependencies).
