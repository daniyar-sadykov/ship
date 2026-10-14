# ship

Плагин из одной команды.

- `commands/ship.md`: команда `/ship`, довести работу до влитого `main`.

Скиллов, агентов и хуков в плагине нет намеренно. Команда самодостаточна:
все правила, которые ей нужны (ветка под работу, conventional commits,
порядок проверок, squash-влитие, запреты), записаны в её тексте, поэтому
она не зависит от содержимого `CLAUDE.md` в проекте ученика.

## Установка

```
/plugin install ship --marketplace daniyar-sadykov/ship
```

Требования и способы без маркетплейса: [README репозитория](../../README.md).

## Проверка

```bash
claude plugin validate --strict plugins/ship
```
