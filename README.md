# Nicholas Moriarty

Building practical backend tools in Python. My focus is HTTP, SQL, testing,
and reliable data storage.

| Project | What it does | Engineering focus |
| --- | --- | --- |
| [Datatrail](https://github.com/nickmori05/datatrail) | Compare CSV snapshots and trace records to their source | Typed column checks, per-record provenance history, streamed CSV diffs, API and CLI |
| [Ticket Backend](https://github.com/nickmori05/ticket-backend) | Track support tickets through HTTP or the terminal | Scoped, expiring API tokens, idempotent submissions, transactional outbox with SMTP delivery |
| [Uptime Monitor](https://github.com/nickmori05/uptime-monitor) | Check saved HTTP endpoints and alert on incidents | Bounded concurrency, crash-tested webhook alerts, fault-injection reliability tests, JSON API and dashboard |
| [ApplyTrack](https://github.com/nickmori05/applytrack) | Track job applications and follow-up dates | Dated status history, response-rate stats, SQLite migrations, CSV import and export |

Each project includes a quick start, automated tests, and notes on its design
and current limits. Feature work goes through branches and pull requests with
GitHub Actions tests, linting, and Docker checks.

Currently learning: per-user authorization, worker leases and crash recovery,
and at-least-once delivery. The goal is to understand how a backend behaves
when data, networks, or dependencies fail.
