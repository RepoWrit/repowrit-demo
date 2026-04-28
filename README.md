| File | Description |
|---|
| [REPOWRIT.md](./REPOWRIT.md) | A mock Executive Briefing generated from this repo's commit history — Founder, PM, and CTO views including Tech Debt Trends, Time-Saved Metrics, and Business Impact scores. |
| `README.md` | You're reading it. |

# repowrit-demo

**A live example of what RepoWrit generates.**

This repository exists as a demonstration of RepoWrit's automated documentation and executive briefing capabilities. The commit history is real — the AI-generated outputs in [REPOWRIT.md](./REPOWRIT.md) are what RepoWrit produces from those commits.

---

## What's Inside

| File | Description |
|---|---|
| [REPOWRIT.md](./REPOWRIT.md) | A mock Executive Briefing generated from this repo's commit history — Founder, PM, and CTO views including Tech Debt Trends, Time-Saved Metrics, and Business Impact scores. |
| `README.md` | You're reading it. |

## How It Works

When you connect a repository to RepoWrit:

1. **Every push** triggers Claude 4.5 to analyze the commit diff.
2. **Documentation PRs** are opened automatically on the `repoWrit/docs-update` branch — with a self-correcting agent that retries up to 3 times if CI fails.
3. **Executive Briefings** synthesize recent activity into Founder / PM / CTO summaries, sent every Monday by email on paid plans.
4. **Architecture Maps** visualize your module structure and dependency graph (cached for 24 hours, refreshable on demand).
5. **Ask RepoWrit** lets you query your codebase in plain English using semantic search across every commit summary.
6. **PR Reviews** (BYOK and above) post a severity-graded review comment on every external pull request.

This demo repo shows the output of step 3. To see the full experience — automatic docs, semantic search, architecture mapping, PR reviews, and weekly briefings — [install RepoWrit](https://repowrit.com) on your own repositories.

## Try RepoWrit

RepoWrit works with any GitHub repository. Install the app and push code — results appear in under a minute. Your first sync analyzes the last 3 commits so you have an instant baseline.

- [Sign up free →](https://repowrit.com)
- [See pricing →](https://repowrit.com/pricing) — Hobbyist (free), BYOK ($4.99/mo), Team ($20/seat/mo), Enterprise ($49.99/seat/mo)
- [Read the changelog →](https://repowrit.com/changelog)
