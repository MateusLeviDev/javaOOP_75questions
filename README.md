## `Java Questions`

- 01. What is inheritance? `(herança)`
> É a capacidade de uma subclasse herdar atributos e métodos, ou seja, herdar "características" de uma superclasse. Isso ajuda a evitar a duplicação de código e a criar hierarquias de classes com diferentes níveis de abstração.
- 02. What are the different types of inheritance?
> Herança simples, podendo ser múltipla como em C++. Existindo também a hierárquica e híbrida. 
- 03. What are the limitations of inheritance?
> A herança cria uma relação rígida entre as classes, onde as subclasses herdam todos os atributos e métodos da superclasse, mesmo que não precisem de todos eles. Isso pode tornar o código menos flexível e mais difícil de manter. A herança pode levar a um alto grau de acoplamento entre as classes, o que significa que uma mudança em uma classe pode afetar várias outras classes na hierarquia de herança. A herança múltipla pode ser confusa e pode levar a problemas de ambiguidade quando duas ou mais superclasses têm métodos ou atributos com o mesmo nome.
- 04. What is a superclass?
> Uma superclasse pode ser definida como uma classe mãe que se estende e gerando a herança para com outras subclasses. Ao meu ver uma main classe, gênerica, talvez? How knows. Mas na verdade, sim, visto que os métodos serão melhor trabalhados pelas subclasses.
- 05. What is a subclass?
> Subclasses herdam os atributos e métodos dessas superclasses, podendo personalizá-los ou adicionar novos métodos e atributos específicos de acordo com sua necessidade, regra de negócio e afins. 
- 06. What is polymorphism? `(polimorfismo ou poliformismo? rs)`
> Poliformismo (a forma certa, quando se retrata sobre programação. Em contrapartida, polimorfismo, maneira correta de se escrever a palavra, é referente a um ramo da ciência) em suma, é a capacidade de uma variável gênerica herdar métodos relacionados a um objeto, sem a necessidade de relação entre si. Por exemplo, consigo explicar com os seguintes dados: 
Account x = new Account(1020, "Alex", 1000.0);
Account y = new SavingsAccount(1023, "Maria", 1000.0, 0.01); 

x.withdraw(50.0);
y.withdraw(50.0)
- 07. What is method overloading?
- 08. What is method overriding?
- 09. What is encapsulation?
- 10. What are ‘access specifiers’?
- 11. What is the difference between public, private and protected access modifiers?
- 12. Can you create an instance of an abstract class?
- 13. What is an interface?
- 14. Differentiate between an abstract class and an interface?
- 15. What is a try/ catch block?
- 16. Can you override a static method in Java?
- 17. O que é Programação Orientada a Objetos (POO) e quais são seus princípios básicos?
- 18. Quais são as diferenças entre POO e programação procedural?
- 19. O que são classes e objetos em POO?
- 20. O que é encapsulamento em POO e qual é sua importância?
- 21. O que são métodos em POO e como eles são usados?
- 22. O que são atributos em POO e como eles são usados?
- 23. O que é herança em POO e como ela é implementada?
- 24. Quais são as vantagens da herança em POO?
- 25. O que é polimorfismo em POO e como ele é implementado?
- 26. O que é sobrescrita de método e quando ela é usada em POO?
- 27. O que é sobrecarga de método e quando ela é usada em POO?
- 28. O que é abstração em POO e como ela é implementada?
- 29. Qual é a diferença entre uma classe abstrata e uma interface em POO?
- 30. O que é composição em POO e como ela é implementada?
- 31. O que é agregação em POO e como ela é implementada?
- 32. O que é associação em POO e como ela é implementada?
- 33. Qual é a diferença entre composição, agregação e associação em POO?
- 34. O que é um construtor em POO e como ele é usado?
- 35. O que é um destrutor em POO e como ele é usado?
- 36. O que são exceções em POO e como elas são tratadas?
- 37. Qual é a relação entre herança e polimorfismo em POO?
- 38. Como a herança é usada para implementar o polimorfismo em POO?
- 39. Quais são os tipos de herança em POO e como eles afetam o polimorfismo?
- 40. O que é sobrescrita de método em POO e como ela afeta o polimorfismo?
- 41. O que é sobrecarga de método em POO e como ela afeta o polimorfismo?
- 42. O que é polimorfismo de sobrecarga em POO e como ele é implementado?
- 43. O que é polimorfismo de sobrescrita em POO e como ele é implementado?
- 44. O que é polimorfismo ad hoc em POO e como ele é implementado?
- 45. Como o polimorfismo pode ser usado para melhorar a reutilização de código em POO?
- 46. Quais são as vantagens e desvantagens do uso de herança e polimorfismo em POO?
- 47. What is the abstraction in Java?
- 48. Is Java a pure object-oriented language? if not why?
- 49. What is the difference between a class and an instance?
- 50. What is the difference between Decorator, Proxy, and Adapter patterns in Java?
- 51. Can we overload or override the main method in Java?
- 52. Can we make a class abstract without an abstract method?
- 53. Can we make a class both final and abstract at the same time?
- 54. What is the default method of Java 8?
- 55. O que é encapsulamento em Java e como ele é implementado? (Encapsulamento e Modificadores de Acesso)
- 56. Qual a diferença entre uma classe abstrata e uma interface em Java? (Abstração e Interface)
- 57. Como as classes internas funcionam em Java e em quais situações elas podem ser úteis? (Classes Internas)
- 58. Como é possível implementar herança múltipla em Java? (Herança Múltipla)
- 59. O que são classes finais em Java e por que elas podem ser úteis? (Classes Finais)
- 60. O que é polimorfismo em Java e como ele pode ser aplicado? (Polimorfismo)
- 61. Como funciona a sobrecarga de métodos em Java e em que situações ela pode ser útil? (Sobrecarga de Métodos)
- 62. Como funcionam as exceções em Java e como elas podem ser tratadas? (Tratamento de Exceções)
- 63. Como é possível criar e utilizar anotações em Java? (Anotações)
- 64. Qual a diferença entre composição e herança em Java? (Composição e Herança)
- 65. Como funciona a serialização de objetos em Java e quais são suas limitações? (Serialização de Objetos)
- 66. Como as classes abertas podem ser úteis em Java? (Classes Abertas)
- 67. Como as expressões lambda podem ser utilizadas em Java? (Expressões Lambda)
- 68. Como é possível utilizar os streams em Java e quais são suas vantagens? (Streams)
- 69. O que é o padrão DAO (Data Access Object) e como ele pode ser utilizado em Java? (Padrão DAO (Data Access Object))
- 70. Qual a diferença entre uma classe estática e uma classe normal em Java? (Classes Estáticas)
- 71. Como funcionam os genéricos em Java e quais são suas limitações? (Genéricos)
- 72. Como é possível implementar a segurança em Java? (Segurança)
- 73. Como funcionam os listeners em Java e como eles podem ser utilizados? (Listeners)
- 74. omo funciona a injeção de dependência em Java e quais são suas vantagens? (Injeção de Dependência)
- 75. Como é possível utilizar a reflexão em Java e quais são suas limitações? (Reflexão.)























