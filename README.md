# Reusable GitHub Actions

This is repository for reusable GitHub Actions.

Insert the below code into the file <repository>/.github/workflows/master-push-actions.yml
  

```yaml
name: Tag and Release
on:
  push:
    branches:
      - master
jobs:
  tag-and-release:
    uses: apple-industries/github-workflows/.github/workflows/tag-and-release.yml@v1.0.0
```
