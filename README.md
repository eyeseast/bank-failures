# Bank failures

Track updates to FDIC's list of bank failures here: https://www.fdic.gov/resources/resolutions/bank-failures/failed-bank-list/

See `.github/workflows/update.yml`:

- `env.ENDPOINT`: https://www.fdic.gov/resources/resolutions/bank-failures/failed-bank-list/banklist.csv
- `env.TARGET`: `failures.csv`

Hopefully this doesn't change very often.
