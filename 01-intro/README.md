# Домашнее задание

Дописать решение для случая неквадратного уравнения (a == 0).

## Как проверять

1.  Изменить числа в `main` и запустить программу

        $ stack runhaskell square.hs

2.  Загрузить файл в `stack ghci` и применить функцию

        > :load square.hs
        > :reload
        > solveSquareEquation 1 (-2) 1
