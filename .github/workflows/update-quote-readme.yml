name: Update Quote Readme

on:
  workflow_dispatch:
  schedule:
    # Runs at 2 UTC everyday
    - cron: "0 2 * * *"

jobs:
  update-readme:
    name: Update Quote README
    runs-on: ubuntu-latest
    steps:
      - uses: siddharth2016/quote-readme@main
        with:
          COMMIT_MESSAGE: <your-commit-message>       # default - Update with quote-readme
          OPTION: both            # default - both, can be one of (quote, funfact, both), if 'both' then will display either a quote or a fact
