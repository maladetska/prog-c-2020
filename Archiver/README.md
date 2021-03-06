# Архиватор
Задача: Разработка программы по архивированию и распаковке нескольких файлов в один архив.
## Архиватор должен:
* Уметь архивировать несколько (один и более) указаных файлов в архив в расширением __*.arc__
* Уметь распаковывать файловых архив, извлекая изначально запаковонные файлы
* Предоставлять список файлов упакованных в архиве
* Сжимать и разжимать данные при архивировании  с помощью алгоритма Хаффмана
## Архиватор выполнен в виде консольного приложения, принимающего в качестве аргументов следущие параметры:
* __--file FILE__ - Имя файлового архива с которым будет работать архиватор
* __--create {FILE1 FILE2 ... FILEN}__ - Команда для создание файлового архива 
* __--extract__ - Команда для извлечения из файлового архива файлов
* __--list__ - Команда для предоставления списка файлов, хранящихся в архиве
## Примеры использования:
* __arc --file  data.arc --create a.txt b.bin c.bmp
* __arc --file  data.arc --extract
* __arc --file  data.arc --list
