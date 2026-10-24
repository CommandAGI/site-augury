# site-augury

The site of Augury, the forecasting company of CommandAGI (`org-augury`). A static folder served by CommandAGI's site
hosting; mounted in the CommandAGI repository at `seed/drive/platform/org-augury/sites/augury`.

- `index.html` + `style.css`: one page, light and dark, from the copy brief
  (`seed/drive/platform/user-commandagi/companies/augury/sites/BRIEF.md` in the CommandAGI repository). It runs no
  script and makes no request after it loads (its content security policy).
- The track record says "No forecast has resolved yet." until one has; then it lists every resolved forecast, right
  or wrong. No accuracy number before there are resolved forecasts; prices are the owner's.
