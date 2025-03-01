# AI-ассистент - личный менеджер

AI-ассистент — это интеллектуальный помощник, созданный для улучшения качества жизни пользователя за счет эффективного управления временем, задачами и коммуникацией. Этот проект направлен на помощь в планировании встреч, организации мероприятий и поддержании осмысленного диалога с близкими людьми.

## Основные функции

### 1. **Осмысленное ведение диалога**
AI-ассистент способен вести естественные и эмпатичные диалоги с пользователем. Благодаря использованию нейросетей, ассистент понимает контекст, учитывает эмоции и предлагает релевантные ответы.

### 2. **Ответы на вопросы по базе знаний**
Ассистент может отвечать на вопросы, используя предварительно созданную базу знаний. Это позволяет предоставлять точные и полезные ответы на часто задаваемые вопросы или запросы, связанные с конкретной темой.

### 3. **Планирование встреч и мероприятий**
Одной из ключевых функций является возможность планирования встреч и мероприятий. Ассистент автоматически добавляет запланированные события в Google Calendar, что делает процесс организации времени максимально удобным.

---

## Использованные сервисы

### 1. **Qwen**
- **Роль**: Создание системного промпта и базы знаний.
- **Описание**: Qwen используется для разработки структурированного промпта, который определяет поведение ассистента, а также для формирования базы знаний, на основе которой ассистент отвечает на вопросы.

### 2. **Савви (Suvvy)**
- **Сайт**: [https://app.suvvy.ai](https://app.suvvy.ai)
- **Роль**: Создание ИИ-ассистента.
- **Описание**: Платформа Савви предоставляет инструменты для создания и настройки ИИ-ассистентов. Она позволяет интегрировать различные функции, такие как диалоговый интерфейс, управление календарем и взаимодействие с базой знаний.

---

## Установка и настройка

### Предварительные требования
- Аккаунт Google для доступа к Google Calendar API.
- Доступ к платформе Савви ([https://app.suvvy.ai](https://app.suvvy.ai)).
- Настроенный промпт и база знаний через Qwen.

### Шаги для установки
1. **Настройка Google Calendar API**:
   - Перейдите в [Google Cloud Console](https://console.cloud.google.com/).
   - Создайте новый проект и активируйте Google Calendar API.
   - Получите учетные данные (API key) для интеграции с ассистентом.

2. **Создание ассистента в Савви**:
   - Зарегистрируйтесь на платформе Савви.
   - Создайте нового ассистента и настройте его функционал, указав параметры для диалогового интерфейса и интеграции с Google Calendar.

3. **Настройка базы знаний через Qwen**:
   - Разработайте системный промпт, описывающий поведение ассистента.
   - Создайте базу знаний, содержащую информацию, на основе которой ассистент будет отвечать на вопросы.

4. **Тестирование**:
   - Проверьте работу ассистента, отправляя тестовые запросы.
   - Убедитесь, что события корректно добавляются в Google Calendar.

---

## Пример использования

### Ведение диалога
**Запрос пользователя**:  
"Как мне организовать встречу с друзьями на выходных?"

**Ответ ассистента**:  
"Давайте спланируем! Когда именно вы хотите встретиться? Я могу предложить несколько вариантов мест и занятий, например, кафе, парк или настольные игры. После этого я добавлю событие в ваш Google Calendar."

### Планирование встречи
**Запрос пользователя**:  
"Запланируй встречу с коллегами на пятницу в 15:00."

**Действие ассистента**:  
- Создает событие "Встреча с коллегами" в Google Calendar на пятницу в 15:00.
- Отправляет уведомление пользователю об успешном добавлении события.

---

## Лицензия

Этот проект распространяется под лицензией MIT. Подробности см. в файле [LICENSE](LICENSE).

---

## Авторы

- **[Ваше имя]**  
  GitHub: [ссылка на ваш профиль]  
  Email: [ваш email]

---

## Благодарности

- Команде Qwen за мощные инструменты для создания промптов и баз знаний.
- Платформе Савви за удобные инструменты разработки ИИ-ассистентов.
- Google Calendar API за надежную интеграцию.

---
