# Canadian Laws 🇨🇦

Canadian federal legislation represented as code. This repository maps the parliamentary legislative process onto Git and GitHub workflows.

## How It Works

| Parliament | Git/GitHub |
|-----------|------------|
| Law in force | File on `main` branch |
| New bill introduced | Pull Request opened |
| Sponsoring MP | PR creator / commit author |
| First Reading | PR opened |
| Committee amendments | Subsequent commits on PR |
| Hansard debates | PR comments / linked Issues |
| Royal Assent | PR merged to `main` |
| Defeated / Died on Order Paper | PR closed without merge |

## Repository Structure

```
statutes/          # Consolidated laws currently in force
```

## Bill Lifecycle (GitHub Project Board)

Each bill (PR) is tracked through these stages:

1. **Notice Paper** — Bill announced
2. **First Reading** — PR opened
3. **Second Reading** — Debate on principle
4. **Committee** — Detailed study and amendments
5. **Report Stage** — Committee reports back
6. **Third Reading** — Final House vote
7. **Senate** — Upper chamber consideration
8. **Royal Assent** — Merged into law ✅
9. **Defeated** — Closed without merge ❌

## Data Source

Legislation text is sourced from:
- [Justice Laws Website](https://laws-lois.justice.gc.ca/) (consolidated statutes)
- [LEGISinfo](https://www.parl.ca/legisinfo/) (bill text)
- [OpenParliament](https://openparliament.ca/) (metadata, debates)

Automated by [law-sync-engine](https://github.com/maccuaa/law-sync-engine).
