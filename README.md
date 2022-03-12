# netology_javacore_specialfiles_CSV-JSON
Converting files from CSV into JSON

## Задача: CSV - JSON парсер

[Ссылка](https://github.com/A-Sakhmina/netology_javacore_specialfiles_CSV-JSON/tree/master/src/main/java) на код
### Задание 
Произвести запись в файл `data.json` JSON объекта, полученного из CSV файла `data.csv`, который содержит в себе информацию об объектах `Employee`.
### Реализация
Метод `parseCSV()` возвращет список `Employee` сотрудников из считываемого CSV файла. Принимает **в качестве аргументов** _массив стринговых значений_ `String[] columnMapping`, 
который содержит в себе наименования столбцов(атрибуты класса `Employee`) исходных данных из исходного файла `data.csv`, 
и _стринговое значение `String fileName` с названием файла_ с исходными данными `data.csv`. Возвращает `List<Employee>`.

Метод `listToJson()` полученный список сотрудников преобразует в строчку в формате JSON. Принимает в качестве аргумента список сотрудников `List<Employee>`, возвращает `String`.

Метод `writeString()` записывает строчку в формате JSON в полученный в качестве аргумента JSON-файл `data.json`. Принимает в качестве аргумента название JSON-файла, 
в который будет осуществляться запись информации о сотрудниках.
