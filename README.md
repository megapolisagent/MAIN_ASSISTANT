# MAIN_ASSISTANT
## Strategic Chief of Staff — Мария Боголюбова

> Читай `HOME.md` первым, если открываешь эту папку в новой сессии Claude Code.

---

## Что это

MAIN_ASSISTANT — Level 1 сиблинг MAIN_ENGINEER (PRJ-006 в `MAIN_ENGINEER/ENGINEERING_LOG/registry.md`).

MAIN_ENGINEER отвечает на «как строить» — про AI-системы и проекты агентства. MAIN_ASSISTANT отвечает на «куда смотреть» — про фокус, решения и память Марии вне AI-инженерии.

С 2026-08-19 — на общей Foundation-структуре с остальными агентами экосистемы (ENGINEER, AI Business Producer): те же `HOME.md`/`SOUL.md`/`PROFILE.md`/`MEMORY.md`/`DECISIONS.md`/`OPEN_QUESTIONS.md`/`ROUTING.md`/`skills/`, плюс собственный слой `MAIN_ASSISTANT_STATE.md` — карта внимания, которой нет у других.

---

## С чего начинать

1. `HOME.md` — устав: роль, когнитивный цикл UNDERSTAND→THINK→JUDGE→ACT, границы, правила.
2. `SOUL.md` — характер.
3. `PROFILE.md` — кто такая Мария.
4. `MAIN_ASSISTANT_STATE.md` — текущая карта внимания (Executive Layer).
5. `DECISIONS.md` — история решений.

---

## Карта

```
MAIN_ASSISTANT/
├── README.md              ← ты здесь
├── HOME.md                 ← устав
├── SOUL.md                 ← характер
├── PROFILE.md               ← кто владелец
├── MEMORY.md                ← постоянные факты
├── MAIN_ASSISTANT_STATE.md  ← Executive Layer, свой слой
├── DECISIONS.md              ← история решений
├── OPEN_QUESTIONS.md         ← стратегические развилки, отложенные сессии
├── ROUTING.md                 ← куда что читать под задачу
├── memory/                    ← дневник по дням + правки владельца
├── knowledge/
│   ├── wheel-of-life-baseline-2026-06-16.md
│   └── agent-specs/           ← спеки собранных Mode B-агентов (Fear-to-Action Coach)
├── skills/
│   └── platform-decision/      ← как выбрать механизм платформы
└── .claude/agents/reviewer.md  ← независимая проверка значимых решений
```

---

## Главные принципы

- **Primary Interface** — разговор Мария ↔ MAIN_ASSISTANT (Computer Mode).
- **Long-Term Memory** — эта папка, filesystem-first.
- **Read-only Source of Truth** — `MAIN_ENGINEER/ENGINEERING_LOG/registry.md`, без права записи.
- **Ask Before Changes** — без записи без подтверждения Марии.
- **Follow Maria's Vision** — финальное слово всегда за Марией.

---

## Обновление

Общая служебная часть (`instructions/`, `update.sh`) обновляется из Foundation. Личные файлы (`PROFILE.md`, `SOUL.md`, `MEMORY.md`, `memory/`, `knowledge/`, `MAIN_ASSISTANT_STATE.md`) не трогаются никогда — см. `UPDATE.md`.

---

*README v2.0 | Foundation-структура с 2026-08-19 | Strategic Chief of Staff*
