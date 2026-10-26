# Hi, I'm Chris Abner 👋

**Senior Full-Stack Developer** from Cancún, México. I build multi-tenant B2B SaaS for the vacation club and travel industry with **Laravel 12, Vue 3, Inertia.js and AWS** — 30+ white-label brands, 98+ vacation clubs, 40,000+ hotels of inventory.

---

## 🔥 Featured project: Cordon Modulith

**Verifiable boundaries between the modules of a Laravel application, checked in CI.**

Modular monoliths usually rely on folders. Folders don't stop the `Billing` module from reaching into `Catalog`'s models — six months later the "modules" are just directories. Cordon Modulith reads your code statically, builds the dependency graph between modules, and fails the build when a module:

- uses **internal classes** of another module instead of its public API,
- depends on a module it **did not declare**, or
- takes part in a **dependency cycle**.

It also ships Laravel Boost resources that teach AI coding agents to go through a module's public API. Inspired by Spring Modulith and Shopify's Packwerk, adapted to Laravel conventions.

```bash
composer require --dev chrisabner/cordon-modulith
php artisan cordon:verify
```

[![Tests](https://github.com/ChrisAbner/Cordon-Modulith/actions/workflows/tests.yml/badge.svg)](https://github.com/ChrisAbner/Cordon-Modulith/actions/workflows/tests.yml)
[![Latest version](https://img.shields.io/packagist/v/chrisabner/cordon-modulith.svg)](https://packagist.org/packages/chrisabner/cordon-modulith)
[![Downloads](https://img.shields.io/packagist/dt/chrisabner/cordon-modulith.svg)](https://packagist.org/packages/chrisabner/cordon-modulith)

📖 [Documentation](https://chrisabner.github.io/Cordon-Modulith/) · 📦 [Packagist](https://packagist.org/packages/chrisabner/cordon-modulith) · 💻 [Repository](https://github.com/ChrisAbner/Cordon-Modulith)

> Status: 0.1 (alpha) — the public API may change before 1.0.

---

## 🛠️ What I'm building

- **[PromoInvestor](https://promoinvestor.com)** — fintech rates comparator for Mexico (Laravel, Laravel Cloud). My capstone project.
- **Riviera Apps & Web** — apps, websites and marketing for local businesses in Cancún.
- **Owners Link** — multi-tenant B2B SaaS platform for vacation clubs, with external API aggregation via DTOs, Redis caching and AWS infrastructure (EC2, S3, RDS, Lambda).

## 🧰 Stack

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white)
![Inertia.js](https://img.shields.io/badge/Inertia.js-9553E9?style=flat&logo=inertia&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

## 📊 GitHub stats

![Chris's GitHub stats](https://github-readme-stats.vercel.app/api?username=ChrisAbner&show_icons=true&theme=transparent&hide_border=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ChrisAbner&layout=compact&theme=transparent&hide_border=true)

## 📫 Find me

🌐 [chrisabner.github.io](https://chrisabner.github.io) · 💼 [LinkedIn](https://www.linkedin.com/in/chrisabnerr) · 💼 [PromoInvestor](https://promoinvestor.com)
