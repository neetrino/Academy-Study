# Скрипт рутины перед PR

**Курс:** AI-Coding в Cursor  
**День 12:** Agent + Terminal — безопасная автоматизация

Что прогоняем перед каждым PR. Порядок выполнения.

---

## Чек-лист перед PR

### 1. Линтер

```bash
# Примеры по стеку:
npm run lint
# или
pnpm lint
# или
eslint .
```

- [ ] Линтер **без ошибок**

### 2. Форматтер (если отдельно)

```bash
npm run format
# или
prettier --write .
```

- [ ] Код отформатирован

### 3. Проверка типов (если есть)

```bash
npm run typecheck
# или
tsc --noEmit
```

- [ ] Типы в порядке

### 4. Тесты

```bash
npm test
# или
npm run test
```

- [ ] Все тесты **зелёные**

### 5. Сборка

```bash
npm run build
```

- [ ] Сборка **успешна**

### 6. Security (опционально)

```bash
npm audit
```

- [ ] Нет критичных уязвимостей (или задокументированы)

---

## Один скрипт (если поддерживается)

```bash
# package.json
"scripts": {
  "pre-pr": "npm run lint && npm run typecheck && npm test && npm run build"
}
```

```bash
npm run pre-pr
```

---

## Правило

> **Не пушить**, пока всё не зелёное. Agent может запускать команды — проверяй вывод сам.
