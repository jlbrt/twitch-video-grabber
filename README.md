# Twitch Video Collector

## Getting Started

1. get YouTube API Key from `https://console.developers.google.com/apis/credentials`
2. copy `.env.sample` -> `.env` and fill out values
3. run `bun install`
4. run `docker-compose up -d`
5. run `docker-compose exec app bun run db:migrate:dev`
