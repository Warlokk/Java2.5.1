# JaCoCo Coverage Counters
### **Использование счётчиков JaCoCo**


Плагин **JaCoCo (Java Code Coverage)** - инструмент, который показывает насколько используемый код покрыт автотестами.

Для расчета метрики, указанный плагин использует счётчики **(Coverage Counter)**.

В зависимости от целей расчёта, инструмент позволяет выбрать один из шести счётчиков:

- **Instructions (C0 Coverage)**
    
    Подсчитывает количество исполненного/пропущенного кода по отдельным инструкциям. 
    
    Доступен всегда, даже при отсутствии отладочной информации в классе.
- **Branches (C1 Coverage)**

    Подсчитывает количество в коде операторов **if/switch** и результат их исполнения. 
    
    Доступен всегда, даже при отсутствии отладочной информации в классе.
- **Cyclomatic Complexity**

    Подсчитывает сложность классов, пакетов и групп в каждом неабстрактном методе кода.

    Доступен всегда, даже при отсутствии отладочной информации в классе.
- **Lines**

    Если классы содержат отладочную информацию, счётчик может быть использован 
    
    для подсчета исполнения/пропуска кода по каждой строке.
- **Methods**

    Подсчитывает количество исполненных/пропущенных неабстрактных методов.

    Метод считается исполненным, если исполнена хотя бы одна инструкция из него.

- **Classes**

    Подсчитывает количество исполненных/пропущенных классов.
    
    Класс считается исполненным, если исполнен хотя бы один метод из него.

