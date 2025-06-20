# Al_assistant_restaurant

# Проект: Ресторан итальянской кухни "Везувий"  
## ИИ-ассистент для автоматизации обслуживания клиентов

## Сслылка на проект @restaurant_Vezuvyi_bot

![скрин 1](https://github.com/Airathabib/Al_assistant_restaurant/blob/main/vez-5.png)
![скрин 2](https://github.com/Airathabib/Al_assistant_restaurant/blob/main/vez-6.png)

### **Цель проекта**  
Создание интеллектуального ассистента для ресторана итальянской кухни "Везувий", способного:  
- Вести диалог с клиентами с помощью нейросети.  
- Отвечать на вопросы по меню, акциям и услугам на основе базы знаний.  
- Автоматически записывать клиентов на встречи и добавлять их в Google Календарь.  

---

### **Основные функции проекта**  

#### 1. **Интеллектуальное ведение диалогов**  
- **Технология**: ИИ-ассистент на платформе **Савви (Suvvy.ai)**.  
- **Особенности**:  
  - Отвечает на **100% обращений** клиентов (гарантия Suvvy).  
  - Точность ответов **от 95%** (по данным Suvvy).  
  - Поддерживает сложные сценарии: бронирование, консультации по меню, вопросы о доставке.  
  - Интеграция с мессенджерами (Telegram, WhatsApp) и сайт ресторана.  

#### 2. **База знаний**  
- **Создание**: На основе **Qwen** (нейросети Alibaba Cloud).  
- **Содержание**:  
  - Информация о меню, акциях, времени работы, расположении.  
  - Рекомендации по блюдам, аллергены, диетические ограничения.  
  - Правила бронирования, условия доставки, особенности банкетов.  
- **Обновление**: Автоматическое обновление базы через интерфейс Suvvy.  

#### 3. **Автоматизация бронирования**  
- **Процесс**:  
  1. Клиент связывается с ИИ-ассистентом через сайт или мессенджер.  
  2. Ассистент задает уточняющие вопросы (дата, время, количество гостей).  
  3. Если есть свободные места, автоматически добавляет встречу в **Google Календарь** ресторана.  
  4. Отправляет клиенту подтверждение с деталями брони.  
- **Интеграция**: Suvvy + Google Calendar API.  

---

### **Технологии и сервисы**  
| **Сервис** | **Роль в проекте** |  
|------------|-------------------|  
| **Савви (Suvvy.ai)** | Основная платформа для создания ИИ-ассистента: <br> - Обработка естественного языка. <br> - Интеграция с CRM и календарями. <br> - Поддержка сложных сценариев. |  
| **Qwen** | Создание базы знаний: <br> - Формирование системного промпта. <br> - Структурирование данных о меню и услугах. |  
| **Google Calendar** | Автоматическое управление бронированием столиков. |  

---

### **Пример работы системы**  
**Сценарий 1: Запрос о бронировании**  
- **Клиент**: "Хочу забронировать столик на 6 человек на 15.10 в 19:00".  
- **ИИ-ассистент**:  
  - Проверяет доступность времени в календаре.  
  - Если свободно: "Столик на 6 человек на 15.10 в 19:00 забронирован. Подтверждение отправлено на ваш email."  
  - Если занято: предлагает альтернативные варианты.  

**Сценарий 2: Вопрос о меню**  
- **Клиент**: "Есть ли у вас веганская пицца?"  
- **ИИ-ассистент**:  
  - Отвечает: "Да, у нас есть пицца «Фиори ди Везувий» с овощами и соевым сыром. Она готовится в дровяной печи и стоит 650 рублей."  
  - Предлагает: "Хотите записаться на дегустацию веган-меню?"  

---

### **Преимущества проекта**  
1. **Снижение нагрузки на персонал**: Автоматизация 80% рутинных запросов.  
2. **Увеличение точности**: Ответы на основе проверенной базы знаний (Qwen + Suvvy).  
3. **Сокращение времени бронирования**: Клиенты могут записаться за 2 минуты.  
4. **Расширение каналов продаж**: Интеграция с мессенджерами и сайтами.  

---

### **Этапы реализации**  
1. **Сбор данных**: Формирование базы знаний о меню, акциях, услугах.  
2. **Настройка Suvvy**:  
   - Создание сценариев диалогов.  
   - Интеграция с Google Calendar.  
3. **Тестирование**: Проверка точности ответов и работы календаря.  
4. **Запуск**: Интеграция с сайтами и мессенджерами.  
5. **Мониторинг**: Аналитика эффективности через Suvvy Dashboard.  

---

### **Примеры интеграции**  
| **Канал** | **Пример ответа ИИ-ассистента** |  
|-----------|--------------------------------|  
| **Telegram** | "Добрый день! Это ресторан ‘Везувий’. Для бронирования столика укажите дату, время и количество гостей." |  
| **Сайт** | "Наша пицца готовится в дровяной печи при температуре +400°C. Хотите попробовать ‘Маргариту’ с моцареллой из Базиликата?" |  

---

### **Итог**  
Проект автоматизирует общение с клиентами, повышает качество обслуживания и увеличивает лояльность гостей. Благодаря Suvvy и Qwen, ресторан "Везувий" становится одним из первых в категории fine dining, где ИИ помогает создавать персонализированные впечатления.  
