# KODEX-VisionFit Security Requirements

1. Every customer and brand request is associated with a server-derived tenant context.
2. Every access to restricted body data is authenticated, authorized, and auditable.
3. Raw images are not written to application logs.
4. Every expensive VTO request is rate-limited and quota-controlled.
5. The assistant cannot call tools outside its explicit allowlist.
6. Every model and dataset promoted to production has a version, source, checksum/provenance record, and approval.
