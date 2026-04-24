# 👨‍💻 sujitharao93's LeetCode Journey

> Daily automated tracking of my LeetCode progress — powered by GitHub Actions

---

## 📊 Live Stats

![LeetCode Stats](https://leetcode-badge-showcase.vercel.app/api?username=sujitharao93&theme=dark)

&nbsp;

![Total Solved](https://img.shields.io/badge/dynamic/json?url=https://leetcode-stats-api.herokuapp.com/sujitharao93&query=$.totalSolved&label=Total%20Solved&color=orange&style=for-the-badge)
![Easy](https://img.shields.io/badge/dynamic/json?url=https://leetcode-stats-api.herokuapp.com/sujitharao93&query=$.easySolved&label=Easy&color=00b8a3&style=for-the-badge)
![Medium](https://img.shields.io/badge/dynamic/json?url=https://leetcode-stats-api.herokuapp.com/sujitharao93&query=$.mediumSolved&label=Medium&color=ffa116&style=for-the-badge)
![Hard](https://img.shields.io/badge/dynamic/json?url=https://leetcode-stats-api.herokuapp.com/sujitharao93&query=$.hardSolved&label=Hard&color=ff375f&style=for-the-badge)
![Ranking](https://img.shields.io/badge/dynamic/json?url=https://leetcode-stats-api.herokuapp.com/sujitharao93&query=$.ranking&label=Ranking&color=blue&style=for-the-badge)

---

## 🗂️ Repo Structure

```
📁 leetcode/
├── 📁 logs/
│   └── daily.csv          # Daily snapshot of solved counts + streak
├── 📁 reports/
│   └── week-YYYY-WXX.md   # Auto-generated every Sunday
└── 📁 solutions/          # (Optional) Your solution files
    ├── easy/
    ├── medium/
    └── hard/
```

---

## 🤖 Automation

| Workflow | Schedule | What it does |
|----------|----------|--------------|
| `leetcode-tracker.yml` | Daily @ 6 AM UTC | Logs solve count & streak to `daily.csv` |
| `leetcode-tracker.yml` | Every Sunday | Generates weekly markdown report |

---

## 📈 Progress Log

<!-- This section is updated automatically via GitHub Actions -->
> Latest stats are always reflected in the badges above.
> Check [`leetcode/logs/daily.csv`](./leetcode/logs/daily.csv) for the full history.

---

## 📅 Weekly Reports

Weekly summaries are auto-generated every Sunday in [`leetcode/reports/`](./leetcode/reports/).

Each report includes:
- ✅ Cumulative Easy / Medium / Hard counts
- 🔥 Current streak
- 📅 Total active days

---

## 🧠 About

I'm solving LeetCode daily to sharpen my problem-solving skills and prepare for technical interviews.

- 🔗 [My LeetCode Profile](https://leetcode.com/u/sujitharao93/)
- 📬 Feel free to connect or discuss solutions!

---

## 🚀 How to Use This Template

Want to set up the same automated tracking for yourself?

1. Fork this repo
2. Change `LEETCODE_USERNAME` in `.github/workflows/leetcode-tracker.yml`
3. Enable **Read & Write** permissions under Settings → Actions → General
4. Run the workflow manually once to verify

---

*Last updated automatically by GitHub Actions* 🤖
