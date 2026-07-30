# Hi, I'm Matthew Flood

Software engineer working across **data engineering**, **backend services**, and **iOS**.

## Data engineering

| Project | What it is |
|---|---|
| [wikimedia_pageview_processor](https://github.com/mflood/wikimedia_pageview_processor) | Pipeline that downloads hourly Wikimedia pageview dumps and reports the top 25 pages per subdomain. Cached and restartable, 94% test coverage |
| [frivenmeld](https://github.com/mflood/frivenmeld) | Multi-threaded ETL merging a REST API dataset with a MySQL dataset, using bounded queues to throttle memory. Designed against a one-hour runtime budget; runs in 50 seconds |
| [apartment_data_merger](https://github.com/mflood/apartment_data_merger) | ETL merging apartment listings from disparate Snowflake and SQL Server exports into a Postgres data model, using heuristic matching |

## Backend and services

| Project | What it is |
|---|---|
| [rudecgi](https://github.com/mflood/rudecgi) | C++ library that parses form data, cookies, `PATH_INFO` and multipart uploads into one collection you query by field name. First released in 2000; modernized in 2026 with a CMake build, C++17, contract tests and CI — [docs](http://mflood.github.io/rudecgi/) |
| [mail_forward_flask_app](https://github.com/mflood/mail_forward_flask_app) | Flask email-forwarding service with a pluggable provider layer (Mailgun/Mandrill), mocked provider tests, and Docker deployment |
| [s3_music_player](https://github.com/mflood/s3_music_player) | Finds the music buried in your S3 buckets and plays it. Paginated scanner, CLI that emits M3U or JSON, and a Qt player whose playback logic sits behind an audio-backend protocol so it can be tested without a sound card |

## Algorithms

| Project | What it is |
|---|---|
| [mahjong](https://github.com/mflood/mahjong) | Hand solver for Chinese/Hong Kong mahjong — is this a winning hand, and what would complete it. Decomposes on tile counts rather than tile lists; a curses table keeps the analysis live as you draw. No dependencies |
| [pizza_flow](https://github.com/mflood/pizza_flow) | Works out who should eat which pizza by reducing the question to maximum flow. Edmonds–Karp with residual edges, which is what lets it undo an earlier choice in order to feed someone who eats only one thing |
| [whimsical](https://github.com/mflood/whimsical) | Small programs that were fun to write: a sudoku solver, an O(N) anagram checker, Codenames tooling, Advent of Code, and friends. A playground, not a portfolio piece |

Every project above except `whimsical` runs its tests in CI on each push.

## Currently building

- AI-powered personal agents for email triage, calendar management, and task tracking (Python, Claude API)
- An iOS language-learning app with a Whisper-based audio content pipeline (Swift, Python)

These are private while under active development — happy to walk through them in conversation.
