# Sintaxe e Operadores

* Este repositório contém a solução da atividade prática do Curso "Sintaxe e Operadores", que faz parte do Bootcamp Philips Fullstack Developer | You Are You - Digital Innovation One.

## Atividade 1: Sintaxe e Operadores

1) Crie uma função que recebe dois números como parâmetros.
2) Confira se os números são iguais.
3) Confira se a soma dos números é maior que 10 ou menor que 20.
4) Retorne uma string dizendo "Os números ``num1`` e ``num2`` não/são iguais. Sua soma é ``soma``, que é ``maior/menor`` que 10 e ``maior/menor`` que 20".

Exemplo:

``Input: 1, 2``

``Output: Os números 1 e 2 não são iguais. Sua soma é 3, que é menor que 10 e menor que 20.``

# Variáveis e Tipos

* Este repositório contém a solução da atividade prática do Curso "Variáveis e Tipos", que faz parte do Bootcamp Philips Fullstack Developer | You Are You - Digital Innovation One.

## Atividade 1: Variáveis e Tipos

1) Verifique, de duas maneiras diferentes entre si, se uma String é um palíndromo.

``Nota: Palíndromo = frase ou palavra que se pode ler, indiferentemente, da esquerda para a direita ou vice-versa (ex.: raiar, ama, ovo, radar)``

## Atividade 2: Variáveis e Tipos

* Troque todos os elementos pares e diferentes de zero de um array pelo número 0. Se o array for vazio, retorne -1.

Exemplo: 

``Input: [1, 3, 4, 6, 80, 33, 23, 90]``

``Output: [1, 3, 0, 0, 0, 33, 23, 0]``

``Input: []``

``Output: -1``

# Módulos

* Este repositório contém a solução da atividade prática do Curso "Módulos", que faz parte do Bootcamp Philips Fullstack Developer | You Are You - Digital Innovation One.

## Atividade 1: Módulos

* Esta atividade tem como objetivo que você veja no console do seu navegador como os módulos funcionam.

1) Instale a extensão "Live Server" no seu VSCode;

2) Crie um arquivo com uma estrutura HTML padrão;

3) Crie dois arquivos ``.js`` ou ``.mjs``, um chamado funcoes e outro chamado ``main``;

4) No arquivo ``funcoes``:

4.1) Crie uma função chamada ``mostraIdade``, que recebe ``nome`` e ``idade`` e retorna a string: ``A idade de ${nome} é ${idade}``;

4.2) Siga o mesmo padrão para outras funções como ``mostraCidade`` e ``mostraHobby``;

4.3) Exporte estas funções.

5) No arquivo ``main``:

5.1) Importe as funções do arquivo funcoes;

5.2) Faça a chamada de todas elas;

* Utilizando a extensão ``"Live Server"``, abra o seu navegador e veja no console que as informações foram logadas corretamente.

## Atividade 2: Módulos - "Imports Dinâmicos"

* Este exercício serve apenas como um exemplo de como utilizar módulos por demanda. Na nossa página HTML, ao clicar no botão, o fundo da página fica vermelho.

* Não se esqueça de utilizar a extensão ``"Live Server"`` ao realizar a atividade!

# Funções

* Este repositório contém a solução da atividade prática do Curso "Funções", que faz parte do Bootcamp Philips Fullstack Developer | You Are You - Digital Innovation One.

## Atividade 1: Funções - "Alunos Aprovados"

1) Crie uma função que recebe o array ``alunos`` e um número que irá representar a média final;
2) Percorra o array e popule um novo array auxiliar apenas com os ``alunos cujas notas são maiores`` ou ``iguais`` à média final;
3) Utilize a técnica ``"object destructuring"`` para manipular as propriedades desejadas de cada aluno.

## Atividade 2: Funções - "This"

1) Dada a função ``calculaIdade``, utilize os métodos call e apply para modificar o valor de ``this``. 

2) Crie seus próprios objetos para esta atividade!

```
function calculaIdade(anos) {
	return `Daqui a ${anos} anos, ${this.nome} terá ${this.idade + anos} anos de idade.`;
}
```
# Coleções Chaveadas

* Este repositório contém a solução da atividade prática do Curso "Coleções", que faz parte do Bootcamp Philips Fullstack Developer | You Are You - Digital Innovation One.

## Atividade 1: Maps - "Coleções"

* Crie uma função que retorna o nome dos membros de um Map que tem o papel 'ADMIN' no sistema.
1) Crie uma função ``getAdmins`` que recebe um ``Map``;
2) Crie um Map e popule-o com nomes de usuários e seus papeis no sistema. ``(Ex: 'Luiz' => 'Admin');``
3) Dentro de ``getAdmins``, utilize o loop ``for...of`` para retornar uma lista com os nomes dos usu;arios que são administradores.

## Atividade 2: Sets - "Coleções"

* Dado o array ``[30, 30, 40, 5, 223, 2049, 3034, 5]``, retorne outro array apenas com valores únicos.

# Tratamento de Erros

* Este repositório contém a solução da atividade prática do Curso "Tratamento de Erros", que faz parte do Bootcamp Philips Fullstack Developer | You Are You - Digital Innovation One.

## Atividade: Validação de erros por tipo

* O objetivo é que a função receba um array e retorne ele caso o seu tamanho corresponda ao número enviado como parâmetro na função. Caso contrário, um erro será lançado.

1) Crie uma função que recebe um array e um número
2) Realize as seguintes validações
2.1) Se os parâmetros não forem enviados, lance um erro do tipo ``ReferenceError``
2.2) Se o array não for do tipo 'object', lance um erro do tipo ``TypeError``
2.3) Se o número não for do tipo 'number', lance um erro do tipo ``TypeError``
2.4) Se o tamanho do array for diferente do número enviado como parâmetro, lance um erro do tipo ``RangeError``
3) Utilize a declaração ``try...catch``
4) Filtre as chamadas de catch por cada tipo de erro utilizando o operador ``instanceof``

## Projeto desenvolvido durante o Bootcamp Philips Fullstack Developer | You Are You - Digital Innovation One.
