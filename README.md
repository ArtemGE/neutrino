# neutrino
Обработка данных симуляций эксперимента на Байкале. Строит осциллограммы событий, подсчитывает достоверность определения иерархии масс.


sigma(years) - программа для обработки данных для байкальской нейтринной обсерватории. Если говорить точнее, то обрабатываю я данные симуляции. БОльшую часть симуляции писал не я, поэтому её не посылаю, а обработку данных делаю уже я. Задача такая:
Даны два больших набора событий для двух разных вариантов иерархии масс нейтрино (неизвестный пока параметр этих частиц. Принимает два значения.). Событие - энергия нейтрино, его угол и тип (6 типов). Известна погрешность, с которой эти данные восстанавливаются как функция энергии и угла. Требуется определить зависимость точности определения иерархии масс от количества лет наблюдений. Для этого я строю осциллограммы - двумерные гистограммы с шириной бинов соответствующей погрешности в точке, а затем по критерию хи-квадрат отличаю один тип осциллограмм от другого. Последняя половина ноутбука - наполовину черновик, там всё в разработке.
