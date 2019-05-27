# Docker Demo Application
This is a Go demo application used for demonstrating Docker and load balancing.

This application is created by Evan Hazlett (ehazlett/docker-demo).

## Environment Variables

- `TITLE`: sets title in demo app
- `SHOW_VERSION`: show version of app in ui (`VERSION` env var)
- `REFRESH_INTERVAL`: interval in milliseconds for page to refresh (default: 1000)
- `SKIP_ERRORS`: set this to prevent errors from counting (useful on janky load balancers)
- `METADATA`: extra text at bottom of info area

## Build

`make`

## Run

`docker run -P --rm docker-demo`
