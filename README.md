# India Agent Skills 🇮🇳

Ready-made skills that teach AI agents (OpenClaw, Claude Code, Codex, Cursor) to handle **Indian** tasks correctly: tax, GST, mutual funds, banking and more.

| Skill | What it does | Status |
|---|---|---|
| [india-income-tax](india-income-tax/) | New vs old regime tax, HRA, 80C, NPS, monthly TDS, break-even deductions (Tax Year 2026-27, Income-tax Act 2025) | ✅ Live |
| india-gst | GST invoices, reverse GST, GSTIN validation | 🔜 Coming soon |
| india-mutual-funds | NAV lookup, portfolio value and returns | 🔜 Coming soon |

## Install a skill
```bash
openclaw skills install india-income-tax        # OpenClaw
```
Claude Code: copy the skill folder into `~/.claude/skills/`.

## Quick try
```bash
cd india-income-tax
python3 scripts/tax.py '{"salary": 1800000, "age": 30, "sec_80c": 150000}'
```

⭐ Star this repo to get updates — every Union Budget the numbers are updated within a day.

*Estimates only, not tax or financial advice. Confirm with official calculators or a CA.*
