<!-- markdownlint-disable -->
## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| env-name | environment name to get ID for | N/A | true |
| github-token | The GitHub token used to create an authenticated client | ${{ github.token }} | true |
| ref-to-search | ref of the branch/commit to search by | N/A | true |
| status | status to get ID for | N/A | false |

## Outputs

| Name | Description |
|------|-------------|
| deploymentId | deployment id retrieved based on ref and environment |
<!-- markdownlint-restore -->
