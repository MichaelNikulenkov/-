# -
Решение задачи Коши для ОДУ первого порядка с помощью искусственных нейронных сетей

На сегодняшний день разработано множество методов решения дифференциальных уравнений. Некоторые из них дают ответ в виде решения в выбранной группе точек, 
другие используют базисные функции для представления решения. Другой подход к решению дифференциальных уравнений основан на возможности аппроксимировать функции с 
помощью нейронных сетей прямого распространения.

Задачи:
Реализовать алгоритм решения задачи Коши для ОДУ первого порядка с помощью искусственных нейронных сетей. Продемонстрировать работу алгоритма, сравнить результат 
с численными методами решения других классов. Выделить достоинства и недостатки метода.

Результаты:
Показано, что выбор начального значения
результирующего нейрона и выбор алгоритма минимизации позволяет улучшить решение. Приведено сравнение с методами Эйлера и Рунге-Кутты 4-го порядка. Так
же, установлено, что рассматриваемый метод требует большего времени выполнения,
а также, что погрешность нейронной сети не зависит от выбора сетки, на которой
ищется решение. Минимальная полученная относительная погрешность: 0.01123 для
первого теста; 0.20659 для второго теста; 0.14362 для третьего теста.
К достоинствам рассмотренного метода относится то, что погрешность нейронной
сети не зависит от выбора сетки, на которой ищется решение. К недостаткам относится сложность реализации и большее время, необходимое для получения решения
(в сравнении с методом Рунге-Кутты 4-го порядка и методом Эйлера).

Полный текст работы: https://github.com/MichaelNikulenkov/Neural-Cauchy-problem/blob/master/%D0%B4%D0%B8%D1%84%D1%84.%20%D1%83%D1%80-%D1%8F%20%D0%98%D0%9D%D0%A1.pdf

Код:
https://github.com/MichaelNikulenkov/Neural-Cauchy-problem/tree/master/NeuralDiffEqGradDescent/NeuralDiffEq
