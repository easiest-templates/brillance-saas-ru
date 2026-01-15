![Preview](https://cdn.poehali.dev/templates/brillance-saas-ru/preview.jpg)

# Бриллиант SaaS Landing Page (RU)

Современный лендинг для SaaS-продукта автоматизации биллинга, выполненный в стиле premium с градиентами и анимациями.

## Теги

`saas` `gradient` `general` `pricing`

## Описание

Бриллиант - это шаблон лендинга для SaaS-продуктов, ориентированных на автоматизацию биллинга и управление подписками. Дизайн выполнен в теплых коричневых тонах с мягкими градиентами, что создает ощущение премиальности и надежности.

## Особенности

- **Адаптивный дизайн** - полная поддержка мобильных устройств, планшетов и десктопов
- **Современный UI** - использование Tailwind CSS, shadcn/ui компонентов
- **Интерактивные секции** - анимированные карточки, слайдеры отзывов, переключатель тарифов
- **Полная русская локализация** - весь контент переведен на русский язык
- **Оптимизированная производительность** - собран на Vite с React

## Секции лендинга

1. **Hero** - главный блок с заголовком и CTA
2. **Feature Cards** - карточки с основными возможностями
3. **Social Proof** - логотипы клиентов
4. **Bento Grid** - визуальные демонстрации функций
5. **Documentation** - секция с возможностями платформы
6. **Testimonials** - отзывы клиентов
7. **Pricing** - тарифные планы с переключателем годовой/месячной оплаты
8. **FAQ** - часто задаваемые вопросы
9. **CTA** - призыв к действию
10. **Footer** - подвал с навигацией и соцсетями

## Технологии

- React 18
- TypeScript
- Vite 5
- Tailwind CSS
- shadcn/ui
- React Router

## Установка и запуск

```bash
# Установка зависимостей
npm install

# Запуск dev сервера
npm run dev

# Сборка для production
npm run build
```

## Структура проекта

```
src/
├── components/
│   ├── landing/          # Компоненты лендинга
│   │   ├── CTASection.tsx
│   │   ├── DocumentationSection.tsx
│   │   ├── EffortlessIntegration.tsx
│   │   ├── FAQSection.tsx
│   │   ├── FooterSection.tsx
│   │   ├── NumbersThatSpeak.tsx
│   │   ├── PricingSection.tsx
│   │   ├── SmartSimpleBrilliant.tsx
│   │   ├── TestimonialsSection.tsx
│   │   └── YourWorkInSync.tsx
│   └── ui/               # shadcn/ui компоненты
├── pages/
│   └── Index.tsx         # Главная страница
└── index.css             # Стили
```

## Шрифты

- **Inter** - основной шрифт для UI
- **Instrument Serif** - акцентный шрифт для заголовков

## Лицензия

MIT
