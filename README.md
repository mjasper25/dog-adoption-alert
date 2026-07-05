# Dog Adoption Alert

This project monitors rescue sites every 2 hours using GitHub Actions.

## Sites
- lifelinepuppy.org
- rezdawgrescue.org
- foothillsanimalshelter.org
- 4p4l.org
- coloradopuppy.org
- 2babrescue.org
- lolasrescue.com
- rmpuppyrescue.org

## Configure
1. Create GitHub repo and upload files.
2. Create Gmail App Password.
3. Add GitHub Secrets:
   - EMAIL_USER = your Gmail
   - EMAIL_PASS = Gmail App Password
   - ALERT_TO = mjasper5280@gmail.com
4. Enable GitHub Actions.

The sample code is a framework; each rescue may require site-specific parsing.
