# 👨‍💻 sujitharao93's LeetCode Journey

> Daily automated tracking of LeetCode progress — powered by GitHub Actions

---
## 📊 Live Stats

[![LeetCode Stats](https://leetcard.jacoblin.cool/sujitharao93?theme=dark&font=Karma&ext=heatmap)](https://leetcode.com/u/sujitharao93/)

&nbsp;

![Total Solved](https://img.shields.io/badge/dynamic/json?url=https://alfa-leetcode-api.onrender.com/sujitharao93&query=$.totalSolved&label=Total%20Solved&color=orange&style=for-the-badge)
![Easy](https://img.shields.io/badge/dynamic/json?url=https://alfa-leetcode-api.onrender.com/sujitharao93&query=$.easySolved&label=Easy&color=00b8a3&style=for-the-badge)
![Medium](https://img.shields.io/badge/dynamic/json?url=https://alfa-leetcode-api.onrender.com/sujitharao93&query=$.mediumSolved&label=Medium&color=ffa116&style=for-the-badge)
![Hard](https://img.shields.io/badge/dynamic/json?url=https://alfa-leetcode-api.onrender.com/sujitharao93&query=$.hardSolved&label=Hard&color=ff375f&style=for-the-badge)
![Ranking](https://img.shields.io/badge/dynamic/json?url=https://alfa-leetcode-api.onrender.com/sujitharao93&query=$.ranking&label=Ranking&color=blue&style=for-the-badge)

---

## 🗂️ Repo Structure

```
📁 leetcode/
├── 📁 logs/
│   ├── daily.csv         # Daily snapshot: solved counts, streak, active days, ranking
│   ├── heatmap.json      # Full submission calendar (date → submission count)
│   └── recent-ac.md      # Last 10 accepted submissions with links
└── 📁 reports/
    ├── badges.md          # All badges earned with dates
    └── week-YYYY-WXX.md  # Auto-generated every Sunday
```

---

## 🤖 Automation

| Workflow | Schedule | What it does |
|----------|----------|--------------|
| `leetcode-tracker.yml` | Daily @ 6 AM UTC | Logs stats, heatmap, recent AC submissions, badges |
| `leetcode-tracker.yml` | Every Sunday | Generates full weekly report |

---

## 📈 What Gets Tracked

| Data | File | Frequency |
|------|------|-----------|
| Easy / Medium / Hard / Total solved | `daily.csv` | Daily |
| Current streak | `daily.csv` | Daily |
| Total active days | `daily.csv` | Daily |
| Global ranking | `daily.csv` | Daily |
| Submission heatmap | `heatmap.json` | Daily |
| Recent AC submissions (last 10) | `recent-ac.md` | Daily |
| All badges + earned dates | `badges.md` | Daily |
| Full weekly summary | `week-YYYY-WXX.md` | Weekly (Sunday) |

---

## 📝 Recent Accepted Submissions

> 📄 [View latest accepted submissions](./leetcode/logs/recent-ac.md)

---

## 🎖️ Badges

> 📄 [View all earned badges](./leetcode/reports/badges.md)

---

## 📅 Weekly Reports

Weekly summaries auto-generated every Sunday in [`leetcode/reports/`](./leetcode/reports/).

Each report includes:
- ✅ Cumulative Easy / Medium / Hard / Total counts
- 🔥 Current streak & total active days
- 🏅 Global ranking
- 🎖️ Total badges earned
- 📝 Top 5 recent accepted submissions

---

## 🧠 About

Solving LeetCode daily to sharpen problem-solving skills and prepare for technical interviews.

- 🔗 [My LeetCode Profile](https://leetcode.com/u/sujitharao93/)

---

*Updated daily by GitHub Actions 🤖*
