# AiSD_LAB_4
С клавиатуры вводится два числа K и N. Квадратная матрица А(N,N), состоящая из 4-х равных по размерам подматриц, B,C,D,E заполняется случайным образом целыми числами в интервале [-10,10].
Формируется матрица F следующим образом: если в Е сумма чисел по периметру области 1 больше, чем количество нулей по периметру области 4, то поменять в С симметрично области 1 и 3 местами,
иначе В и Е поменять местами несимметрично. При этом матрица А не меняется. После чего вычисляется выражение:((К*AT)*А)-K*FT . Выводятся по мере формирования А, F и все матричные операции последовательно.
