# Calculadora Orientada a Objetos

Desenvolva uma calculadora única e especial, levando em consideração que você, meu caro aluno, pode ser tentado a copiar uma calculadora da internet, mesmo sabendo que não faria isso com seu estimado professor. Proponho uma abordagem diferente para criar uma calculadora!

### Requisitos:

- **Entidade Usuário (User):** Armazene os dados de registro do usuário, como nome, profissão, idade, etc. Utilize orientação a objetos para encapsular as responsabilidades dessa entidade. Demonstre sua habilidade em organizar código, separando as responsabilidades de forma eficiente.

- **Calculadora com Orientação a Objetos:** Utilize a orientação a objetos para modificar o código existente da calculadora. Organize o código de forma que seja visualmente fácil de compreender e que represente uma boa prática de clean code. 

### Dicas:

1. Na chamada main, instancie o objeto calculadora e utilize o menor número possível de linhas.

2. Experimente criar um objeto Usuario (User) e explore métodos públicos e privados dentro da classe calculadora. Defina estrategicamente quais métodos devem ser públicos e quais devem ser privados.

3. Se julgar necessário, crie uma classe `CalcularUtils` para realizar as operações. Separe as operações em métodos chamados pela sua classe `CalcularUtils` dentro da `CalculadoraService`. Use métodos estáticos para Utils.

4. Torne a interface o mais esteticamente agradável possível. Antecipe-se às possíveis formas de erro por parte dos usuários e trate situações como a divisão por zero.

5. Aproveite a oportunidade para utilizar instanciamento nos construtores para inicializar os parâmetros necessários no início da instância em memória.

6. Utilize formas de operadores de alto nível em Java para diferenciar sua implementação.
