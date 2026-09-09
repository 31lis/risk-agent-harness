# Security Policy

## Reporting a vulnerability

Please use GitHub's private vulnerability reporting feature for this repository when it is available. Do not include secrets, access tokens, private repository content, or working exploit details in a public issue.

If private reporting is unavailable, open a public issue containing only a high-level description and a request for a private contact channel.

## Secret handling

- Keep `.env`, API keys, GitHub tokens, webhook secrets, private keys, database files, and logs out of version control.
- Use least-privilege, repository-scoped GitHub credentials.
- Rotate a credential immediately if it is accidentally committed or exposed; deleting the file from the latest commit is not sufficient.
- Enable authentication before exposing the dashboard or API to a network.
