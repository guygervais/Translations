Арифметическая прогрессия - это последовательность чисел, обладающая особым свойством - каждое следующее значение больше
предыдущего на фиксированную величину (назовем её "шагом" прогрессии).

Т.е. разность между `(K+1)`-ым и `K`-ым значениями одинакова для любых `K`.

Раз так, арифметическая прогрессия полностью определяется начальным значением (`A`) и шагом (`B`).
Первые несколько значений можно выразить как

    A,  (A + B),  (A + 2*B),  (A + 3*B), ...

Наша задача - вычислить сумму первых нескольких членов арифметической прогрессии. 
[Статья в википедии](http://en.wikipedia.org/wiki/Arithmetic_progression) - или какой-нибудь другой источник могут быть
весьма полезны если вы сталкиваетесь с такими последовательностями впервые.

**Входные данные:** первая строка содержит число тестов.  
Остальные строки содержат тесты, по три значения в каждом: `A B N` где `A` это начальное значение последовательности,
`B` её шаг, а `N` количество первых членов которые нужно просуммировать.  
**Ответ** должен содержать результат (сумму первых членов) для каждой тестовой последовательности, через пробел.

Пример:

    входные данные:
    2
    5 2 3
    3 0 10
    
    ответ:
    21 30
