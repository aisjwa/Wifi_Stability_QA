

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
