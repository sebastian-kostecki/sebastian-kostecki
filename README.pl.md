<div align="center">

# Sebastian Kostecki

**Backend developer (PHP · Laravel) z Lublina — backendy w PHP i Laravelu, które działają na produkcji.**

[![kostecki.dev](https://img.shields.io/badge/kostecki.dev-0A0A0A?style=for-the-badge&logo=googlechrome&logoColor=white)](https://kostecki.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kostecki-sebastian)
[![E-mail](https://img.shields.io/badge/kontakt@kostecki.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kontakt@kostecki.dev)

[English](README.md) · **Polski**

</div>

Pracuję nad **[PanelAlpha](https://panelalpha.com)** w ModulesGarden — platformą B2B, która automatyzuje zarządzanie WordPressem dla firm hostingowych i agencji: API w Laravelu, integracje z panelami hostingowymi (cPanel, Plesk, DirectAdmin), DNS, SSL, poczta, kopie zapasowe i rozliczenia w WHMCS.

Współtworzę też **[PanelAlpha Engine](https://github.com/panelalpha/panelalpha-engine)** — otwartoźródłową platformę do self-hostingu, którą agenci AI obsługują przez MCP.

### Stos

[![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)
[![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)](https://laravel.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)](https://vuejs.org/)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Inertia](https://img.shields.io/badge/Inertia-9553E9?style=for-the-badge&logo=inertia&logoColor=white)](https://inertiajs.com/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Pest](https://img.shields.io/badge/Pest-F28D1A?style=for-the-badge)](https://pestphp.com/)
[![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)](https://playwright.dev/)

### Projekty po godzinach

| Projekt | Co to jest | Stos |
| --- | --- | --- |
| **[Domowy Skarbnik](https://github.com/sebastian-kostecki/household-treasurer)** · [aplikacja](https://budget.kostecki.dev) | Roczny budżet domowy: plan kontra wykonanie, płynność, import wyciągów, serwer MCP dla Claude. | Laravel 13, Vue 3, Inertia, PostgreSQL |
| **[Root Keeper](https://github.com/sebastian-kostecki/root-keeper)** · [aplikacja](https://genealogy.kostecki.dev) | Drzewo genealogiczne, w którym każdy fakt ma źródło. | Laravel 13, React 19, TypeScript, Playwright |
| **[Menu Maker](https://github.com/sebastian-kostecki/menu-maker)** · [aplikacja](https://menu.kostecki.dev) | Tygodniowy jadłospis z pomocą AI i listą zakupów w PDF. | Laravel 13, Vue 3, Inertia, Playwright |
| **[FocusBlocker](https://github.com/sebastian-kostecki/focus-blocker)** | Blokada stron dla Windows, której nie da się wyłączyć, gdy już trwa: plik hosts, Harmonogram zadań, rozszerzenie przeglądarki. | PowerShell |
| **[Nawigator dnia](https://github.com/sebastian-kostecki/day-navigator)** | Aplikacja w zasobniku Windows na dzień pracy programisty: zadania z GitLaba i GitHuba, lista „Do zrobienia” i licznik czasu pracy. | Tauri 2, Rust, React |
| **[kostecki.dev](https://github.com/sebastian-kostecki/kostecki-dev-landing)** · [strona](https://kostecki.dev) | Osobista strona prerenderowana do statycznego HTML. | Vue 3, TypeScript, Vite |

### Jak pracuję z AI

Najpierw specyfikacja, słownik domeny i ADR-y. Agenci (Claude Code, Cursor) piszą dużą część kodu; o tym, co trafia na produkcję, decydują testy, analiza statyczna i review. Każda zmiana zostawia w repozytorium folder z dokumentacją — zajrzyj do folderów `context/` w projektach powyżej. Ten sposób pracy szlifuję na kursie 10xDevs.
