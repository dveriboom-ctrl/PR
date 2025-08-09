# My Awesome Project

Проект для изучения основ работы с Pull Requests и GitHub Actions.

## Установка

```bash
pip install -r requirements.txt
```

## Запуск тестов

```bash
pytest tests/
```

## Работа с PR

1. Создайте новую ветку: `git checkout -b feature/your-feature`
2. Внесите изменения и коммитьте их
3. Отправьте ветку: `git push origin feature/your-feature`
4. Создайте Pull Request через GitHub интерфейс
5. Дождитесь прохождения всех проверок
6. Получите одобрение от ревьюеров
7. Смержите PR

## GitHub Actions

Проект использует GitHub Actions для:
- Автоматического запуска тестов
- Проверки качества кода (linting)
- Автоматического ревью с помощью Gemini CLI