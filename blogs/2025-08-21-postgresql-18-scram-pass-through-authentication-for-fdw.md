---
title: "PostgreSQL 18 - SCRAM pass-through authentication for fdw connections"
url: "https://enterprisedb.com/blog/postgresql-18-scram-pass-through-authentication-fdw-connections"
date: "2025-08-21"
feed_url: "https://www.enterprisedb.com/blog/rss.xml"
---
PostgreSQL 18 brings a nice improvement for folks using postgres_fdw or dblink_fdw: SCRAM pass-through authentication. You no longer need to store plain-text passwords in your USER MAPPING options when setting up a foreign server connection.
