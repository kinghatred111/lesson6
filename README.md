Мальцев Александр

Номер группы: 6378


В классе Main производится создание экземпляров классов операций (таких как Addition, Subtraction, Multiplication, Division) и объекта конвертера (BinaryConverter). Эти объекты передаются в конструктор класса Calculator. Такой подход соответствует принципу единственной ответственности (SRP), так как класс Main отвечает исключительно за создание объектов и запуск программы.


Класс Addition реализует интерфейс Operation и предоставляет функционал для выполнения сложения. Это соответствует принципу единственной ответственности (SRP), так как класс занимается только операцией сложения.


Аналогично, класс Subtraction реализует интерфейс Operation и выполняет вычитание, следуя принципу единственной ответственности, так как он отвечает исключительно за вычитание.


Класс Multiplication также реализует интерфейс Operation и занимается выполнением умножения, что соответствует принципу единственной ответственности, так как он сосредоточен только на умножении.


Класс Division, реализующий интерфейс Operation, выполняет деление, что также соответствует принципу единственной ответственности, так как он отвечает только за деление.


Интерфейс Converter определяет методы для преобразования чисел между десятичной и двоичной системами.


Класс BinaryConverter реализует интерфейс Converter и предоставляет методы для преобразования чисел между десятичной и двоичной системами. Он поддерживает принцип единственной ответственности (SRP), фокусируясь исключительно на преобразовании чисел.


Класс Calculator представляет собой калькулятор, который может выполнять различные операции и преобразования чисел. Он следует принципу инверсии зависимостей (DIP), внедряя зависимости в виде объектов операций и конвертера через свой конструктор.
