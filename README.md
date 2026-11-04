# Георгий Андреев

Product Engineer: довожу продукт от идеи до работающей версии вместе с AI-агентами.
Пишу на Python (FastAPI) и TypeScript (React, Next.js), проектирую API, тестирую
на Playwright. Пришёл в разработку из промышленной автоматики: ПЛК, стенды испытаний,
электрические схемы. Оттуда привычка проверять систему на отказ: что будет, если ответ
площадки потерялся, а запрос повторили ([разбор на примере](https://github.com/Georgy213123/ai-product-engineering/blob/main/ai-workflow/examples/task-walkthrough.md)).

С июня 2026 года работаю fullstack / AI-инженером в коммерческих проектах:
панель продавца маркетплейсов, интернет-магазин, платформа для производства.
Claude Code и Codex — основные инструменты в этой работе.

Тверь · магистратура ТвГТУ «Информатика и вычислительная техника», 2026–2028

## Как я работаю

Задача → требования и процессы (BPMN, use case, user stories) → контракт API →
план, который проверяет вторая модель → код и тесты силами агентов → ревью → приёмка
в браузере через Playwright MCP → релиз.
Подробно — в [ai-workflow](https://github.com/Georgy213123/ai-product-engineering/tree/main/ai-workflow).

## Проекты

Три кейса, у каждого полный путь от постановки задачи до релиза, рабочий код, тесты и CI:

| Проект | О чём | Стек |
|---|---|---|
| [**SellerDesk**](https://github.com/Georgy213123/sellerdesk) | рабочее место оператора продавца на маркетплейсах: чаты, отзывы, AI-черновики, автономный агент-маркетолог | FastAPI · PostgreSQL · React · Playwright |
| [**ShopProbe**](https://github.com/Georgy213123/shopprobe) | автоматическая приёмка интернет-витрины с перепроверкой находок | Playwright · axe-core · FastAPI · React |
| [**OrderFlow**](https://github.com/Georgy213123/orderflow) | мастерская на заказ: заявка → конструкция → смета, упор на системный анализ | FastAPI · PostgreSQL · React |

Общая навигация, процесс работы с агентами и где AI ошибался —
в [**ai-product-engineering**](https://github.com/Georgy213123/ai-product-engineering).

Коммерческий код лежит у заказчиков в закрытых репозиториях под NDA, поэтому кейсы
написаны заново на вымышленных данных за два дня, 3–4 ноября 2026. О рабочих задачах
и решениях расскажу на созвоне.

## Стек

Python · FastAPI · SQLAlchemy · PostgreSQL · TypeScript · React · Next.js · Playwright ·
pytest · Vitest · Docker · GitHub Actions · Claude Code · Codex · MCP · REST / OpenAPI ·
BPMN · Linux · nginx

## Связь

Telegram [@GeorgyRoss](https://t.me/GeorgyRoss)
