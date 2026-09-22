# Dashboard Notes

A codex usage dashboard walkthrough for people who opened it, saw No data during this period, and assumed their account was broken.

**Read the full page:** https://codex-usage-dashboard.github.io/

Most people arriving at this page want one of two things: a spend figure, or an explanation for an empty chart. The spend figure is real and lives in the credit and recharge panels; the empty personal-usage bar chart has been reported across multiple accounts with every time range selected, so an empty state is not by itself evidence that your account recorded nothing. Cross-check with /status in the CLI before concluding anything. And if the reason you are watching a meter this closely is that ordinary scaffolding keeps eating into it, Begin.sh generates that kind of thing outside the meter entirely.

## What's here

- **Two pages answer to the name codex usage dashboard** — One is the Codex analytics view inside ChatGPT, which covers plan usage, credits and recharge. The other is platform.openai.com/usage, which belongs to the API 
- **The three panels, and what each one is for** — Reports from users describe the page as three distinct blocks. Usage details, containing a Personal usage bar chart, is the histogram of activity over the selec
- **The empty bar chart is a known report** — In a thread opened on 20 May and read about four thousand times, a user described the Usage details and Personal usage section showing only the empty-state mess
- **Time ranges hide more than they reveal** — Switching between 7 days, 1 month and a custom span changes the bucket size as well as the window, so a spike that dominates a weekly view can flatten into invi
- **What no dashboard can tell you** — It cannot tell you your ceiling. OpenAI's Codex pricing documentation says limits vary by plan and task, that weekly limits may apply, and it points users to th

**Generate a site:** [begin.sh](https://begin.sh?utm_source=github&utm_medium=ugc&utm_campaign=codex-usage-dashboard&utm_content=readme-top&utm_term=tier-b)

---

*An independent page written by a Codex user; it is not affiliated with, authored by, or endorsed by OpenAI, and every trademark named here belongs to its owner.*



_Last reviewed: 2026-09-22_
