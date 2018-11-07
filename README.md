# Формальные языки и трансляции

Все написанный алгоритмы лежат в директории "library". В "main.cpp" реализована сама задача из практикума с использованием библиотеки. Подробное решение приводится снизу.

## Практикум 1
Заметим, что количество состояний в НКА по данному регулярному выражению O(N), тогда если поддерживать количество состояний перехода, то на каждом шаге будет не более, чем O(N) различных состояний. Тогда запустившись от всех префиксов по нашему НКА мы для каждой подстроки узнаем подходит она под регулярное выражение или нет. Тогда так как префиксов всего N, длина их N, а переход выполняется за O(N), то итоговая ассимптотика будет O(N^3)
