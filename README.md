# Домашнее задание 6
## Условие 
Написать подпрограмму, осуществляющую копирование строки символов аналогично функции strncpy языка программирования C. Протестировать функцию на различных комбинациях данных. Ознакомиться с функцией можно в системе справки по библиотеке языка C, которая имеется в различных источниках информации. Исходные данные для тестирования задавать как при вводе с консоли, так и с использованием строк символов в разрабатываемой программе (по аналогии с программами, рассмотренными на семинаре). Подпрограмму вынести в отдельный файл.
+ 
Реализован макрос в дополнение к подпрограмме
## Решение
[Основная программа с тестовыми значениями](HW6/main.asm)

[Макрос](HW6/macro.asm)

Тестовые значения: 
<table>
    <tr>
        <th>input</th>
        <th>output</th>
    </tr>
    <tr>
        <td>\0</td>
        <td>\0</td>
    </tr>
    <tr>
        <td>Hello World!\0</td>
        <td>Hello World!\0</td>
    </tr>
    <tr>
        <td>Hello\0 World!</td>
        <td>Hello\0</td>
    </tr>
</table>
