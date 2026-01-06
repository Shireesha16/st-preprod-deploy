# Shireesha Test – Pre-Production (ST)

This repository is used to deploy the **Pre-Production Static Web App (ST)** on **Azure Static Web Apps**.

## Environment
- **Platform:** Azure Static Web Apps (ST)
- **Branch:** pre-prod
- **Purpose:** Pre-production testing before Cloudflare environments

## Deployment
- Deployments are triggered automatically on every push to the `pre-prod` branch.
- GitHub Actions workflow: `azure-preprod-st-deploy.yml`

## Access
- Azure Static Web App URL:
  https://lively-bush-01ac65b0f.4.azurestaticapps.net

## Notes
- Staging, QA, and Production environments remain on Cloudflare.
- This environment is used only for validation and testing.