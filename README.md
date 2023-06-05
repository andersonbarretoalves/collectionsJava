# Collections em Java

**Atalhos para Intellij:**
http://www.basef.com.br/index.php/Atalhos_do_IntelliJ_Idea

## Trabalhando com Collections Java

---

* **Collection** é um objeto que agrupa múltiplos elementos (Variáveis primitivas ou
objetos) dentro de uma única unidade.
* Serve para armazenar e processar conjuntos de dados de forma eficiente.

### Composição da Collections
* **Interfaces:** É um contrato que quando assumido por uma classe deve ser implementado
* **Implementações ou Classes:** São as materializações, a codificação das interfaces.
* **Algoritmos:** É uma sequência lógica, finita e definida de instruções que devem ser seguidas para resolver um problema

---

### Lists

`java.util.list`

* Elementos duplicados e garante ordem de inserção.

### Set

`java.util.Set`

* Não permite elementos duplicados
* Não possui índice

### Map

* Elementos Unicos(key) para cada valor (value)

### Stream

#### Classe Anônima
A classe anônima em Java é uma classe que nao recebeu um nome e é tanto
declarado e instanciado em uma única instrução. Você deve considerar o uso
de uma classe anônima sempre que você precisa para criar uma classe que
será instanciado apenas uma vez.

#### Funcional Interface
Qualquer interface com um SAM (Single Abstract Method) é uma interface funcional e sua implementação pode ser tratada
como expressões lambda.
* Comparator
* Consumer
* Function
* Predicate

#### Lambda
Uma função Lambda é uma função sem declaração, isto é, não é necessário colocar um nome, um tipo de retorno e o
modificador de acesso. A ideia é que o método seja declarado no mesmo lugarem que será usado. As funções Lambda em 
java tem a sintaxe definida como (argumento) -> (corpo).

#### Reference Method
Method Reference é um novo recurso do java 8 que permite fazer referência a um método ou contrutor de uma classe
(de forma funcional) e assim indicar que ele deve ser utilizado num ponto específico  do código, deixando-o mais
simples. Para utilizá-lo, basta informar uma classe ou referência seguida do símbolo "::" e o nome do método sem os
parênteses no final.

### Stream API
A streams API traz uma nova opção para a manipulação de coleções em java seguindo os princípios da programação funcional.
Combinada comas expressões lambda, ela proporciona uma forma diferente de lidar com conjuntos de elementos, oferecendo
ao desenvovedor uma maneira simples e concisa de escrever códico que resulta em facilidade de manutenção e paralelização
sem efeitos indesejados em tempo de execução. 
