# Kong Konnect CI/CD with GitHub Actions

This repo demonstrates how to:
- Validate Kong configs with decK
- Ping Konnect Control Plane
- Sync configs to Konnect
- Test Data Plane routes

## Setup
1. Generate a Personal Access Token (PAT) in Konnect.
2. Store it in GitHub Secrets as `KONNECT_PAT`.
3. Adjust `--konnect-control-plane-name` and `--konnect-addr` in the workflow.
4. Push to `main` branch to trigger the workflow.
