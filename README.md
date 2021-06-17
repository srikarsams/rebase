# Rebase Action

This action rabases the branches only if the checkbox is checked in the PR description. v1.1

## Inputs

### `GITHUB_ACTION`

**Required**

### `TRIAL_RUN`

flag for trial run. No merge will happen, just logs the result.

### `COMMIT_MESSAGE`

Message to be used while merging!

## Example usage

```
uses: srikarsams/rebase@v1.0
  with:
  GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  COMMIT_MESSAGE: "Rebase done successfully!"
```
