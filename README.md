# Задание 2*. Пусть плагин ищет баги 
[SpotBugs](https://spotbugs.github.io/) и [Maven Plugin](https://spotbugs.readthedocs.io/en/latest/maven.html) для него предоставляют возможность производить статический анализ, то есть анализ кода без его запуска, для выявления наиболее часто встречающихся багов.

[Список багов, которые ищет SpotBugs.](https://spotbugs.readthedocs.io/en/latest/bugDescriptions.html)

Ваша задача
 
1. Подключить плагин к вашему проекту. Возьмите проект из первой задачи или создайте новый на его базе.
2. Настроить goal check в фазу verify.
3. Удостовериться, что код проходит проверки SpotBugs, если не проходит, то пофиксить.
4. Сделать push в GitHub и удостовериться, что сборка проходит.