# SpotBugs
SpotBugs - это программа, которая использует статический анализ для поиска ошибок в коде Java. SpotBugs проверяет более 400 шаблонов ошибок.
# Задание 2*. Пусть плагин ищет баги (НЕобязательная задача)
<code>[SpotBugs](https://spotbugs.github.io/) </code> и <code>[Maven Plugin](https://spotbugs.readthedocs.io/en/latest/maven.html) </code> для него предоставляют возможность производить статический анализ (анализ кода без его запуска) для выявления наиболее часто встречающихся багов.

Список багов, которые ищет SpotBugs: https://spotbugs.readthedocs.io/en/latest/bugDescriptions.html

Ваша задача:

1. Подключить плагин к вашему проекту (возьмите проект с первой задачи, либо создайте новый на его базе)
2. Настроить goal check в фазу verify
3. Удостовериться, что код проходит проверки SpotBugs (если не проходит, то пофиксить)
4. Сделать push в GitHub и удостовериться, что сборка проходит.

Итого: отправьте на проверку ссылку гитхаб-репозиторий с вашим проектом.
