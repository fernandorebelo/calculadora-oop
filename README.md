# Calculadora em OOP
Calculadora com operações de dois números desenvolvida no curso de Dev TI.

### Sistema
É solicitado ao usuário escolher qual operação ele vai querer realizar através de um menu.
Após selecionar a opção é solicitado escolher o primeiro e o segundo número.
O resultado é mostrado na tela.
### Por trás dos panos:
Foi criado uma classe chamada calculadora onde estão os métodos de adição, subtração, multiplicação e divisão.
Na classe principal está o código onde é mostrado um menu com quatro opções.
Após o usuário inserir um valor, este valor cai em uma estrutura switch.
Esta estrutura switch contém o código solicitando o valor ao usuário e armazenando em uma variável.
Esta variável é enviada aos métodos dentro da classe calculadora e a operação é realizada.
Este bloco é inserido em uma estrutura de repetição do-while que, ao final da operação, pergunta ao usuário se ele quer realizar outra operação.
