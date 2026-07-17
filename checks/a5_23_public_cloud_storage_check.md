> Install: `pip install prowler`

Run Prowler's public object-storage checks against each cloud provider in scope per [cloud_security_policy.md](../policies/cloud_security_policy.md) (e.g. `prowler <provider> --check s3_bucket_public_access` plus the provider's equivalent blob/bucket public-access checks); check passes if no publicly accessible storage is reported.
