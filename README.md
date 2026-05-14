# Лабораторная работа №20. Работа с DOM и событиями в JavaScript

**ФИО**: Пономарёва Наталья Андреевна
**Группа**: ИСП-232
**Дата**: 15.05.2026

### Описание

Научились работать с DOM-деревом и освоили поиск HTML-элементов из JavaScript.

### Структура проекта

+ img - скриншоты
+ index.html - файл для работы main.js
+ main.js - основной файл лабы
+ dynamicElements.html - файл для работы main.js
+ dynamicElements.js - второй файл лабы
+ README.md - о проекте

|Концепция|C# (WinForms)| Самостоятельное|
|---|---|---|
|Найти элемент|Button myButton = this.Controls["myButton"]| const myButton = document.getElementById("myButton")|
|Изменить текст|label1.Text = "Новый текст"| label.textContent = "Новый текст"|
|Добавить обработчик|button1.Click += HandleClick|button.addEventListener("click", handleClick)|
|Создать элемент|Button btn = new Button()|const btn = document.createElement("button")|
|Добавить в контейнер|panel1.Controls.Add(btn)|panel.appendChild(btn)|
|Скрыть элемент|button1.Visible = false|button.style.display = "none"|

### Преимущества DOM перед WinForms:

+ Кроссплатформенность (работает везде)
+ Не нужна установка приложения
+ Легко обновлять (обновил файлы — всё работает)
+ Современные UI (CSS, анимации)

### Преимущества WinForms перед DOM:

+ Визуальный дизайнер (drag & drop)
+ Ошибки на этапе компиляции
+ Интеграция с Windows API
+ Более понятная структура
Вывод: DOM и WinForms решают схожие задачи, но разными подходами.