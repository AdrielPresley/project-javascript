# Sintaxe e Operadores

* Este repositório contém a solução da atividade prática do Curso "Sintaxe e Operadores", que faz parte do Bootcamp Philips Fullstack Developer | You Are You - Digital Innovation One.

## Atividade 1: Sintaxe e Operadores
* Crie uma função que recebe dois números como parâmetros.
* Confira se os números são iguais.
* Confira se a soma dos números é maior que 10 ou menor que 20.
* Retorne uma string dizendo "Os números ``num1`` e ``num2`` não/são iguais. Sua soma é ``soma``, que é ``maior/menor`` que 10 e ``maior/menor`` que 20".

Exemplo:

``Input: 1, 2``

``Output: Os números 1 e 2 não são iguais. Sua soma é 3, que é menor que 10 e menor que 20.``

# Variáveis e Tipos

* Este repositório contém a solução da atividade prática do Curso "Variáveis e Tipos", que faz parte do Bootcamp Philips Fullstack Developer | You Are You - Digital Innovation One.

## Atividade 1: Variáveis e Tipos

* Verifique, de duas maneiras diferentes entre si, se uma String é um palíndromo.

* *Palíndromo: frase ou palavra que se pode ler, indiferentemente, da esquerda para a direita ou vice-versa (ex.: raiar, ama, ovo, radar)*

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

* Instale a extensão "Live Server" no seu VSCode;

* Crie um arquivo com uma estrutura HTML padrão;

* Crie dois arquivos ``.js`` ou ``.mjs``, um chamado funcoes e outro chamado ``main``;

* No arquivo ``funcoes``:

1) Crie uma função chamada ``mostraIdade``, que recebe ``nome`` e ``idade`` e retorna a string: ``A idade de ${nome} é ${idade}``;

2) Siga o mesmo padrão para outras funções como ``mostraCidade`` e ``mostraHobby``;

3) Exporte estas funções.

* No arquivo ``main``:

1) Importe as funções do arquivo funcoes;

2) Faça a chamada de todas elas;

* Utilizando a extensão ``"Live Server"``, abra o seu navegador e veja no console que as informações foram logadas corretamente.

## Atividade 2: Módulos - "Imports Dinâmicos"

* Este exercício serve apenas como um exemplo de como utilizar módulos por demanda. Na nossa página HTML, ao clicar no botão, o fundo da página fica vermelho.

* Não se esqueça de utilizar a extensão ``"Live Server"`` ao realizar a atividade!

# Funções

* Este repositório contém a solução da atividade prática do Curso "Funções", que faz parte do Bootcamp Philips Fullstack Developer | You Are You - Digital Innovation One.

## Atividade 1: Funções - "Alunos Aprovados"

* Crie uma função que recebe o array ``alunos`` e um número que irá representar a média final;
* Percorra o array e popule um novo array auxiliar apenas com os ``alunos cujas notas são maiores`` ou ``iguais`` à média final;
* Utilize a técnica ``"object destructuring"`` para manipular as propriedades desejadas de cada aluno.

## Atividade 2: Funções - "This"

* Dada a função ``calculaIdade``, utilize os métodos call e apply para modificar o valor de ``this``. 

* Crie seus próprios objetos para esta atividade!

```
function calculaIdade(anos) {
	return `Daqui a ${anos} anos, ${this.nome} terá ${this.idade + anos} anos de idade.`;
}
```

## Projeto desenvolvido durante o Bootcamp Philips Fullstack Developer | You Are You - Digital Innovation One.
