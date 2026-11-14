# SvelteKit

Пример приложения [SvelteKit](https://svelte.dev/docs/kit), которое можно развернуть без настройки.

## Параметры деплоя

Приложение разворачивается как frontend: [`@sveltejs/adapter-static`](https://svelte.dev/docs/kit/adapter-static) пререндерит страницы в HTML (`prerender = true` в `src/routes/+layout.ts`).

| Параметр          | Значение        |
| ----------------- | --------------- |
| Фреймворк         | SvelteKit       |
| Команда сборки    | `npm run build` |
| Директория сборки | `build`         |

## <a name="dev"></a>Локальный запуск проекта

```bash
# установка зависимостей
npm install

# запуск в дев режиме с отслеживанием изменений
npm run dev

# сборка для продакшн с минификацией
npm run build

# локальный просмотр собранной сборки
npm run preview
```

Для работы нужен Node.js 22.17 или новее.
