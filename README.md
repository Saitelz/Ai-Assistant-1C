# ИИ-ассистент для 1С:ERP

Расширение, предоставляющее интеллектуального помощника для пользователей 1С:ERP Управление предприятием. Расширение представляет собой небольшое окно с минималистичным дизайном, которое позволяет пользователям задавать вопросы и получать ответы от ИИ-ассистента в контексте работы с 1С:ERP.

## Возможности

- Задавать вопросы на естественном языке
- Получать ответы с пошаговыми инструкциями
- Помощь новичкам в навигации по интерфейсу 1С:ERP
- Объяснение функционала системы
- Получение подсказок и рекомендаций

## Структура расширения

Расширение состоит из следующих основных компонентов:

- `CommonModules/AI_AssistantModule` - модуль для работы с API ИИ
- `Forms/AI_AssistantForm` - форма интерфейса ИИ-ассистента
- `Commands/OpenAI_Assistant` - команда для открытия окна ассистента
- `Subsystems/AI_Assistant` - подсистема расширения

## Требования

- 1С:Предприятие 8.3.14 или выше
- 1С:ERP Управление предприятием
- Доступ к API OpenAI (или другому выбранному провайдеру ИИ)
- Наличие ключа API для доступа к сервисам ИИ

## Установка

1. Скачайте файлы расширения из репозитория
2. В режиме "Конфигуратор" откройте конфигурацию 1С:ERP
3. Выберите пункт меню "Расширения конфигурации"
4. Нажмите "Добавить" и выберите файлы расширения
5. Сохраните и обновите конфигурацию

## Настройка

1. После установки расширения запустите 1С:ERP в режиме "Предприятие"
2. Найдите и откройте "ИИ-ассистент" в разделе "Администрирование" или через поиск
3. Нажмите на кнопку "Настройки" в правом верхнем углу
4. Введите свой ключ API для доступа к сервисам ИИ
5. Выберите модель ИИ (по умолчанию GPT-4)
6. Сохраните настройки

## Использование

1. Откройте окно ИИ-ассистента через меню или команду
2. Введите свой вопрос в текстовое поле
3. Нажмите кнопку "Отправить запрос"
4. Получите ответ от ИИ с инструкциями и рекомендациями

## Примеры вопросов

- "Как создать нового контрагента?"
- "Где найти отчет по остаткам товаров?"
- "Как провести инвентаризацию?"
- "Как настроить права пользователей?"
- "Как сформировать финансовый отчет за месяц?"

## Дополнительная информация

Это расширение использует HTTP сервисы для взаимодействия с внешними API. Убедитесь, что у вас есть соответствующие разрешения в настройках безопасности 1С.

## Техническая поддержка

По вопросам технической поддержки обращайтесь по адресу: support@example.com 