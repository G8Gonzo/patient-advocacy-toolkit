# Patient Advocacy Toolkit

**Open-source, privacy-first complaint generator for patients.**

This is a static web tool. Everything runs in your browser. No data is sent to any server. You fill in your story, attach documents, and it generates pre-filled complaint letters and forms for the right agencies. You review, download, and send them yourself.

## Why this exists

Patients who are sick, tired, or not fluent in medical bureaucracy get dismissed. This levels the field by turning the slow, paper-heavy process into a guided, fillable one. The system has layers of bureaucracy; this gives you a single lever.

## How it works (the process)

1. **Document everything** — dates, names, what was said, what was promised, what failed.
2. **Try internal first** — patient advocate / patient relations at the facility. Get it in writing. Request a written response.
3. **If unresolved, escalate in parallel** (you can hit multiple at once):
   - State Medical Board (for the doctor)
   - Hospital Patient Advocate / Grievance (if hospital)
   - The Joint Commission (if accredited facility) — note: they shred medical records, so summarize only
   - HHS Office for Civil Rights (OCR) — for HIPAA, discrimination, or rights violations (180-day window for privacy)
   - State Department of Health / CMS for facility quality
   - Medicare BFCC-QIO if Medicare
4. **Keep copies of everything.** Reference numbers matter.

## Files

- `index.html` — the generator (open in any browser)
- `process-map.md` — the full step-by-step
- `templates/` — pre-filled letter templates for each agency
- `docs/` — resources and links

## Privacy

This is static HTML/JS. No backend. No tracking. Run it offline if you want. Source is yours to audit.

## License

MIT — use it, fork it, improve it.

Built for patients who have to become their own case managers.