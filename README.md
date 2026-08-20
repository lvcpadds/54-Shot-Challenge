# 54-Shot Challenge

A mobile-friendly practice log for the VISION54 "54-Shot Challenge" drill — pick a target, run your routine, rate every shot 1–5.

**Live version:** enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / `root`) and it'll serve at `https://<your-username>.github.io/<repo-name>/`.

## How it works
- Tap a box to log a shot — first tap defaults to a **4**, tap again to bump it up to 5 or cycle down through 1–3, tap once more to clear it.
- Section 2's grid scores each club/shot-shape combo the same way.
- Every date you log gets saved as its own session in the browser's local storage on your phone — nothing leaves the device, no login.
- The **Session history** card at the bottom shows lifetime sessions logged, your all-time average rating, and your best single session, plus a tappable list of every past date. Tap a past date to reload and review (or keep editing) that session.
- The date field switches which session you're editing — pick an old date to revisit it, or today's date to start fresh.
- "Clear this session" only wipes the currently loaded date; other saved sessions are untouched.

## Files
- `index.html` — the entire app (HTML/CSS/JS, no build step, no dependencies).
