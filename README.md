# Calculator-2-revised-

Я попробовала код из скриншота, но программа с ним все так же завершается с ошибкой. В решении отсутствует код, который ловит ArithmeticException, и программа просто умирает и всё. Она должна завершаться с ошибкой? Но в чем смысл? 

Я всё-таки написала код с блоком try и catch. Программа перестала умирать, но мне всё также непонятно, как можно эту задачу решить тернарным оператором, не меняя при этом делитель? 

Или я должа просто тернарным оператором написать 
y != 0 ? x / y : trow new ArithmeticException("Делить на ноль нельзя")?


Но ведь тогда пограмма завершится с ошибкой.


Может быть, я просто не понимаю, что от меня надо, но на эту задачу я потратила уже три недели и отстала от курса совсем. 
