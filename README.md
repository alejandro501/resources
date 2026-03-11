# Resources

This folder stores reusable resources for the flow (mainly wordlists and supporting static assets).
Keep files here stable and generic so they can be reused across runs and targets.
Do not place sensitive client data or per-engagement secrets in this directory.

## Structure
- `wordlists/`: shared wordlists used by discovery/fuzzing modules.

## Notes
- Prefer adding new reusable lists here instead of duplicating them under `data/`.
- Use `data/` for run output and target-specific artifacts.
