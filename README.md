# Тест план для веб-сайт Нетологии

## 1 Исследование функционала сайта и требуемого для автоматизации тестирования

## 2 Чеклист
1. автоматизация тестирования входа на страницу професии с главной страницы сайта :высокая важность
2. автоматизация тестирования всех 3 вариантов записей на странице професии :высокая важность

## 3 Тест кейсы
1. коректный вход на страницу професии: испульзуя  валидный селлектор полученный с помощью DevTools вход на каталог курсов а,
 затем с помощью валидного селектора отуда вход на страницу професии
приоритет высокий , предусловие вход на страницу и получение необходимого селектора, ожидаймый результат : успешный вход на страницу професии.
2. коректный вход на страницу професии: испульзуя  валидный селлектор полученный с помощью DevTools вход на направление обучения:програмирование,
 а затем с помощью валидного селектора отуда вход 
на страницу професии
приоритет высокий , предусловие вход на страницу и получение необходимого селектора, ожидаймый результат : успешный вход на страницу професии.
3. некоректный вход на страницу професии: испульзуя  валидный селлектор полученный с помощью DevTools попытка вход на каталог курсов,
 а затем с помощью невалидного селектора отуда вход на страницу професии
приоритет средний , предусловие вход на страницу и получение необходимого селектора, ожидаймый результат :тест выдал ошибку связаную с селектором.
4. некоректный вход на страницу професии: испульзуя  валидный селлектор полученный с помощью DevTools вход на направление обучения:програмирование,
 а затем с помощью невалидного селектора отуда вход 
попытка вхожана страницу професии
приоритет средний , предусловие вход на страницу и получение необходимого селектора с помощью DevTools, ожидаймый результат :тест выдал ошибку связаную с селектором.
5. нажатие кнопки "Записаться",в верхней части  страницы професии: с помощью селектора нажимаем кнопку записаться с верху страцы професии
приоритет средний , предусловие вход на страницу професии и получение необходимого селектора с помощью DevTools, ожидаймый результат :
находимся в нижней части страницы у полей ввода и кнопки записи.
6. некоректное нажатие кнопки "Записаться",в верхней части  страницы професии: с помощью некоректного селектора нажимаем кнопку записаться с верху страцы професии
приоритет низкий , предусловие вход на страницу професии и получение необходимого селектора с помощью DevTools, ожидаймый результат :падение теста из за неверного селектора.
7. Успешная запись , ввод коректых значений в поля имени, почты и телефона , а также нажатие кнопки с помощью селекторов
приоритет высокий ,предусловие вход на страницу професии и получение необходимых селекторов с помощью DevTools, ожидаймый результат :успешная запись на курс.
8. Ввод имени латиницей, ввод коректых значений в поля  почты и телефона , а также нажатие кнопки с помощью селекторов, но ввод имени латинскими символами
приоритет высокий ,предусловие вход на страницу професии и получение необходимых селекторов с помощью DevTools, ожидаймый результат :вывод ошибки:ввод имени возможен только рускими буквами.
9. Ввод имени цифрами или спецсимволами, ввод коректых значений в поля  почты и телефона , а также нажатие кнопки с помощью селекторов, но ввод имени цифрами или спецсимволами
приоритет высокий ,предусловие вход на страницу професии и получение необходимых селекторов с помощью DevTools, ожидаймый результат :вывод ошибки:ввод имени возможен только рускими буквами.
10. Ввод почты  рускими буквами, ввод коректых значений в поля  имени, телефона , а также нажатие кнопки с помощью селекторов, но ввод почты  рускими буквами
приоритет высокий ,предусловие вход на страницу професии и получение необходимых селекторов с помощью DevTools, ожидаймый результат :
вывод ошибки:ввод почты   ошибка введены символы не латиницы и не допустимые спецсимволы .
11. Ввод почты  некоректными спецсимволами, ввод коректых значений в поля  имени, телефона , а также нажатие кнопки с помощью селекторов, но ввод почты  некоректными спецсимволами
приоритет высокий ,предусловие вход на страницу професии и получение необходимых селекторов с помощью DevTools, ожидаймый результат :
вывод ошибки:ввод почты   ошибка введены символы не латиницы и не допустимые спецсимволы .
12. Ввод телефона не цифрами,ввод коректых значений в поля  имени, почты, а также нажатие кнопки с помощью селекторов, но ввод телефона  не цифрами
приоритет высокий ,предусловие вход на страницу професии и получение необходимых селекторов с помощью DevTools, ожидаймый результат :
вывод ошибки: ошибка ввода в поле телефона.
13.Ввод имени  смешаными рускими латинскими буквами и спецсимволами, ввод коректых значений в поля  почты и телефона , а также нажатие кнопки с помощью селекторов,
 но  ввод имени смешаными рускими латинскими буквами и спецсимволами
приоритет высокий ,предусловие вход на страницу професии и получение необходимых селекторов с помощью DevTools, ожидаймый результат :вывод ошибки:ввод имени возможен только рускими буквами.
14. Ввод почты  смешаными рускими латинскими буквами и спецсимволами, ввод коректых значений в поля  имени, телефона , а также нажатие кнопки с помощью селекторов,
 но ввод почты смешаными рускими латинскими буквами и спецсимволами
приоритет высокий ,предусловие вход на страницу професии и получение необходимых селекторов с помощью DevTools, ожидаймый результат :
вывод ошибки:ввод почты   ошибка введены символы не латиницы и не допустимые спецсимволы .
15. Ввод телефона  смешаными рускими латинскими буквами и спецсимволами, ввод коректых значений в имени, почты , а также нажатие кнопки с помощью селекторов,
 но ввод телефона смешаными рускими латинскими буквами и спецсимволами
приоритет высокий ,предусловие вход на страницу професии и получение необходимых селекторов с помощью DevTools, ожидаймый результат :
вывод ошибки:ошибка ввода в поле телефона.
16. Неверный выбор селектора , ввод коректых значений в поля имени, почты и телефона , а также нажатие кнопки но некоректный селектор в любом из пунктов
приоритет средний ,предусловие вход на страницу професии и получение необходимых селекторов с помощью DevTools, ожидаймый результат :тесты падают из за ошибки селектора.
17. Нагрузочное тестирование: одновременная генерация данных и запись на сайте в множестве процессов 
приоритет высокий ,предусловие вход на страницу професии и получение необходимых селекторов с помощью DevTools, ожидаймый результат : сайт успешно справился с нагрузкой

# Используемые инструменты:
* **Операционная система^**  Windows 10 Pro
* **IDE:** IntelliJ IDEA 2023.2.3 (Community Edition) 
* **Java:** OpenJDK 11
* **build system** gradle
* **Браузер** Google Chrom Версия 121.0.6167.160 (Официальная сборка), (64 бит)

использумые библиотеки:
1. junit для юнит тестирования и совмещения с allure
2. lombok для краткости и скорости написания, и уменьшения обьёма кода 
3. allure для понятных  и подробных но не слишком репортов
4. faker для генерации данных что бы в последущих версия тестов не было пестецидов
5. selenide для тестирования сайта с помощью селекторов

# Перечень необходимых разрешений, данных и доступов.
1. разрешение на автоматизированое тестирование
2. требования к тестированию
3. тестовый доступ
4. данные пользователей для тестирования
5. доступ к базе данных

# Перечень и описание возможных рисков при автоматизации.
1. из за нагрузочного тестирования может случиться падение сервера
2. сложность нахождения селекторов
3. при изменениях интрефейса сайта придется менять и автотесты.

# Перечень необходимых специалистов для автоматизации.
1. Автотестировщик

# Интервальная оценка с учётом рисков в часах:72+