## 📚 Полезные ресурсы

1. [Setting up your IDE and installing BMC Helix Innovation Studio SDK](https://docs.bmc.com/xwiki/bin/view/Service-Management/Innovation-Suite/BMC-Helix-Innovation-Suite/is233/Developing-applications-by-using-BMC-Helix-Innovation-Studio/Developing-and-deploying-code-based-applications/Setting-up-the-environment-to-develop-a-code-based-application/Setting-up-your-IDE-and-installing-BMC-Helix-Innovation-Studio-SDK/)

2. [Creating a Project using Maven and the Archetype](https://docs.bmc.com/xwiki/bin/view/Service-Management/Innovation-Suite/BMC-Helix-Innovation-Suite/is233/Developing-applications-by-using-BMC-Helix-Innovation-Studio/Developing-and-deploying-code-based-applications/Setting-up-the-environment-to-develop-a-code-based-application/Creating-a-Project-using-Maven-and-the-Archetype/)

3. [Deploying your application for the first time to start working in BMC Helix Innovation Studio](https://docs.bmc.com/xwiki/bin/view/Service-Management/Innovation-Suite/BMC-Helix-Innovation-Suite/is233/Developing-applications-by-using-BMC-Helix-Innovation-Studio/Developing-and-deploying-code-based-applications/Setting-up-the-environment-to-develop-a-code-based-application/Deploying-your-application-for-the-first-time-to-start-working-in-BMC-Helix-Innovation-Studio/)

---

## 🧩 Tooltip
Создать Angular-компонент **Tooltip**, который поддерживает:  
- позицию отображения (`top`, `right`, `bottom`, `left`);  
- способ отображения: по `hover` или `focus`;  
- интегрировать в **Books_View**: при наведении на поле **Price** появляется подсказка:  
  > 💬 «Цена указана в $USD»

---

## ✉️ Валидация Publisher Email
Реализовать валидацию на **Publishers_View**:  
Поле **Publisher Email** должно соответствовать формату **email**.  

❌ При нарушении условий должно выводиться **сообщение об ошибке** или **подсказка**.

---

## 🎨 Кастомный CSS-стиль
Добавить кастомный стиль для любого поля:  

- 🟩 зелёная рамка вокруг `input`;  
- 🌫️ текст в поле должен обрезаться с «fade out» эффектом  
  *(например, через `linear-gradient` или `ellipsis`)*.  

---

## 🗂️ Компонент «Карточки»
Создать компонент **«Карточки»** и отобразить список карточек на основе данных:  

- данные можно взять из regular record **Books**,  
- либо захардкодить массив объектов.  

---

## 📊 Таблица с данными
Создать таблицу с данными из формы **Books** (или любого стороннего API) и реализовать:  

- фильтрацию по одному или нескольким полям (например, `Title` или `Price`);  
- пагинацию по страницам.  

> 💡 Если непонятно как брать данные из форм в текущей структуре,  
> можно использовать внешний источник ниже или любой другой API по своему выбору:  
> [🌐 Wizard World API](https://wizard-world-api.herokuapp.com/swagger/index.html)  

---
## ⚡ Бонус (по желанию)

- Подключить lazy loading для одного из компонентов.  
- Реализовать визуализацию данных (график/диаграмма) на основе Books.  
- Подключить и продемонстрировать работу внешней библиотеки (например, **ngx-tour** или **shepherd.js**).  
- Применить базовые стили **Hexa UI**: цвета, spacing, размеры или иконки на свой выбор.  
- Локализовать один-два компонента на два языка (например, английский и русский) используя встроенные средства.  
