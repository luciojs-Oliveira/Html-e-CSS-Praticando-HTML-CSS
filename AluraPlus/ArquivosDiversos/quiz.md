Variáveis CSS
 Próxima Atividade

No vídeo anterior, declaramos variáveis que representam o hexadecimal das cores ao invés de usar esse valor diretamente nos atributos CSS. Qual afirmação abaixo representa melhor a motivação do uso de variáveis CSS?

Alternativa correta
Os nomes das variáveis CSS indicam o contexto em que ela será usada, ajudando a entender onde deve ser colocada.


Alternativa correta
Variáveis CSS facilitam o entendimento do uso das cores, a atribuição e manutenção.


Alternativa correta! Variáveis CSS auxiliam no entendimento do uso das cores por terem nomes que fazem sentido com o seu uso, consequentemente isso também facilita a atribuição nos elementos HTML. Além desses dois benefícios, facilita na manutenção do código: é possível alterar o valor de alguma cor reescrevendo um único lugar do código.

Alternativa correta
Variáveis CSS diminuem significativamente a repetição de valores na folha de estilo.


Alternativa correta
Variáveis CSS servem apenas para tornar o código agradável esteticamente.

...............................................................................................................

A motivação da imagem
 Próxima Atividade

Acabamos de inserir duas imagens de maneira distinta no nosso código. A imagem do Combo+ foi implementada no arquivo index.html dessa maneira:

<img src=”img/Combo.png” alt=”O combo+ é a junção do alura+ e o alura lingua”>
Copiar código
Já a imagem de fundo, que apresenta vários instrutores da Alura, foi implementada no arquivo styles.css desse jeito:

.principal {
background-image: url(“img/Background.png”);
}
Copiar código
Por que a imagem dos instrutores e instrutoras não foi colocada dentro da tag de imagem, a <img>?

Alternativa correta
Pois a imagem “Background.png” é decorativa e seu contexto não muda a leitura da página.


Alternativa correta! É isso aí! Quando estamos inserindo uma imagem, é importante pensar: essa imagem faz parte do conteúdo da página? Se não, é possível colocá-la como background-image() de algum elemento.

Alternativa correta
Porque ela tem o intuito de ilustrar uma informação da página: a equipe de instrutores.


Alternativa correta
Não é possível definir um texto alternativo para a imagem “Background.png”


Alternativa correta
Por preferência pessoal da pessoa desenvolvedora do código.

...............................................................................................................

 Botão ou âncora?
 Próxima Atividade

Não seja levado pelas aparências: os elementos <a> e <button> podem ser exatamente iguais aos nossos olhos, pois basta que sejam estilizados apropriadamente. Porém, por trás, não são iguais. Eles possuem significados diferentes, e cabe à pessoa desenvolvedora compreender o contexto para escolher qual utilizar.

Analise o botão do layout a seguir e escolha qual elemento é mais apropriado para usar e a sua motivação:

Elemento com um formulário de nome AluraForm solicitando e-mail, senha e nome completo. Ao final dele, consta os botões Enviar e Apagar. Uma seta vermelha aponta para o botão Apagar.

Alternativa correta
O elemento que deverá ser usado é o <a> por permitir o clique do mouse.


Alternativa correta
O elemento que deverá ser usado é o <button> por ele ser igual a um botão.


Alternativa correta
O elemento que deverá ser usado é o <a> por executar uma função ao ser clicado: apagar os dados do formulário.


Alternativa correta
O elemento que deverá ser usado é o <button> por executar uma função ao ser clicado: apagar os dados do formulário.


Alternativa correta! Isso mesmo! Quando queremos que um evento aconteça a partir do clique do mouse, utilizamos os botões.

...............................................................................................................

Dividindo nossa section
 Próxima Atividade

Utilizando do conhecimento adquirido no vídeo anterior, qual código abaixo resulta na divisão da tela representada pela imagem a seguir ?

Primeira section do alura plus cortada em três partes, a primeira ocupando um espaço maior e, ao lado direito, duas menores de tamanho igual

Alternativa correta
display: grid;
grid-columns: 50% 25% 25%;

Alternativa correta
display: grid;
grid-template-columns: 50% 25% 25%;

Alternativa correta! Dessa maneira, a primeira coluna ocupará metade da tela e em seguida serão construídas duas colunas menores, que ocupam a metade do tamanho da primeira cada uma.

Alternativa correta
grid-template-columns: 50% 25% 25%;

Alternativa correta
display: grid;
grid-template-columns: 50% 25%;

...............................................................................................................

Separando elementos
 Próxima Atividade

No vídeo anterior, foi demonstrado o uso de margins e as comparações dele com o padding. Das afirmações abaixo, quais são corretas?

I. Margins criam um espaçamento ao redor do elemento.

II. Paddings criam um espaçamento dentro do elemento.

III. Paddings afastam um elemento do outro.

IV. É possível configurar valores de margins diferentes para cada lado.

Alternativa correta
Somente I e III.


Alternativa correta
Todas as alternativas estão corretas.


Alternativa correta
Somente I, II e IV.


Alternativa correta! Margins realmente criam espaço ao redor do elemento e paddings criam dentro dele, ou seja, o padding afasta o conteúdo da borda e não um elemento do outro. Por fim, também podemos configurar valores diferentes para cada lado do elemento e, no vídeo, vimos diversas maneiras de fazer isso.

Alternativa correta
Somente I e II.


Alternativa correta
Somente II e IV.

...............................................................................................................

Centralizando elementos
 Próxima Atividade

No último vídeo, conhecemos as propriedades de alinhamento text-align e align-items. Imagine que você está desenvolvendo outro projeto ao mesmo tempo no nosso time, o Alura Cats, que consiste em um container com um título, uma imagem, um parágrafo e uma âncora:

<div class="container">
<h2 class="container__titulo">Alura Cats!</h2>
<img src="https://thecatapi.com/api/images/get?format=src&type=gif" alt=”imagem de gatos” class="container__imagem">
  <p>Para mais informações:</p>
<a href="www.alura.com.br" class="container__botao">Acesse a Alura<a>
</div>
Copiar código
Visualmente, após algumas estilizações feitas com CSS, o resultado desse código ficará assim:

Um bloco contendo um título chamado Alura Cats!, em seguida uma imagem de um gato branco, depois um texto “Para mais informações” e por fim uma âncora chamada “Acesse a Alura”, que redireciona para o site da Alura

Você pode testar o código do Alura Cats no meu repositório do codepen.

Tendo isso pronto, qual propriedade CSS você usaria para alinhar ao centro todos os itens deste container e por quê?

Alternativa correta
text-align, porque ele consegue alinhar todos elementos dentro do bloco.


Alternativa correta! O código começa com um elemento de bloco (a div), ou seja, que tem display block, e há elementos dentro dele que são inline. Dessa maneira, usar a propriedade text-align na div permitirá alinhar para qualquer lado que você desejar os elementos filhos da div.

Alternativa correta
align-items, por conseguir alinhar todos elementos da página.


Alternativa correta
align-items, por alinhar os elementos de acordo com a coluna do grid.


Alternativa correta
text-align, pois como diz sua tradução literal: alinhar texto.

...............................................................................................................

O famoso Github!
 Próxima Atividade

Acabamos de criar a nossa conta no Github, criar nosso repositório e inserir os arquivos. Analisando o que fizemos, qual das opções abaixo NÃO é uma função do Github?

Alternativa correta
Montar portfólio.


Alternativa correta
Compartilhar projetos com a equipe de trabalho.


Alternativa correta
Visualizar código de outros desenvolvedores.


Alternativa correta
Executar código.


Alternativa correta! Não conseguimos executar o código, apenas fazer o deploy da aplicação através do Github Pages ou outras aplicações semelhantes como a Vercel.

...............................................................................................................

