# FSM Dispensary Water Tanks dashboard

A free, public web dashboard. Anyone can open the link in a browser; no Power BI or sign-in needed.

## Files
- `index.html` – the dashboard (don't need to edit)
- `data/water_tanks.csv` – facilities with tanks (edit this to update)
- `data/other_sites.csv` – sites not counted (edit this to update)

## Update the data
Keep the column headers exactly as they are. Valid Condition values:
Good, Working, Fair, Partial, Needs maintenance, Inadequate, Not working, Not installed, Not stated.
State must be Chuuk, Kosrae, Pohnpei or Yap.

Option A – edit on GitHub: open the CSV file in your repository, click the pencil icon, change it, click "Commit changes".
Option B – edit in Excel: open the CSV, edit, File > Save As > "CSV UTF-8 (Comma delimited)", keep the same file name,
then in GitHub open the `data` folder > Add file > Upload files > drag the file in > Commit changes.

The site updates about 1 minute after you commit. Refresh the page to see it.
