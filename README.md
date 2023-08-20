# План автоматизации тестирования сценария перехода к форме записи и заполнения этой формы

# Перечень автоматизируемых сценариев.

## Сценарии перехода на страницу профессии "Тестировщик ПО" с главной страницы сайта https://netology.ru:

### Сценарий 1. Каталог курсов. Меню профессиий:
1. Открыть https://netology.ru
2. Нажать кнопку "Каталог курсов"
3. В выпадающем меню профессий нажать кнопку "Программирование"
4. Пролистать страницу до появления профессии "Тестировщик ПО"
5. Нажать на ссылку "Тестировщик ПО"
6. Нажать кнопку "Записаться"

### Сценарий 2. Каталог курсов. Поле ввода. Профессия целиком:
1. Открыть https://netology.ru
2. Нажать кнопку "Каталог курсов"
3. В выпадающем поле ввода "Какой курс вам нужен?" вписать "Тестировщик ПО"
4. Нажать Enter
5. Нажать на появившуюся ссылку "Тестировщик ПО"
6. Нажать кнопку "Записаться"

### Сценарий 3. Каталог курсов. Поле ввода. Начало называния профессии:
1. Открыть https://netology.ru
2. Нажать кнопку "Каталог курсов"
3. В выпадающем поле ввода "Какой курс вам нужен?" вписать "Тест"
4. В выпадающем меню нажать на "Тестировщик ПО"
5. Нажать кнопку "Записаться"

### Сценарий 4. Полный каталог. Меню профессиий:
1. Открыть https://netology.ru
2. Пролистать страницу до кнопки "Полный каталог"
3. Нажать кнопку "Полный каталог"
4. В выпадающем меню профессий нажать кнопку "Программирование"
5. Пролистать страницу до появления профессии "Тестировщик ПО"
6. Нажать на ссылку "Тестировщик ПО"
7. Нажать кнопку "Записаться"

### Сценарий 5.Полный каталог. Поле ввода. Профессия целиком:
1. Открыть https://netology.ru
2. Пролистать страницу до кнопки "Полный каталог"
3. Нажать кнопку "Полный каталог"
4. В выпадающем поле ввода "Какой курс вам нужен?" вписать "Тестировщик ПО"
5. Нажать Enter
6. Нажать на появившуюся ссылку "Тестировщик ПО"
7. Нажать кнопку "Записаться"

### Сценарий 6. Полный каталог. Поле ввода. Начало называния профессии:
1. Открыть https://netology.ru
2. Пролистать страницу до кнопки "Полный каталог"
3. Нажать кнопку "Полный каталог"
4. В выпадающем поле ввода "Какой курс вам нужен?" вписать "Тест"
5. В выпадающем меню нажать на "Тестировщик ПО"
6. Нажать кнопку "Записаться"

## Сценарии заполнения формы

### Сценарий 1. Валидные значения. Имя кириллицей
1. Вписать в поле "Имя": Вася
2. Вписать в поле ввода номера телефона: "+79261234567"
3. Вписать в поле "Электронная почта": 123@asd.ru
4. Нажать кнопку "Записаться"
5. Убедиться, что открылась страница оплаты, содержащая надртсь "Вы записались на курс"

### Сценарий 2. Валидные значения. Имя на английском языке
1. Вписать в поле "Имя": "Vasya"
2. Вписать в поле ввода номера телефона: "+79261234567"
3. Вписать в поле "Электронная почта": 123@asd.ru
4. Нажать кнопку "Записаться" 
5. Убедиться, что открылась страница оплаты, содержащая надртсь "Вы записались на курс"
   
### Сценарий 3. Валидные значения. Имя с маленькой буквы
1. Вписать в поле "Имя": "vasya"
2. Вписать в поле ввода номера телефона: "+79261234567"
3. Вписать в поле "Электронная почта": 123@asd.ru
4. Нажать кнопку "Записаться"
5. Убедиться, что открвлась страница оплаты, содержащая надртсь "Вы записались на курс"

### Сценарий 4. Валидные значения. Имя с пробелом
1. Вписать в поле "Имя": "Вася Пупкин"
2. Вписать в поле ввода номера телефона: "+79261234567"
3. Вписать в поле "Электронная почта": 123@asd.ru
4. Нажать кнопку "Записаться"
5. Убедиться, что открвлась страница оплаты, содержащая надртсь "Вы записались на курс"
   
### Сценарий 5. Валидные значения. Дефис
1. Вписать в поле "Имя": "Вася-Пупкин"
2. Вписать в поле ввода номера телефона: "+79261234567"
3. Вписать в поле "Электронная почта": 123@asd.ru
4. Нажать кнопку "Записаться"
5. Убедиться, что открвлась страница оплаты, содержащая надртсь "Вы записались на курс"

### Сценарий 6. Невалидные значения. Символы в поле "Имя"
1. Вписать в поле "Имя": "*"
2. Убедиться, что поле "Имя" выделено красным
3. Убедиться, что поля "Имя" подписано красным как "Должно состоять из букв"
4. Убедиться, что кнопка "Записаться" не функционирует

### Сценарий 7. Невалидные значения. Символы в поле ввода номера телефона
2. Вписать в поле ввода номера телефона: "."
3. Убедиться, что поле ввода номера телефона выделено красным
4. Убедиться, что поле ввода номера телефона подписано красным как "Должно состоять из букв"
5. Убедиться, что кнопка "Записаться" не функционирует

### Сценарий 8. Невалидные значения. Пустые поля
1. Оставить поля ввода имени, номера телефона и e-mail пустыми
2. Убедиться, что поля выделены красным
3. Убедиться, что поля подписаны красным как "обязательное поле"
4. Убедиться, что кнопка "Записаться" не функционирует

### Сценарий 9. Невалидные значения. 15 цифр в номере без "+"
1. Вписать в поле "Имя": Вася
2. Вписать в поле ввода номера телефона: "123456789101112"
4. Убедиться, что поле ввода номера подписано красным с текстом: "Номер в формате +9 (999) 999-99-99"
4. Убедиться, что кнопка "Записаться" не функционирует

### Сценарий 10. Невалидные значения. 8 цифр в номере без "+"
1. Вписать в поле "Имя": Вася
2. Вписать в поле ввода номера телефона: "12345678"
4. Убедиться, что поле ввода номера подписано красным с текстом: "Номер в формате +9 (999) 999-99-99"
4. Убедиться, что кнопка "Записаться" не функционирует

### Сценарий 11. Невалидные значения. Буквы в поле ввода номера телефона
1. Вписать в поле "Имя": Вася
2. Вписать в поле ввода номера телефона: "фыв"
3. Убедиться, что поле ввода номера выделено красным
4. Убедиться, что поле ввода номера подписано красным с текстом: "Номер в формате +9 (999) 999-99-99"
5. Убедиться, что кнопка "Записаться" не функционирует

### Сценарий 12. Невалидные значения. Электронная почта без "@"
1. Вписать в поле "Электронная почта": 123asd.ru
2. Убедиться, что поле "Электронная почта" выделено красным
3. Убедиться, что поле "Электронная почта" подписано красным с тектом "Неверный email"
4. Убедиться, что кнопка "Записаться" не функционирует

# Перечень используемых инструментов с обоснованием выбора

1. Java. Автоматизированное тестирование удобно осуществлять с помощью этого языка
3. Selenide. Для написания удобных для чтения и обслуживания автоматизированных тестов на Java
3. Junit. Для модульного тестирования программного обеспечения на языке Java
4. Faker. Для ускорения заполнения форм
5. Lombok. Для сокращения шаблонного кода
6. Gradle. Для автоматической сборки
7. Allure. Для построения отчётов автотестов с упрощением их анализа
   
# Перечень необходимых разрешений, данных и доступов

1. Доступ к сайту
2. Разрешение на тестирование
3. Разрешение пользоваться тестовой версией, если есть
4. Разрешение тестировать API, если требуется

# Перечень и описание возможных рисков при автоматизации

1. Вероятность продления времени выполнения
2. Вероятность отсутствия возможности подключения
3. Вероятность недоступности сайта
4. Вероятность нехватки информации для выполнения работы
5. Вероятность настабильной работы системы
6. Вероятность сложности с поиском элементов на страницах
7. Вероятность изменения структуры сайта до завершения работы
 
# Перечень необходимых специалистов для автоматизации

1. Специалист, имеющий навыки автоматизированного тестирования, для реализации проекта автотамизации тестирования

# Интервальная оценка с учётом рисков в часах

Приблизительно 24 часа

