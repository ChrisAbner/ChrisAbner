# Hi, I'm Chris Abner 👋

**Senior Full-Stack Developer** in Cancún, México. I build web products with **PHP/Laravel, Vue 3, Inertia.js and AWS**, and I contribute fixes to the PHP and Laravel open-source ecosystem.

---

## 🔥 Cordon Modulith

**Verifiable boundaries between the modules of a Laravel application, checked in CI.**

Folders don't stop the `Billing` module from reaching into `Catalog`'s models. Cordon Modulith parses your code statically (it never loads or runs it), builds the dependency graph between modules and fails the build when a module:

- uses **internal classes** of another module instead of its public API,
- depends on a module it **did not declare**, or
- takes part in a **dependency cycle**.

It works with nwidart/laravel-modules, InterNACHI/modular or a plain `app/Modules` folder, supports a baseline for existing projects, and also runs as a Pest expectation, a PHPStan rule and a GitHub Action. `php artisan cordon:docs` generates Mermaid diagrams of the real architecture.

```bash
composer require --dev chrisabner/cordon-modulith
php artisan cordon:verify
```

[![Tests](https://github.com/ChrisAbner/Cordon-Modulith/actions/workflows/tests.yml/badge.svg)](https://github.com/ChrisAbner/Cordon-Modulith/actions/workflows/tests.yml)
[![Latest version](https://img.shields.io/packagist/v/chrisabner/cordon-modulith.svg)](https://packagist.org/packages/chrisabner/cordon-modulith)

📖 [Documentation](https://chrisabner.github.io/Cordon-Modulith/) · 📦 [Packagist](https://packagist.org/packages/chrisabner/cordon-modulith) · 💻 [Repository](https://github.com/ChrisAbner/Cordon-Modulith) · Status: 0.2 (alpha)

## 🤝 Open source

Merged pull requests:

- **[doctrine/DoctrineBundle#2324](https://github.com/doctrine/DoctrineBundle/pull/2324)**: `find()` no longer refreshes managed entities on ORM < 3.7, which ran an extra query and discarded their unflushed changes.
- **[pestphp/pest-plugin-browser#295](https://github.com/pestphp/pest-plugin-browser/pull/295)**: scoped container bindings no longer leak between requests in browser tests (it broke Inertia SSR).
- **[pestphp/pest#2002](https://github.com/pestphp/pest/pull/2002)**: PHPUnit extensions can register event subscribers again in `--parallel` mode (based on a fix proposed in #1685).
- **[php-debugbar/php-debugbar#1074](https://github.com/php-debugbar/php-debugbar/pull/1074)**: no more "Refused to get unsafe header" console errors on cross-origin XHR.

## 🛠️ Also building

- **[PromoInvestor](https://promoinvestor.com)**: fintech rates comparator for Mexico (Laravel, Laravel Cloud).

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

![Chris's GitHub stats](./profile/stats.svg)
![Top languages](./profile/top-langs.svg)

## 📫 Find me

🌐 [chrisabner.github.io](https://chrisabner.github.io) · 💼 [LinkedIn](https://www.linkedin.com/in/chrisabnerr)
