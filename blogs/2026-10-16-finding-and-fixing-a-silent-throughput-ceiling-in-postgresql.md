---
title: "Finding (and Fixing) a Silent Throughput Ceiling in PostgreSQL"
url: "https://enterprisedb.com/blog/finding-and-fixing-silent-throughput-ceiling-postgresql"
date: "2026-10-16"
feed_url: "https://www.enterprisedb.com/blog/rss.xml"
---
“A benchmarking case study on relation extension locks, partitioning, and peak write load”; I gave this talk at PG Pune 2026, a community Postgres event with about 170 attendees, mostly database engineers, DBAs and Postgres enthusiasts. This post is the written version, plus two questions from the audience. Under heavy write load, I ran into a throughput saturation in Postgres.
