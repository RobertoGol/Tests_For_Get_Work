# Тестовое задание: Login Form & ReqRes API

## 1. Test Plan (Краткий тест-план)

### Scope (Область тестирования)
* **Web:** Авторизация на странице `https://herokuapp.com` (Desktop).
* **Mobile Web:** Адаптивность и мобильная специфика формы в мобильном браузере.
* **API:** Базовые CRUD-операции (GET, POST, PUT, DELETE) в сервисе `https://reqres.in`.{API-key not provided}

### Types of Testing (Виды тестирования)
* **Functional:** Логика входа и корректность ответов API.
* **Negative:** Обработка ошибок (неверные данные, пустые поля).
* **UI/UX:** Верстка, доступность элементов, сообщения об ошибках.
* **Mobile Testing:** Прерывания, ориентация экрана, экранная клавиатура.
* **API Testing:** Валидация статус-кодов и структуры JSON.

### Environments & Tools (Среда и инструменты)
* **Browsers:** Google Chrome (Desktop), Firefox (Desktop), Chrome (Android).
* **Devices:** Реальный смартфон (Android).
* **API Tool:** Postman. 
* **Documentation:** GitHub (Markdown).

### Risks & Limitations (Риски и ограничения)
* **Данные:** Публичные песочницы могут изменять данные сторонними пользователями.
* **Доступ:** Отсутствие доступа к БД и логам сервера (Black Box testing).
* **Время:** Лимит 3–5 часов исключает глубокое регрессионное и нагрузочное тестирование.

##Сылка на баг репорты [Bug-reports](https://github.com/RobertoGol/Tests_For_Get_Work/blob/main/I%20Test/tests.md)
