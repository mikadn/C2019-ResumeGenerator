# Тестовое задание для курса по java
##  Общее задание:
Приложение должно создавать HTML страницу по заданному шаблону, на основе .properties файла.

##  Описание задания:
Имеется входной файл с расширением .properties. Property-файл содержит информацию о Вас в формате “ключ”-“значение”. Вам необходимо разработать java приложение, создающее HTML страницу – резюме содержащее данные о Вас. HTML страница должна корректно открываться в любом современном интернет-браузере (chrome, firefox, microsoft edge и др.)
### Шаблон HTML страницы:
отдельным файлом

### Пример входного файла с расширением .properties:
FIO=N N N
DOB=20.06.1994 г.
email=N@gmail.com
skype=N
avatar=https://pp.vk.me/c604420/v604420985/31f0f/_MS61ivGiMM.jpg
target=Получение работы на должности java-стажер.

##  Обязательные требования
1. Программа должна быть написана на языке Java 8;
2. В программе необходимо предусмотреть обработку нештатных ситуаций (Например, выбранный файл заблокирован, или имеет неправильную структуру и т.д.);
3. Программа должна обеспечивать корректную обработку исключительных ситуаций (exceptions);
4. Приложение должно извлекать данные из .properties - файла;
5. Данные внутри .properties файла должны быть как на кириллице так и на латинице;
6. При обработке .properties файла необходимо пользоваться стандартными средствами, включенными в Java Core;
7. .properties файл должен содержать информацию формата “ключ” - “значение”;
8. Сгенерированный HTML файл должен быть загружен любым современным браузером за время не более 5-10 секунд;

## Требования к постановке (список файлов для проверки)
1. Все файлы поставляются в виде одного архива минимального размера
2. Архив должен содержать:
a. Папку с исходным кодом программы, с одним .properties файлом, включенным в него 
b. Сгенерированную при помощи кода html страничку
3. Readme-файл содержащий:
a. Руководство по запуску Вашего приложения
b. Руководство пользователя

## Требования к качеству продукта
1. Соблюдение java code conventions
2. Исполняемый код должен корректно выполнять вышеописанный функционал

## Дополнительные требования
1. Приложение должно быть разбито на слои (см. data access layer);
2. Работа со строками должна быть с использованием StringBuilder;
3. Приложение должно учитывать, что по одному “ключу” может быть несколько значений; (например: цель=“Получать мандаринки”, “получать еще и зарплату!” 
4. Приложение должно быть выполнено с использованием bootstrap 3.
