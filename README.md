# ECCE AI Hub Uganda — AskDesk + Is My Centre Ready?

This build adds the second tool to the hub:

## Tool 1
ECCE AskDesk

## Tool 2
Is My Centre Ready?
ECCE Standards & Licensing Readiness Checker

The new readiness checker includes:
- Centre profile
- 25 readiness questions
- Readiness score
- Urgent action / Needs improvement / Mostly ready categories
- Priority gaps
- Corrective actions
- Source labels
- Downloadable self-check report

## Render settings

Build Command:

```bash
python -m pip install --upgrade pip setuptools wheel && pip install -r requirements.txt
```

Start Command:

```bash
python -m uvicorn app:app --host 0.0.0.0 --port $PORT
```

Pre-deploy Command: leave empty.
Root Directory: leave empty.
