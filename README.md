# tail

This repository contains a GitHub Actions workflow for setting up secure RDP access via Tailscale.

## Usage

1. Go to the Actions tab
2. Select the "RDP" workflow
3. Click "Run workflow"
4. Wait for the workflow to complete
5. Check the logs for RDP connection details

## Security

- RDP access is only available through Tailscale network
- Temporary user account with secure random password
- Workflow automatically terminates after 60 hours

## Requirements

- Tailscale auth key must be set as repository secret `TAILSCALE_AUTH_KEY`
