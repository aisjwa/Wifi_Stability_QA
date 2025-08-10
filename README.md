# Wi‑Fi Roaming & Stability Tests (Public‑safe)

Demonstrates how to validate client roaming and session continuity between APs using **synthetic logs** and a test harness.
Good for showcasing intermediate/advanced QA practice (~4 yrs).

## Includes
- Roaming event parser (from dummy logs)
- Dwell time & re‑assoc timing analysis
- Packet loss during roam (simulated)
- Pytest checks + figures

> Replace dummy logs with your own **anonymized** captures later.

## Quick start
```bash
pip install -r requirements.txt
python scripts/generate_dummy_roam.py
python scripts/analyze_roam.py
pytest -q
```
