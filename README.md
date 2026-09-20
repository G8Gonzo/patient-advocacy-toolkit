# Patient Advocacy Toolkit

**Open-source, privacy-first complaint generator for patients.**

This is a static web tool. Everything runs in your browser. No data is sent to any server. You fill in your story, and it generates pre-filled complaint letters for the right agencies. You review, copy, and send them yourself.

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
- `process-map.md` — the full step-by-step attack plan
- `docs/resources.md` — verified links and statutes
- `LICENSE` — MIT
- `DISCLAIMER.md` — full liability waiver

## Privacy

This is static HTML/JS. No backend. No tracking. No cookies. Run it offline if you want. Source is yours to audit. When you press generate, nothing leaves your machine.

## License

MIT — use it, fork it, improve it.

## Disclaimer

This is a patient-to-patient gift. Not legal advice. Not medical advice. The author is not responsible for outcomes. Use at your own risk. See DISCLAIMER.md.

Built for patients who have to become their own case managers.