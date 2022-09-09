<!-- markdownlint-disable -->
## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| environment | Environment name | N/A | true |
| github-token | The GitHub token used to create an authenticated client | ${{ github.token }} | true |
| ref | Branch or commit SHA | N/A | true |
| status | Deployment status | N/A | false |

## Outputs

| Name | Description |
|------|-------------|
| id | Deployment ID |
<!-- markdownlint-restore -->
