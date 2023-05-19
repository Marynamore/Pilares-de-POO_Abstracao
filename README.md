# Os-quatro-pilares-de-POO
Continuamos com a Programação Orientada a Objeto (POO), agora informando os 4 pilares desta programação

A programação orientada a objetos pode ser definida por quatro pilares principais, sendo eles herança, abstração, encapsulamento e polimorfismo.

* **Herança:** Reaproveitar o código, para trazer características de um objeto pai para um filho
* **Abstração:** Reduzir a exposição dos objetos escondendo os detalhes da implementação e expondo somente o necessário

Abstração é como separar e simplificar um sistema de objetos em partes importantes. Em vez de olhar para o sistema como um todo, focamos nas partes principais e ignoramos os detalhes por enquanto. Isso nos ajuda a construir partes bem-definidas que podem ser reutilizadas posteriormente.

Quando desenvolvemos um sistema orientado a objetos, é importante aplicar a abstração, ou seja, separar o sistema em módulos.

Existem as classes abstratas, que são modelos comuns utilizados como base para outras classes, mas não podem ser usadas para criar objetos diretamente. Elas são como um molde que as classes filhas devem seguir.

Também existem os métodos abstratos, que são definidos nas classes abstratas apenas com a assinatura, sem uma implementação específica. Esses métodos devem ser obrigatoriamente implementados pelas classes filhas.

Um exemplo seria a classe "Animal" que é abstrata e serve como base para outras classes, como "Cachorro" e "Gato". A classe "Animal" define características comuns a todos os animais, como nome e idade. Porém, ela não pode ser usada para criar um objeto diretamente, apenas suas subclasses podem ser instanciadas.

Em resumo, a abstração nos permite separar um sistema em partes importantes e criar modelos comuns que são seguidos pelas subclasses, garantindo uma estrutura organizada e reutilizável.
