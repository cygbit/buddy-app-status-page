# Buddy App Status Page

Uptime monitor and status page for Buddy App backend services, powered by [Upptime](https://upptime.js.org).

## Monitored Services

| Service | URL |
|---|---|
| Production API | https://api-prod-v2.divewithbuddy.com/health |
| Staging API | https://api-staging.divewithbuddy.com/health |
| Dev API | https://api-dev.divewithbuddy.com/health |

## How it works

- GitHub Actions checks each endpoint every 5 minutes
- Results are committed to this repo
- GitHub Pages hosts the status page at https://status.divewithbuddy.com
