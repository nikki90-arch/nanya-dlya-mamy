# Няня для мамы 🌸

AI-собеседница для молодых мам. Работает 24/7, без осуждения.

## Деплой на Vercel (5 минут)

### Шаг 1 — Загрузи проект на GitHub
1. Зайди на github.com → New repository
2. Назови: `nanya-dlya-mamy`
3. Загрузи все файлы этой папки

### Шаг 2 — Подключи Vercel
1. Зайди на vercel.com → Add New Project
2. Выбери репозиторий `nanya-dlya-mamy`
3. Framework Preset: **Other**
4. Root Directory: оставь пустым
5. Нажми **Deploy**

### Шаг 3 — Добавь API ключ
1. В Vercel → Settings → Environment Variables
2. Добавь переменную:
   - Name: `ANTHROPIC_API_KEY`
   - Value: твой ключ с console.anthropic.com
3. Нажми Save
4. **Redeploy** (важно!)

### Готово! 🎉
Vercel даст тебе ссылку вида: `nanya-dlya-mamy.vercel.app`
Можно скинуть подругам сразу.

### Свой домен (опционально)
Settings → Domains → добавь свой домен

## Структура проекта
```
/api/chat.js      ← backend: проксирует запросы к Claude API
/public/index.html ← всё приложение
/vercel.json      ← конфиг Vercel
```

## Получить API ключ
1. console.anthropic.com
2. API Keys → Create Key
3. Скопируй и вставь в Vercel
