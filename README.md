## Guide

1. Update client info in `apps/keycloak-populator/values.yaml`.
3. Ensure both this repository and RFed's Keycloak chart source repository are copied to the airgapped Git repository.
4. Copy the `umbrella/umbrella-app.yaml` into the K3S/RKE2 directory to automatically load the umbrella app after Argo deployment.
