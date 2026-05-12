# Установка GitHub Profile README

1. Создай публичный репозиторий с точным именем:

   `FibonacciFox`

   Полный путь должен быть:

   `https://github.com/FibonacciFox/FibonacciFox`

2. Скопируй в репозиторий файлы из архива:

   - `README.md`
   - `.github/workflows/snake.yml`

3. Включи права для GitHub Actions:

   Repository Settings → Actions → General → Workflow permissions → Read and write permissions

4. Запусти snake workflow вручную:

   Actions → Generate Snake → Run workflow

5. После первого запуска workflow создаст ветку `output`, и contribution snake начнет отображаться в README.

## Что входит

- Красивый animated header через capsule-render
- Typing SVG анимация
- Shields.io tech stack badges
- Featured projects
- GitHub stats
- GitHub streak
- Activity graph
- Contribution snake через GitHub Actions
- Footer wave animation

## Важно

Некоторые картинки генерируются внешними сервисами. Если GitHub временно не показывает изображение, обычно достаточно подождать или обновить страницу позже.
