# Terminal_H1, 17.04.23
The main command for terminal:
________________________

:small_blue_diamond: Вывести текущую рабочую директорию - ***$ pwd***

:small_blue_diamond: Создать папку - ***$ mkdir folder***

:small_blue_diamond: Зайти в папку - __$ cd folder__

:small_blue_diamond: Создать 3 папки - ***$ mkdir test1 test2 test3***

:small_blue_diamond: Зайти в любую папку - ****$ cd test1***

:small_blue_diamond: Создать 5 файлов (3 txt, 2 json) - ***$ touch {1..3}.txt {1..5}.json***

:small_blue_diamond: Создать 3 папки -  ***$ mkdir folder_{1..3}***

:small_blue_diamond: Вывести список содержимого папки - ***$ ls -la***

:small_blue_diamond: Открыть любой txt файл - ***$ vim 1.txt***

:small_blue_diamond: Написать туда что-нибудь, любой текст.- ***i - Hello world***

:small_blue_diamond: Сохранить и выйти - ***esc***
                     - ***:wq;***

:small_blue_diamond: Выйти из папки на уровень выше - ***$ cd ..***

:small_blue_diamond: Переместить любые 2 файла, которые вы создали, в любую другую папку - ***$ mv test1/1.txt test2/1.txt***

:small_blue_diamond: Скопировать любые 2 файла, которые вы создали, в любую другую папку - ***$ cp test2/qa1.txt  test1/qa1.txt***

:small_blue_diamond: Найти файл по имени - __$ find . -name '1*'__

:small_blue_diamond: Найти папку - ***$ find -type d -name folder_1*** 

:small_blue_diamond: Просмотреть содержимое в реальном времени (команда grep) изучите как она работает - __tail -f qa1.txt | grep ".*"__

:small_blue_diamond: Вывести несколько первых строк из текстового файла - ***$ head -n 5 1.txt***

:small_blue_diamond: Вывести несколько последних строк из текстового файла - ***$ tail -3 1.txt***

:small_blue_diamond: Просмотреть содержимое длинного файла (команда less) изучите как она работает -  ***$ less 1.txt***

:small_blue_diamond: Вывести дату и время - ***$ date***
_______
# Задание *

1) Отправить http запрос на [сервер](http://162.55.220.72:5005/terminal-hw-request) - 

      curl "http://162.55.220.72:5005/terminal-hw-request"

    $ curl "http://162.55.220.72:5005/get_method?"name"="Kris"&"age"=29"
 
2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13 - 

   :small_orange_diamond: создаем файл скрипта с командами в расширении sh
   
   :small_orange_diamond: запускаем скрипт sh test.sh
   
