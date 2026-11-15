# HSD Reporting

Plain-language reports on what the Hanover School Division (Manitoba) board of trustees has decided, with every decision linked to its page in the official minutes. Live at https://hsdreporting.ca/ (GitHub Pages).

Independent: not affiliated with Hanover School Division.

## Reports

The first reports are in preparation.

## Site layout

This is a plain static site for GitHub Pages (no Jekyll; see `.nojekyll`). It uses the same design as [Steinbach City Council Reporting](https://steinbachcitycouncilreporting.ca/).

```
index.html              Home page listing all reports
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
