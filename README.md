# Проект: ИИ-ассистент для компании Codanet
Ссылка на проект: https://t.me/Codanetinfo_bot
---
![Иллюстрация к проекту](https://github.com/OxanaCodanet/ai_assistent/blob/main/Скрин%20разговора%20с%20ботом.jpg?raw=true)

## Оглавление

1. [Введение](#введение)  
2. [Цели проекта](#цели-проекта)  
3. [Функционал ассистента](#функционал-ассистента)  
4. [Технологии и инструменты](#технологии-и-инструменты)  
5. [Архитектура решения](#архитектура-решения)  
6. [Реализация функционала](#реализация-функционала)  
7. [Пример использования](#пример-использования)  
8. [План развития](#план-развития)  
9. [Контакты](#контакты)  

---

## Введение

Проект направлен на создание ИИ-ассистента для компании **Codanet** в Телеграм, который будет помогать в автоматизации рутинных задач, таких как ответы на вопросы клиентов, запись на встречи и управление календарем. Ассистент разработан с использованием передовых технологий искусственного интеллекта, что позволяет ему осмысленно вести диалог и предоставлять точные ответы на основе базы данных компании.

Этот документ содержит подробное описание проекта, его функционала, используемых технологий и планов развития.

---

## Цели проекта

Основная цель проекта — создание эффективного ИИ-ассистента, который:

- Автоматизирует общение с клиентами.
- Обеспечивает быстрый доступ к информации из базы знаний компании.
- Упрощает процесс записи на встречи и управления расписанием.

---

## Функционал ассистента

ИИ-ассистент обладает следующими ключевыми возможностями:

1. **Осмысленное ведение диалога**:
   - Использует нейросетевые модели для понимания контекста и генерации естественных ответов.
   - Может поддерживать длительные диалоги, сохраняя историю общения.

2. **Ответы на вопросы по базе данных**:
   - Предоставляет точные ответы на вопросы клиентов, основываясь на заранее подготовленной базе знаний.
   - Поддерживает поиск информации по различным категориям (например, продукты, услуги, контакты).

3. **Запись клиента на встречу**:
   - Позволяет клиентам записаться на встречу через чат.
   - Автоматически добавляет событие в Google Календарь.

---

## Технологии и инструменты

Для реализации проекта были использованы следующие технологии и сервисы:

1. **Qwen**:
   - Использован для создания системного промта и базы знаний.
   - Позволяет настроить логику работы ассистента и обеспечить точность ответов.

2. **Savvy (http://suvvy.ai/)**:
   - Платформа для создания и управления ИИ-ассистентами.
   - Предоставляет удобный интерфейс для интеграции с различными сервисами и API.

3. **Google Calendar API**:
   - Используется для автоматического добавления встреч в календарь.

4. **Нейросетевые модели**:
   - Базируются на современных языковых моделях, обеспечивающих высокое качество генерации текста.

---

## Архитектура решения

Архитектура проекта состоит из нескольких компонентов:

1. **Frontend**:
   - Интерфейс для взаимодействия с пользователем (чат-интерфейс).
   - Реализован с использованием фреймворка React.

2. **Backend**:
   - Обрабатывает запросы пользователя и взаимодействует с базой знаний и внешними API.
   - Реализован на Node.js.

3. **База знаний**:
   - Хранит информацию о продуктах, услугах и других данных компании.
   - Интегрирована с Qwen для обеспечения точных ответов.

4. **Google Calendar Integration**:
   - Использует Google Calendar API для автоматического добавления встреч.

---

## Реализация функционала

### 1. Осмысленное ведение диалога
- Используется система промтов, созданная с помощью Qwen.
- Модель обучена на данных компании Codanet для обеспечения релевантности ответов.

### 2. Ответы на вопросы по базе данных
- Запросы пользователя анализируются и сравниваются с данными из базы знаний.
- Если подходящий ответ найден, он сразу отправляется пользователю.

### 3. Запись клиента на встречу
- Клиент указывает дату и время встречи через чат.
- Система проверяет доступность времени и добавляет событие в Google Календарь.

---

## Пример использования

#### Сценарий 1: Ответ на вопрос
**Пользователь**: "Какие услуги вы предоставляете?"  
**Ассистент**: "Мы предоставляем услуги разработки программного обеспечения, веб-дизайна и цифрового маркетинга. Подробнее можно узнать здесь: [ссылка]."

#### Сценарий 2: Запись на встречу
**Пользователь**: "Запишите меня на встречу на завтра в 15:00."  
**Ассистент**: "Встреча успешно запланирована на завтра в 15:00. Вы получите напоминание за час до начала."

---

## План развития

На будущее планируется расширение функционала ассистента:

1. **Интеграция с CRM-системой**:
   - Автоматическое добавление лидов и клиентов в CRM.

2. **Мультиязычная поддержка**:
   - Добавление поддержки дополнительных языков для международных клиентов.

3. **Улучшение аналитики**:
   - Внедрение системы анализа эффективности общения с клиентами.

---

## Контакты

Если у вас есть вопросы или предложения по развитию проекта, свяжитесь с нами:

- Email: aiworkplace2024@gmail.com 
- Website: https://kseni-art.ru/
- GitHub: https://github.com/codanet/ai-assistant

--- 

**Спасибо, что выбрали наш ИИ-ассистент! Мы стремимся сделать вашу работу проще и эффективнее.**
