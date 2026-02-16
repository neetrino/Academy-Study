# Неделя 2 — Путеводитель студента

**Курс:** AI-Coding в Cursor (VibeCoding → Production)  
**Тема:** Архитектура и качество — AI должен жить в клетке

---

## Что ты изучишь

1. **Архитектурные рамки** — папки, слои, запреты для AI
2. **ADR** — фиксация решений (env, auth)
3. **Security** — чек-лист, что проверять всегда
4. **Тестирование** — как просить тесты у AI
5. **Code Review** — AI как второй глаз, не как судья

---

## Порядок работы (5 дней)

| № | День | Тема | Документ | Действие |
|---|------|------|----------|----------|
| 1 | День 6 | Архитектура | [WEEK_2_PLAN.md](WEEK_2_PLAN.md) | Архитектурный контракт |
| 2 | | ДЗ 6 | [docs/ARCHITECTURE.md](../docs/ARCHITECTURE.md) | Создать ARCHITECTURE.md |
| 3 | День 7 | ADR | [WEEK_2_PLAN.md](WEEK_2_PLAN.md) | 2 ADR: env, auth/roles |
| 4 | | ДЗ 7 | [docs/ADR_TEMPLATE.md](../docs/ADR_TEMPLATE.md) | Шаблон ADR |
| 5 | День 8 | Security | [WEEK_2_PLAN.md](WEEK_2_PLAN.md) | Найти 5 проблем, чек-лист |
| 6 | | ДЗ 8 | [docs/SECURITY_CHECKLIST.md](../docs/SECURITY_CHECKLIST.md) | SECURITY_CHECKLIST.md |
| 7 | День 9 | Тесты | [WEEK_2_PLAN.md](WEEK_2_PLAN.md) | 5 unit + 2 интеграционных |
| 8 | | ДЗ 9 | [docs/AI_TESTING_GUIDE.md](../docs/AI_TESTING_GUIDE.md) | Гайд: как просить тесты |
| 9 | День 10 | Code Review | [WEEK_2_PLAN.md](WEEK_2_PLAN.md) | AI-ревью PR |
| 10 | | ДЗ 10 | [docs/PR_REVIEW_TEMPLATE.md](../docs/PR_REVIEW_TEMPLATE.md) | PR_REVIEW_TEMPLATE.md |

---

## Файлы для создания

| Файл | Назначение |
|------|------------|
| `docs/ARCHITECTURE.md` | Архитектурный контракт (День 6) |
| `docs/ADR_TEMPLATE.md` | Шаблон ADR (День 7) |
| `docs/adr/` | Папка для ADR (2 штуки) |
| `docs/SECURITY_CHECKLIST.md` | Чек-лист security (День 8) |
| `docs/AI_TESTING_GUIDE.md` | Гайд: как просить тесты у AI (День 9) |
| `docs/PR_REVIEW_TEMPLATE.md` | Шаблон для code review (День 10) |

---

## Что должно быть сделано к концу Недели 2

- [ ] AI соблюдает архитектурные границы
- [ ] Решения фиксируются в ADR
- [ ] Security-чек-лист используется перед PR
- [ ] Умею просить тесты у AI корректно
- [ ] Умею отделять шум от реального в AI-ревью
