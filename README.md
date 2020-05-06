# tsurugi-slack-action

This GitHub action generates check-run annotations from outputs of static analysis tools.

## Usage

```yaml
    steps:
      - id: Generate_Annotations 
        name: Generate_Annotations 
        uses: ./.github/actions/tsurugi-annotations-action
        with:
          access-token: ${{ secrets.GITHUB_TOKEN }}
```
