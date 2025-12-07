# Get PR Labels

Retrieves labels from pull requests associated with a commit SHA or merge group PR number.

## Usage

```
    - name: Get PR labels
    uses: htrungngx/gh-actions/get-pr-label@main
    id: get-labels
    with:
        GH_TOKEN: ${{ github.token }}
```
