# Торговый бот Limitless

**🌐 Language / 语言 / Язык:** [English](README.md) · [简体中文](README.zh-CN.md) · [Русский](README.ru.md)

![Status](https://img.shields.io/badge/status-🟢_live-2ea44f?style=flat-square)
[![Engine](https://img.shields.io/badge/engine-shared_core-6e40c9?style=flat-square)](https://github.com/HarrierOnChain/Prediction-Markets-Trading-Bot-Toolkits)
[![Rust](https://img.shields.io/badge/rust-1.70+-orange.svg?style=flat-square&logo=rust)](https://www.rust-lang.org/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](LICENSE)

> Автоматический **торговый бот Limitless** — Ончейн-стакан заявок. Часть набора [Prediction Market Toolkits](https://github.com/HarrierOnChain/Prediction-Markets-Trading-Bot-Toolkits): одно ядро исполнения, один слой риска, все площадки.

**Limitless** уже **работает в продакшене** сегодня.

---

## Limitless в реальной торговле

<div align="center">

<img width="820" alt="Limitless trading bot TUI" src="https://github.com/user-attachments/assets/b6c51ba1-14c6-4582-858c-e9441516dd1d" />
<img width="820" alt="Limitless trading bot TUI" src="https://github.com/user-attachments/assets/66d9cb72-e14a-414f-93e5-600fb1d3f49f" />

<sub>Общий TUI в работе на Limitless — позиции в реальном времени, P&L и состояние предохранителя. <!-- TODO: swap in Limitless-specific captures --></sub>

</div>

---

## Стратегии на Limitless

Эти боты работают на Limitless через один адаптер площадки на общем движке — те же риск-контроли, тот же TUI, полная поддержка dry-run.

| Стратегия |
|----------|
| 🎯 **Снайпер разрешения** — околоуверенность 95¢ → гарантированная выплата $1.00 |
| 📊 **Дисбаланс стакана** — сигнал *и есть* стакан заявок, без внешних фидов |
| 📈 **Сбор спреда** — тысяча выигрышей по 0,5¢ складываются в одно число |

> Нужна стратегия, не указанная здесь для Limitless? Покрытие адаптеров определяется спросом — [напишите](https://t.me/HarrierOnChain).

---

## Один движок, все площадки

Этот репозиторий — точка входа для **Limitless**. Ядро исполнения, слой риска и все 20+ адаптеров площадок находятся в основном наборе:

### 👉 **[Prediction-Markets-Trading-Bot-Toolkits](https://github.com/HarrierOnChain/Prediction-Markets-Trading-Bot-Toolkits)** — полный набор

| | |
|---|---|
| **Исполнение ордеров** | < 100 мс от начала до конца |
| **Обработка событий** | < 1 мс на событие |
| **Безопасность** | Предохранитель · защита глубины · dry-run · минимум сделки |
| **Площадки** | Polymarket · Kalshi · Limitless активны — 20+ в планах |

Добавить площадку — значит написать **один адаптер**, а не пересобирать бота.

---

## Получить доступ

| Платформа | Ссылка |
|----------|------|
| **Полный набор** | [Prediction-Markets-Trading-Bot-Toolkits](https://github.com/HarrierOnChain/Prediction-Markets-Trading-Bot-Toolkits) |
| **Telegram** | [@HarrierOnChain](https://t.me/HarrierOnChain) |
| **Обсуждения** | [GitHub Discussions](https://github.com/HarrierOnChain/Prediction-Markets-Trading-Bot-Toolkits/discussions) |

*Обычно отвечаем в течение нескольких часов.*

---

## Связанные площадки

[Kalshi](https://github.com/HarrierOnChain/Kalshi) · [Polymarket](https://github.com/HarrierOnChain/Polymarket) · [Augur](https://github.com/HarrierOnChain/Augur) · [Interactive Brokers ForecastTrader](https://github.com/HarrierOnChain/Interactive-Brokers-ForecastTrader)

> Полный каталог площадок — в [основном наборе →](https://github.com/HarrierOnChain/Prediction-Markets-Trading-Bot-Toolkits#venue-coverage)

---

## Отказ от ответственности

> Торговля на рынках предсказаний сопряжена с реальным финансовым риском. ПО предоставляется «как есть», без гарантий, и не является финансовой консультацией. Всегда тестируйте с `enable_trading: false` перед вводом реального капитала. Соблюдайте условия использования Limitless и местное законодательство.

---

<div align="center">

**Торговый бот Limitless · построен на движке [Prediction Market Toolkits](https://github.com/HarrierOnChain/Prediction-Markets-Trading-Bot-Toolkits)**

[![Telegram](https://img.shields.io/badge/Telegram-@HarrierOnChain-26A5E4?style=flat-square&logo=telegram)](https://t.me/HarrierOnChain)

</div>
