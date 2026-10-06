# DEOOS

**Durable execution on object storage.**

Write ordinary functions. Completed steps are remembered; unfinished steps retry after failure. Keep workflow state in your own bucket — S3, Azure Blob, GCS, or R2 — with no database to run.

## The problem

Most durable-execution tools assume a cluster and a database. Plenty of teams just need steps that survive crashes and a bucket they already have.

## Our solution

We built the simple version.

- A small Rust core with Python and TypeScript SDKs
- Durable steps, retries, leases, and idempotency keys
- Timers, signals, cancellation, and schedules
- A CLI and a small web UI
- Library mode inside your app, or one small server your workers talk to

## Links

- [deoos.dev](https://deoos.dev) — product + early access
- [Derek Hecksher](https://hckshr.com) — maker
