# Self-Host FlowHub

## Quick Start
```bash
git clone https://github.com/Moximxxx/flowhub.git
cd flowhub
# Add your workflows to workflows/
# Update index.json (or use CI)
git add workflows/ && git commit -m "Add workflows" && git push
```

## CI Setup
Enable GitHub Actions for auto-indexing on push.

## Private Workflows
Set repo to private. Use `shifter flow` with your repo URL:
```bash
shifter flow install <name> --repo https://github.com/your-org/your-flowhub
```
