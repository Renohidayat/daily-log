# 📅 Daily Log

Auto-generated daily log to maintain GitHub activity. Powered by GitHub Actions.

## How It Works

A GitHub Actions workflow runs on a **randomized schedule** across the week, generating varied content types:

| Type | Description |
|------|-------------|
| 📝 Daily Log | Append entry to `log.md` |
| 📊 Progress | Weekly progress files in `progress/` |
| 💡 TIL | Today-I-Learned notes in `til/` |
| 📈 Stats | Auto-calculated repo statistics |
| 📓 Journal | Monthly journal entries in `journal/` |

## Setup

1. Fork or clone this repo
2. Edit `.github/workflows/auto-commit.yml`:
   - Replace `nama-kamu` with your GitHub username
   - Replace `email-terverifikasi-kamu@github.com` with your **verified** GitHub email
3. Push to GitHub
4. Go to **Settings → Actions → General** → set "Workflow permissions" to **Read and write**
5. Done! The workflow runs automatically on schedule

## ⚠️ Important Notes

- The email in `git config` **must** be a verified email on your GitHub account, otherwise commits won't count as contributions
- GitHub Actions cron uses **UTC** timezone and can have delays of a few minutes
- If the repo has no activity for 60 days, GitHub may auto-disable the workflow. Visit the repo periodically or trigger manually via `workflow_dispatch`
