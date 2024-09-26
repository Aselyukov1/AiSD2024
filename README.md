# Проект 2024: проект повторения кода из книги Скиены С. "Алгоритмы. Руководство по разработке"
## Минимальный набор инструментов для участия в проекте
### Установка git
1. Скачать и установить git c сайта: https://git-scm.com/
2. При установке лучше соглашаться со всеми предложенными опциям, за исключением:
первого окна, где лучше выбрать Override
### Установка компилятора MinGW:

1. Скачать и запустить https://sourceforge.net/projects/mingw/
2. Выбрать: mingw32-base, mingw32-gcc-g++
3. Добавить каталог bin установленного mingw к переменным среды Path своей операционной системы

### Репозиторий содержит следующие файлы:
1. m.c - пример простейшей программы на Си.
2. Makefile - пример файла для автоматической сборки этой программы при помощи mingw32-make с комментариями по командам. Помощь по mingw32-make можно найти по адресу: https://rus-linux.net/nlib.php?name=/MyLDP/algol/gnu_make/gnu_make_3-79_russian_manual.html
3. .gitignore - файл, в котором перечисленны рабочие файлы, которые стоит игнорировать при выполнении коммитов. 
### Правила именования листингов
L###_###.c (или .cpp), где первые три цифры ### номер главы и номер листинга без точки между ними, последние три цифры после символа подчеркивания - номер страницы на которой листинг начинается в книге. 


ПРОВЕРКА