# DEOOS

**Durable execution on object storage.**

Write ordinary functions. Completed steps are remembered; unfinished steps retry after failure. Keep workflow state in your own bucket — S3, Azure Blob, GCS, R2, or self-hosted RustFS — with no database to run.

For humans and agents that want:

- A small Rust core with Python and TypeScript SDKs
- Durable steps, retries, leases, and idempotency keys
- Timers, signals, cancellation, and schedules
- A CLI and a small web UI
- Library mode inside your app, or one small server your workers talk to
