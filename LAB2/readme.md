Два проекта (процессы) хранить в одном Solution (Решении)!
В Solution (Решениии) настроить, что бы .exe файлы лежали в одном Debug!

Процесс Parent:
 - Ввести размер массива, ввести элементы массива
 - Формирует командную строку, которая содержит информацию об размерности массива, элементах и т.д.
 - Для консоли дочернего процесса установить высоту буфера для Child
 - Запускает дочерний процесс Child, которому через командную строку передается информация об размерности массива, элементах

Процесс Child:
 - Сортировка методом “пузырька”. Полученный массив вывести.
