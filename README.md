# WEST — Premium Referral Website

Адаптивный React + TypeScript сайт по предоставленному ТЗ.

## Запуск локально

```bash
npm install
npm run dev
```

## Production-сборка

```bash
npm run build
npm run preview
```

## Настройка ссылок

Измени значения в `src/config.ts`:
- `REFERRAL_URL` — реферальная ссылка.
- `TELEGRAM_URL` — Telegram менеджера.
- `TELEGRAM_HANDLE` — отображаемый контакт.

## Стек

- React 18 + TypeScript
- Vite
- Tailwind CSS
- Framer Motion
- Lucide React

## Примечания

- 3D-карта сделана на CSS 3D transforms и Framer Motion, без сторонних изображений и официальных бренд-ассетов.
- Указанные 300 ₽ и 50 ₽ обозначены как потенциальное вознаграждение, зависящее от действующих правил и проверки.
- В проекте предусмотрено юридическое уведомление о независимом характере WEST.
- Анимации учитывают `prefers-reduced-motion`.
