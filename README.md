# Класс для создания документа с цифровой подписью

## Согласно техническому заданию, необходимо реализовать на языке Java класс для работы с API Честного знака.


**Класс должен соответствовать следующим требованиям:**

- Класс должен быть thread-safe и поддерживать ограничение на количество запросов к API. Ограничение указывается в конструкторе в виде количества запросов в определенный интервал времени.
- При превышении лимита запрос вызов должен блокироваться, чтобы не превысить максимальное количество запросов к API и продолжить выполнение, без выбрасывания исключения, когда ограничение на количество вызов API не будет превышено в результате этого вызова. В любой ситуации превышать лимит на количество запросов запрещено для метода.
- Реализовать нужно единственный метод – cоздание документа для ввода в оборот товара, произведенного в РФ. Документ и подпись должны передаваться в метод в виде Java объекта и строки соответственно.
- Реализация должна быть максимально удобной для последующего расширения функционала.
- Решение должно быть оформлено в виде одного файла CrptApi.java. Все дополнительные классы, которые используются должны быть внутренними.

  ### Инструменты разработки:
```
* IntelliJ IDEA
* Java 17
* org.springframework.boot
* org.junit.jupiter
* org.projectlombok
* Сборка с помощью org.apache.maven

