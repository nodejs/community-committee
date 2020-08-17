name: Check Markdown links

on:
  schedule:
    # * is a special character in YAML so you have to quote this string
    - cron:  '0 * * * *'

jobs:
  markdown-link-check:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@master
    - uses: gaurav-nelson/github-action-markdown-link-check@v1
