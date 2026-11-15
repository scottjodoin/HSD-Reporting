# HSD Reporting

Plain-language reports on what the Hanover School Division (Manitoba) board of trustees has decided, with every decision linked to its page in the official minutes. Live at https://hsdreporting.ca/ (GitHub Pages).

Independent: not affiliated with Hanover School Division.

## Reports

Issue histories, July 2013 to September 2026:

- [Religion in Hanover schools](religion-in-schools/): religious exercises, religious instruction and parent petitions
- [Gender, sexuality and classroom materials](gender-sexuality-materials/): the diversity policy, sexual-health classes, Policy AK, mature minors
- [Budgets, school taxes and spending](budget-taxes/): every budget and mill rate, provincial funding, borrowing, trustee pay
- [New schools and catchments](schools-growth/): enrolment growth, new schools and additions, portables, catchment changes
- [Programs, graduation and staff](learning-programs/): Grade 9, kindergarten, graduation policy, student services, teachers and EAs
- [Student safety, discipline and buses](safety-discipline/): safe schools and discipline policies, phones, threats, buses
- [COVID-19 in Hanover schools](covid-19/): closures, remote learning, masks, protests, 2020–2022
- [How the board governs itself](board-governance/): conduct, conflicts of interest, hiring, closed meetings, provincial oversight

About the site: [Ask your own AI about the board](ask-your-ai/) · [How these reports are made](how-its-made/) · [Data accuracy](data-accuracy/) · [Privacy](privacy/)

## Site layout

This is a plain static site for GitHub Pages (no Jekyll; see `.nojekyll`). It uses the same design as [Steinbach City Council Reporting](https://steinbachcitycouncilreporting.ca/).

```
index.html              Home page listing all reports
<slug>/index.html       One page per issue report (see Reports above)
how-its-made/, data-accuracy/  Method and accuracy pages
ask-your-ai/            Copy-ready prompts for researching the board with your own AI
llms.txt                Guide to every report, for AI assistants (regenerate when reports change)
sitemap.xml             List of pages for search engines
assets/css/style.css    Shared styles (follows the browser light/dark setting)
assets/css/report.css   Extra styles for multi-page topic reports
privacy/index.html      Privacy page
CNAME                   Custom domain (hsdreporting.ca)
robots.txt              Allows all crawlers
```

To add a report, create a new folder with an `index.html` that links `../assets/css/style.css`, then add it to the home page and to the list above.

## Report conventions

- **The board's record**: decisions, motions and vote counts from the minutes. Each one links to the page of the minutes PDF on hsd.ca (`#page=N`).
- **Names**: trustees and division staff are named. Members of the public are identified by initials only.
- **Limits stated plainly**: the minutes record vote counts, not how each trustee voted, and HSD doesn't publish meeting video. Each report has an "About this page" section saying what couldn't be confirmed.

The research data (OCR'd minutes, motions, attendance, trustee roster and verified corrections) is kept outside this repository.
