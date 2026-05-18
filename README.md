# Лабораторная работа №4 - Автопарк

## Description

Документация и управление проектом "Автопарк" - консольное приложение для управления автопарком, водителями и заказами на перевозку грузов. Проект включает UML-спецификацию, базу данных, CI/CD и документацию.

## Project Structure

| Раздел | Описание |
|--------|----------|
| [Wiki](https://github.com/fpmi-tpmp2026/tpmp-gr10b-lab4-svibovich/wiki) | Полная документация проекта |
| [Задание 1](https://github.com/fpmi-tpmp2026/tpmp-gr10b-lab4-svibovich/wiki/Свибович_Никита_задание1) | UML-спецификация |
| [Задание 2](https://github.com/fpmi-tpmp2026/tpmp-gr10b-lab4-svibovich/wiki/Задание-2.-Kanban) | Управление проектом в стиле Kanban |
| [Задание 3](https://github.com/fpmi-tpmp2026/tpmp-gr10b-lab4-svibovich/wiki/Задание-3.-Проектирование-приложения) | Проектирование приложения |
| [Задание 4](https://github.com/fpmi-tpmp2026/tpmp-gr10b-lab4-svibovich/wiki/Задание-4.-База-данных) | Проектирование базы данных |
| [Задание 5](https://github.com/fpmi-tpmp2026/tpmp-gr10b-lab4-svibovich/wiki/Задание-5.-CI-и-CD) | Непрерывная сборка и тестирование |
| [Задание 6](https://github.com/fpmi-tpmp2026/tpmp-gr10b-lab4-svibovich/wiki/Задание-6.-Документирование-и-разработка) | Разработка приложения |
| [Глоссарий](https://github.com/fpmi-tpmp2026/tpmp-gr10b-lab4-svibovich/wiki/Глоссарий) | Термины предметной области |

## Installation

### Клонирование репозитория

```bash
git clone https://github.com/fpmi-tpmp2026/tpmp-gr10b-lab4-svibovich.git
cd tpmp-gr10b-lab4-svibovich
```

## Usage

Документация доступна в [Wiki](https://github.com/fpmi-tpmp2026/tpmp-gr10b-lab4-svibovich/wiki).

Для работы с приложением клонируйте репозиторий с кодом:

```bash
git clone https://github.com/svibnik/tpmp-lab4-autopark.git
cd tpmp-lab4-autopark
make all
sqlite3 autopark.db < database/schema.sql
./bin/autopark
```

## Contributing

**Автор:** Свибович Никита  
**Группа:** 10  
**Вариант:** 1 «Автопарк»

**Реализованные задачи:**
- Разработка UML-спецификации (диаграммы)
- Проектирование базы данных в Vertabelo
- Разработка консольного приложения на C
- Настройка CI/CD с GitHub Actions
- Unit-тестирование (CUnit, 40+ тестов)
- Оформление документации в Wiki

## Links

- [Wiki проекта](https://github.com/fpmi-tpmp2026/tpmp-gr10b-lab4-svibovich/wiki)
- [Репозиторий с кодом](https://github.com/svibnik/tpmp-lab4-autopark)
- [GitHub Pages](https://svibnik.github.io/tpmp-lab4-autopark)
- [GitHub Actions](https://github.com/svibnik/tpmp-lab4-autopark/actions)
