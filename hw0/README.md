Данные:

1) ua_reactions.csv - логи кликов/показов рекламы с разных user agents 
(1 - показ рекламы который закончился кликом / 0 - показ без клика)
2) excluded.txt - список user agents которые надо исключить из расчета


Задачи:

1) Взять все UA для которых было больше 5 показов рекламы посчитать CTR (clicks / shows) для каждого UA
и вывести топ 5.

2) Вывести все UA на которых приходится 50% рекламных показов.


P.S - все расчеты надо делать с иключением UA из файла excluded.txt


Технологии:

Spark / Scala 