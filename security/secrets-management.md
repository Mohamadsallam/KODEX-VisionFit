# KODEX-VisionFit Secrets and Key Management Standard

1. **Storage:** No production secrets will be stored in source code or repositories.
2. **Environment Separation:** Use distinct credentials and keys for development, staging, and production environments.
3. **Rotation & Expiry:** Define regular key rotation and emergency revocation procedures.
4. **Scans:** Enforce automated secret scanning via Gitleaks in local development and CI pipelines.
