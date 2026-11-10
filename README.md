# 🏠 EverShelfMAX

> Independent fork of EverShelf, maintained separately from the original upstream project.

This repository is a custom fork of the original EverShelf project and is intentionally disconnected from the upstream maintenance track at `dadaloop82/EverShelf`.

It may include different defaults, custom functionality, deployment choices, and local changes that are not present in the upstream repository. Use it as a separate self-hosted fork, not as an official upstream release or mirror.

<div align="center">

**[Original project](https://github.com/dadaloop82/EverShelf)** · **[License](LICENSE)** · **[Documentation](docs/)**

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE) [![PHP 8+](https://img.shields.io/badge/PHP-8.0+-blue.svg)](https://www.php.net/)

</div>

## Why this fork exists

EverShelfMAX is a separate fork built for a specific self-hosted setup. It diverges from the upstream repository by design:

- independent maintenance and issue tracking
- custom local modifications and deployment assumptions
- no guarantee of compatibility with upstream defaults
- intentionally not tied to upstream release flow or support channels

If you are looking for the upstream project, use the original repository linked above.

## Features

- inventory tracking with barcode scanning and expiry management
- AI-assisted identification, OCR, chat, and recipe generation
- smart shopping list and anti-waste planning
- cooking workflow with timers, voice output, and directions
- PWA-style mobile/web experience for local self-hosting
- optional integrations for health, kiosk, and automation workflows

## Quick start

```bash
git clone https://github.com/PhosphorosAletheia/EverShelfMAX.git
cd EverShelfMAX
cp .env.example .env
docker compose up -d
```

Then open:

- http://localhost:8080

## Important note

This fork is not the official EverShelf repository and is not affiliated with the upstream project maintainers.

The upstream project continues at:

- https://github.com/dadaloop82/EverShelf

Any feature, build, or configuration here may differ from upstream, and compatibility with that project is not guaranteed.

## Project structure

Typical repository layout:

- `api/` — server-side logic and APIs
- `assets/` — frontend assets
- `data/` — local data and SQLite storage
- `docs/` — architecture and supporting documentation
- `evershelf-kiosk/` and `evershelf-health-bridge/` — companion integrations

## License

MIT License — see [LICENSE](LICENSE).

This repository retains attribution to the upstream EverShelf project while remaining a separate and independently maintained fork.
