# SLO Burn Rate Predictor

Forecast SLO burn and trigger preventative mitigation actions.

## Priority Metadata

- ID: 125
- Domain: infrastructure
- TTE (days): 3
- Exposure score: 8/10
- Wave: 1
- Priority score: 7.60

## Phase-1 Build

1. Risk/exposure assessment API.
2. Deterministic launch planning endpoint.
3. Domain-tailored threat and rollout docs.
4. CI test gate and local runnable service.
5. Spatial 3D starter (for spatial projects).

## Run

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -e .[dev]
make test
make run
```
