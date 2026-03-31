# manual_javascript

1. introdução:

O que é JavaScript?
linguagem de programação usada para criar interatividade em páginas da web, permitindo que elas façam mais do que apenas mostrar conteúdo estático.

Para que JavaScript serve em páginas web?
Serve para tornar o site dinâmico, permitindo ações como cliques, animações, validação de formulários e atualização de conteúdo sem recarregar a página.

Como JavaScript se relaciona com HTML e CSS?
O HTML cria a estrutura da página, o CSS define o estilo e o JavaScript controla o comportamento e as interações.

2. FORMAS DE USO NO HTML

JavaScript escrito dentro da própria página HTML:
Pode ser usado dentro do próprio arquivo HTML ou ligado a um arquivo externo que contém o código JavaScript.

Qual a diferença entre script dentro do HTML e script em arquivo separado?
O script dentro do HTML fica no mesmo arquivo da página, enquanto o script externo fica em um arquivo separado, facilitando organização e reutilização.

Exemplo do JavaScript em HTML no arquivo "01_script_no_html.html", dentro da pasta 01_script_no_html.
O exemplo do arquivo externo está em "02_script_externo.js", mas está conectado a um arquivo HTML nomeado de "02_script_externo.html", dentro da pasta 02_script_externo.


3. VARIÁVEIS, TIPOS E ESCOPO

O que é uma variável?
Variáveis são criadas para armazenar dados como números e textos.

Como declarar variáveis em JavaScript?
Podem ser declaradas usando as palavras-chave var, let ou const, seguidas do nome da variável e, opcionalmente, um valor.

Qual a diferença entre var, let e const?
var é a forma antiga, let é mais moderna e permite alterar o valor, e const é usada para valores que não podem ser modificados.

Quando cada uma pode ser usada?
let deve ser usada quando o valor da variável pode mudar ao longo do programa.
const deve ser usada quando o valor não deva mudar.
var é uma forma antiga e geralmente não é recomendada atualmente.

O que é escopo global?
É quando uma variável é declarada fora de qualquer função ou bloco, podendo ser acessada de qualquer parte do código.

O que é escopo de função?
Ocorre quando uma variável é declarada dentro de uma função e só pode ser utilizada dentro dessa função.


O que é escopo de bloco?
Ocorre quando uma variável é declarada dentro de um bloco de código (como if, for, while), sendo acessível apenas dentro daquele bloco.

O exemplo desse topico pode ser encontrado no arquivo "03_variaveis_tipos_escopo.html", dentro da pasta 03_variaveis_tipos_escopo.

4. OPERADORES, COMPARAÇÕES E LÓGICA

Operadores aritméticos principais:
 Adição (+) -> soma valores
 Subtração (-) -> diminui valores
 Multiplicação (*) -> multiplica valores
 Divisão (/) -> divide valores
 Resto (%) -> retorna o resto da divisão
 Incremento (++) -> aumenta 1
 Decremento (--) -> diminui 1

Operadores relacionais principais
São usados para comparar valores. O resultado sempre será verdadeiro (true) ou falso (false).

 Igual (==) -> verifica se os valores são iguais (sem considerar tipo)
 Estritamente igual (===) -> verifica valor e tipo
 Diferente (!=) -> verifica se são diferentes
 Estritamente diferente (!==) -> verifica valor e tipo diferentes
 Maior que (>)         Menor que (<)
 Maior ou igual (>=)   Menor ou igual (<=)

Operadores lógicos principais
São usados para combinar ou inverter condições.

 E lógico (&&) -> verdadeiro se todas as condições forem verdadeiras
 OU lógico (||) -> verdadeiro se pelo menos uma condição for verdadeira
 NÃO lógico (!) -> inverte o valor (true vira false e vice-versa)

Qual a diferença entre == e ===?
 == compara apenas o valor e o converte, enquanto === compara valor e tipo ao mesmo tempo apenas vendo se um é igual ao outro, se não for automaticamente é falso, o que o torna bem mais seguro, por não tranformar valores diferentes em iguais.

Exemplo: Quando usamos ==, estamos comparando apenas o valor, como verificar se o número 5 é igual ao valor '5'. Já o === compara se o número 5 é igual ao valor '5' e também se os tipos são iguais, ou seja, número e texto. Esse exemplo pode ser encontrado no arquivo "04_operadores_e_comparacoes.html".

Qual a diferença entre != e !==?
 != verifica se os valores são diferentes, enquanto !== verifica se são diferentes em valor e tipo.

Exemplo: Aqui se aplica a mesma regra do == ou ===, para != o tipo não interfere e para !== o tipo interfere. Esse exemplo pode ser encontrado no arquivo "04_operadores_e_comparacoes.html", dentro da pasta 04_operadores_e_comparacoes.

5. ESTRUTURAS CONDICIONAIS: 

“If”:
São estruturas utilizadas para apenas uma condição sendo ela verdadeira ou falsa.
Exemplo no arquivo "condicionais.html": Se o estoque estiver com mais de 100 itens deve aparecer na tela “Estoque completo”.

“If e Else”: 

São estruturas utilizadas para executar um bloco de código caso a condição seja verdadeira ou falsa. Na estrutura utiliza-se “if” e “else”. O “if” condiciona que se tal condição se aplicar, o comando será executado. No “else”, se a condição anterior não se aplicar, outro comando irá ser executado. 

Exemplo no arquivo "condicionais.html": O aluno será aprovado se sua nota for igual ou superior a 7, caso ele seja aprovado deve aparecer na tela a mensagem “Parabéns você foi aprovado”. Senão deve exibir a mensagem “Você foi reprovado”, dentro da pasta 05_condicionais.

Switch: 
Em situações que temos mais de um caso para escolher. Dependendo do caso escolhido, situações diferentes irão ser executadas.

Exemplo no arquivo "condicionais.html": Uma família vai receber um auxílio proporcional à quantidade de dependentes em sua casa. 1-2 membros = 100 reais. 3-4 = 200 reais. Mais de 4: 300 reais. Caso não tenha dependentes não recebe, dentro da pasta 05_condicionais.


6. ESTRUTURAS DE REPETIÇÃO:

FOR: O for é uma estrutura de repetição usada quando você já sabe quantas vezes quer repetir uma ação. Ele funciona com três partes: início, condição e incremento.

WHILE:  É uma estrutura de repetição usada quando você não sabe exatamente quantas vezes o código vai repetir, pois depende de uma condição.

O exemplo está no arquivo "06_repeticao.html", dentro da pasta 06_repeticao. E para ambos os casos utilizamos um contador que aumenta o valor de um em um.


7. FUNÇÕES:

O que é uma função?

É um bloco de código que você pode reusar, serve para fazer uma tarefa específica e pode receber informações (parâmetros) e devolver um resultado (retorno).


Como declarar uma função?

Para criar uma função, usamos a palavra function, seguida do nome da função e parênteses (). Dentro das chaves { } colocamos o código que queremos que a função execute.


Como chamar uma função?

Depois de declarar a função, você chama ela usando o nome seguido de parênteses.


Função com parâmetro:

Parâmetros são informações que você passa para a função para ela usar.


Função com retorno:

Uma função pode retornar um valor usando a palavra return. Isso permite guardar ou usar o resultado em outro lugar do código.

Os exemplos básicos de funções estão no arquivo "07_funcoes.html", dentro da pasta 07_funcoes. Neles contém multiplicação e soma utilizando funções.


8. MANIPULAÇÃO DE PÁGINA COM JAVASCRIPT

1. O que é document?
Serve para acessar toda a página HTML e manipular seus elementos, estilos e conteúdo.

2. Para que serve getElementById()?
Seleciona um elemento da página usando o seu id. Retorna apenas um elemento.

3. Para que serve querySelector()?
Seleciona o primeiro elemento que corresponde a um seletor CSS (id, classe ou tag).

4. Para que serve .value?
Usado para ler ou alterar o valor de campos de formulário como input, textarea ou select.

5. Para que serve .checked?
Verifica se um checkbox ou radio button está marcado, ou permite marcar/desmarcar.

6. Para que serve .textContent?
Permite alterar ou ler o texto interno de um elemento.

7. Para que serve .style?
Permite alterar diretamente os estilos CSS de um elemento.

8. Para que serve classList?
Permite adicionar, remover ou alternar classes de um elemento.

9. Para que serve addEventListener()?
Permite adicionar eventos a elementos, como clique, digitar ou passar o mouse.

10. Para que serve querySelectorAll()?
Seleciona todos os elementos que correspondem a um seletor CSS, retornando uma lista.

11. Para que serve checkValidity()?
Verifica se um campo de formulário atende às regras de validação (required, pattern, etc.).

12. Para que serve DOMContentLoaded?
Evento que dispara quando todo o HTML foi carregado, antes de imagens e estilos externos.

13. Para que serve createElement()?
Cria um novo elemento HTML dinamicamente.

14. Para que serve appendChild()?
Adiciona um elemento como filho de outro elemento na página.

15. Para que serve remove()?
Remove um elemento da página.

referências:

LIMA, Guilherme. JavaScript: o que é, para que serve e como aprender. Alura, 2023. Disponível em: https://www.alura.com.br/artigos/javascript. Acesso em: 31 mar. 2026.

WEB.DEV. Escopo global e local. [S. l.]: web.dev, 2020. Disponível em: https://web.dev/articles/global-and-local-scope?hl=pt-br. Acesso em: 31 mar. 2026.

BENNADJI, Ziad. Instruções if else em C explicadas. freeCodeCamp, 2022. Disponível em: https://www.freecodecamp.org/portuguese/news/instrucoes-if-else-em-c-explicadas/. Acesso em: 31 mar. 2026.

ELIAS, Otoniel. Funções na programação: o que são e como criá-las de forma eficiente. DIO, 2023. Disponível em: https://www.dio.me/articles/funcoes-na-programacao-o-que-sao-e-como-cria-las-de-forma-eficiente-f3ed466dbbab. Acesso em: 31 mar. 2026.





