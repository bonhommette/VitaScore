# VitaScore — MVP Demo

Preventive AI health scoring for seniors 65+ in France.

**Live demo:** _enable GitHub Pages on this repo (Settings → Pages → Branch: `main`, folder: `/`) — the URL will appear after about a minute._

---

## What this is

A single-file working MVP of **VitaScore**, a monthly health check-in for seniors. The user (or their family caregiver) answers 12 short questions on sleep, mobility, pain, mood, social contact, and medication. The app:

1. Computes a **VitaScore** between 0 and 100, with a medically-aligned scoring grid.
2. Shows a clean result page with a score gauge and a category breakdown.
3. **Sends a real email** with the report via [Formsubmit](https://formsubmit.co) (free, no signup).
4. Lets the user **subscribe to recurring reminders** (every 14 or 30 days).
5. Stores history locally and lets the user **log in by email** to view a chart of all past scores.

Everything runs client-side. No backend. No build step. No dependencies.

## How to run

Just open `index.html` in any browser. That's it.

For a public URL, push this folder to a GitHub repo and enable GitHub Pages.

## Project context

Built as the working MVP for a startup pitch — VitaScore turns the 5-year gap between official French senior health check-ups into a monthly signal, alerting families before a preventable hospitalisation. 30% of senior hospitalisations in France are preventable; VitaScore exists to catch them earlier.

The full pitch deck, PRD, and business model are in the parent project.

## Stack

- HTML, CSS, vanilla JavaScript — single file, no build.
- `localStorage` for history and reminder preferences.
- [Formsubmit](https://formsubmit.co) for the real email send (free tier).
- Inline SVG for the score chart.

## License

MIT — feel free to fork.
