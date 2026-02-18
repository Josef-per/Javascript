# Variaveis

Variaveis servem para guardar informações em um espaço de memória, Js não é fortimente tipada ou seja, eu preciso colocar somente o nome da variavel e em seguinda atribuir a ele o valor que eu quero.

Para atribuir algum algum valor a uma váriavel utlizamos o =, esse sinal simples indica atribuição, assim o valor da variavel vai ser alterado de acordo com o que estiver após ele.

## > Declarando variaveis

Para declarar variaveis é fácil, temos que utilizar a palvara chave de criação, onde temos 3 formas diferentes de criar, todas elas são validas, contudo cada uma tem suas vantagens e usos diferentes.

- **let** - Armazena um valor que pode ser alterado no futuro, sendo criada no escopo local de trabalho da variavel.
- **const** - Armazena um valor que nunca pode ser alterado por, isso const, de constante, sendo criada no escopo local de trabalho da variavel. Sua alteração só pode ser feita caso sendo utilizada na criação de algum array.
- **var** - metodo antigo de utilizar e declarar variaveis, encontrado normalmente em códigos antigos, sendo criada como uma variavel global, podendo ser encontrada em qualquer lugar da aplicação.

``
  let minhaVariavel = "Opá mundo bom"
``

Esse exemplo mostra como cria uma variavel, para cada forma como, const e let o formato é o mesmo, da mesma forma.

## Nomeando as suas variaveis

O nome das variaveis é muito importante isso define um programador novo a um experiente, sempre use nomes detalhados sobre o tipo de dado que a variavel vai estar utilizando, não escreva algo que não de pra entender ou coisa do tipo.

Nem sempre reutilizar uma variavel vai ser a coisa certa a se fazer, criar uma nova variavel pode ser a melhor escolha em termos de organização e manutenção do código, principamente no caso que esteja trabalhando com outras pessoas.

Em Js sempre se utiliza o metodo Camel, ou seja as variaveis vão ser chamadas dessa forma novoCliente, clienteAtual, se utiliza dessa forma quando o valor da variavel for 'descoberto', na execução do código. As únicas vezes que não vamos seguir esse estilo vai ser quando temos um valor que não vai mudar um const, que vai iniciar com aquele valor desde o inicio, ele não vai precisar de uma conta ou de outra coisa, ele sempre teve aquele valor, sendo muito comum para armazenar código de cores para paginação.

---

# Fontes

[Base teorica](https://javascript.info/)
