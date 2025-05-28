# Vue 3 + TypeScript + Tailwind ToDo App

Мінімальний приклад ToDo-застосунку з фільтрацією, drag & drop сортуванням, темною темою та лічильником виконаних задач. Реалізовано на Vue 3 + TypeScript + Tailwind CSS.

---

## Особливості

- Додавання та видалення задач  
- Фільтрація задач: всі, активні, виконані  
- Drag & Drop сортування задач через [Vue Draggable Next] 
- Лічильник виконаних задач (Completed: X / Y)  
- Перемикання світлої / темної теми з автоматичним збереженням у `localStorage`  
- Збереження задач у `localStorage` для збереження стану між сесіями  

---

## Технології

- Vue 3 (Composition API + `<script setup>`)  
- TypeScript  
- Tailwind CSS (з підтримкою світлої та темної тем)  
- Vue Draggable Next (для drag & drop)  

---

## Установка

```bash
git clone https://github.com/your-repo/todo-vue3.git
cd todo-vue3
npm install
npm run dev
