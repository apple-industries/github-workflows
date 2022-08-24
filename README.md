# Reusable GitHub Actions

This is repository for reusable GitHub Actions.

copy the below code into repository/.github/workflows/

...
name: Tag and Release
on:
  push:
    branches:
      - master
jobs:
  tag-and-release:
    uses: apple-industries/github-workflows/.github/workflows/tag-and-release.yml@v1.0.0
...
