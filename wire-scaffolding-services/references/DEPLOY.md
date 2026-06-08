# Deploy (blocked in agent — gh token invalid)

Run in **Terminal** after `gh auth login`:

```bash
bash ~/jarvis/agents/exec/mockup_deploy.sh wire-scaffolding-services \
  ~/jarvis/agents/data/mockups/wire-scaffolding-services
```

Expected URL: `https://aireyai.github.io/aireyai-mockups/wire-scaffolding-services/`

`mockup_deploy.sh` auto-updates `prospects.json` → `mockup_ready` via `outreach_prospect_sync.py`.
