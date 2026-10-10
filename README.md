# Nicholas Moriarty

Building practical backend tools in Python. My focus is HTTP, SQL, testing,
and reliable data storage.

| Project | What it does | Engineering focus |
| --- | --- | --- |
| [Datatrail](https://github.com/nickmori05/datatrail) | Compare CSV snapshots and trace records to their source | Data quality checks, atomic imports, source provenance, API and CLI |
| [Ticket Backend](https://github.com/nickmori05/ticket-backend) | Track support tickets and comments through HTTP or the terminal | Request validation, idempotent submissions, transactional history |
| [JobQueue](https://github.com/nickmori05/jobqueue) | Queue background jobs in SQLite and run them with workers | Atomic claims, bounded retries, attempt history, schema migrations |
| [Uptime Monitor](https://github.com/nickmori05/uptime-monitor) | Check saved HTTP endpoints individually or in parallel | Bounded concurrency, timeouts, persistent failure history |
| [ApplyTrack](https://github.com/nickmori05/applytrack) | Track applications and follow-up dates | SQL filtering, CSV exports, input validation |

Each project includes runnable examples, automated tests, and notes on its
design and current limits. Feature work is tracked through branches and pull
requests with GitHub Actions checks.

Currently learning: API access control, worker leases and crash recovery,
and at-least-once delivery. The goal is to understand how a backend behaves when data,
networks, or dependencies fail.
