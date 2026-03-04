# GitOps on GKE with Flux

## Summary
Implemented Flux-based GitOps for Kubernetes deployments on GKE to improve consistency, auditability, and rollback speed.

## What I built
- Multi-environment GitOps structure (dev / stage / prod)
- HelmRelease + Kustomize overlays
- RBAC + namespace boundaries
- Image automation (optional) and safe promotion workflow

## Architecture (high level)
- Git repository as the source of truth
- Flux reconciles clusters from Git
- Helm charts standardized across services
- Promotion via PRs and tag/version pinning

## Results / Impact
- Reduced manual changes and configuration drift
- Faster and safer rollbacks
- Improved change traceability through PR history

## Tech
GCP, GKE, Flux, Helm, Kustomize, IAM/RBAC

## Links
- Code: https://github.com/<your-username>/<repo-name>