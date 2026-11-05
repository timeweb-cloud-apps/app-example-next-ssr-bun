![Next.js Logo](https://st.timeweb.com/cloud-static/apps-logo/next.svg)

# Next.js на Bun

Пример приложения [Next.js](https://nextjs.org/) на [Bun](https://bun.sh/) с серверным рендерингом (SSR), которое можно развернуть в **Timeweb Cloud Apps**.

:tada: [Демо]

:rocket: [Создать свой Apps](https://timeweb.cloud/my/apps/create)

:books: [Документация Timeweb Cloud Apps](https://timeweb.cloud/docs/apps)

## Параметры деплоя

Выберите рантайм **Bun**, фреймворк **Next.js** и тип приложения **backend**. Приложение запускается как сервер.

| Параметр | Значение |
| --- | --- |
| Фреймворк | Next.js |
| Версия Bun | 1.2 |
| Тип приложения | `backend` |
| Команда сборки | `bun run build` |
| Команда запуска | `bun run start` |

## <a name="dev"></a>Локальный запуск проекта

```bash
# установка зависимостей
bun install

# запуск в режиме разработки
bun run dev

# сборка для продакшн
bun run build

# запуск собранного серверного приложения
bun run start
```
