# Kōri — Anime Discovery Hub

A free, single-file static website for discovering anime, tracking what you watch, and finding legal places to stream it.

**Live:** https://intror47-create.github.io/kori-anime-hub/

## What it is

A curated, offline-capable catalog of 55 popular series and films. Everything — HTML, CSS, JavaScript, generated artwork, and data — lives in `index.html`. No build step, no backend, no API keys, no tracking, no account.

## Features

- Search by title, genre, or studio
- Genre filters and sort by score, popularity, or newest
- Detail view with synopsis, stats, genres, and legal streaming lookup links
- Personal watchlist with five statuses, persisted in `localStorage`
- **My Videos** — an in-browser player for video files you already own. Drop files in, get a playlist with full native controls; files are stored in IndexedDB on your device and never uploaded.
- Real locally-hosted cover art (54 images, ~5.5 MB), with generated art as fallback
- Fully responsive, keyboard accessible

## Hosting

Drop `index.html` into any static host (GitHub Pages, Netlify, Vercel, Cloudflare Pages, or a plain web server). It works from `file://` too.

## Notes

Kōri does not host, stream, or link to copyrighted video. Titles and artwork belong to their respective creators and studios. Streaming links point to JustWatch and MyAnimeList for region-accurate legal availability.
