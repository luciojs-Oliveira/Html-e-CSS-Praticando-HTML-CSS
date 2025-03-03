Para saber mais: primeiros passos no front-end
 Próxima Atividade

Quando começamos um arquivo HTML, há uma estrutura padrão que é usada em qualquer projeto do tipo, que foi apresentada no vídeo anterior. É importante saber quais são as tags que precisam ser implementadas e entender seus papéis dentro do código.

Você pode aprender mais sobre essas tags que fazem parte da base de um arquivo HTML com o artigo “O que é o HTML e suas tags? Parte 1: estrutura básica”, feito pela instrutora Beatriz Moura em parceria com o instrutor Matheus Henrique.https://www.alura.com.br/artigos/o-que-e-html-suas-tags-parte-1-estrutura-basica

Ao fazer as alterações no projeto, era necessário recarregar a página ou abrir o arquivo para conseguir visualizar o que foi criado. Assim, a extensão Live Server auxilia nisso. Você pode conhecer mais sobre ela e outras extensões no artigo Extensões VS Code: descubra quais são as mais usadas, também da instrutora Beatriz Moura.
https://www.alura.com.br/artigos/extensoes-vs-code-descubra-as-mais-usadas

...............................................................................................................

Para saber mais: classes, unidades e grid!
 Próxima Atividade

Ao continuar o projeto Alura Plus, foi necessário atribuir classes para os elementos, possibilitando a estilização de locais específicos. Quando você fez isso comigo, eu citei sobre um padrão de nomenclatura: o Block Element Modifier (BEM). Você pode ler mais sobre isso no artigo “Nome de classes no CSS”, produzido pelo instrutor Yuri Padilha.
https://www.alura.com.br/artigos/nomes-de-classes-no-css


Para entender melhor sobre o uso de classes e conhecer outro atributo semelhante chamado id, convido você a ler o meu artigo “Qual a diferença entre id e class”.
https://www.alura.com.br/artigos/qual-diferenca-entre-id-e-class

Apresentei a unidade de medida relativa “em” na criação do botão da página e há muitas além dessa com o mesmo intuito. Para conhecer ou compreender melhor o uso do “em”, você pode consultar o artigo “Guia de unidades no CSS” do instrutor Paulo Scalercio. Esse é um ponto de atenção importantíssimo!
https://www.alura.com.br/artigos/guia-de-unidades-no-css


Durante o desenvolvimento da primeira seção, também vimos o uso de Grid. Assim como os outros conteúdos, temos um artigo para você reforçar esse aprendizado e consultar quando for preciso. Apresento a você o “Criando layouts com CSS Grid Layout”, produzido pelo Matheus Castiglioni.
https://www.alura.com.br/artigos/criando-layouts-com-css-grid-layout

...............................................................................................................

Para saber mais: CSS interativo?
 Próxima Atividade

Uma pseudo-classe CSS é uma propriedade que é adicionada ao final dos seletores que especifica o estado que esse elemento está. Ele detecta, por exemplo, se o elemento está com um mouse em cima dele, construindo uma experiência interativa com o usuário. Aqui, você pode conferir uma lista de pseudo-classes para testar no seu projeto:

:focus: é aplicada quando um elemento está em foco, pode ser pelo clique do mouse ou seleção pelo teclado. Um exemplo é quando os campos de escrita em formulários estão selecionados para o usuário escrever.

:hover: detecta quando um usuário está com o mouse em cima do elemento, sem necessariamente estar clicando.

:active: detecta quando o elemento está ativo, quando há uma interação, por exemplo: o link <a> está sendo clicado.

:visited: detecta quando o link <a> já foi visitado, ou seja, se você já clicou anteriormente naquele link.

:link: detecta quando é um link <a> que nunca foi clicado antes.

A sintaxe correta de uso de pseudo-classes é essa:

seletor:pseudo-classe {
  propriedade: valor;
}Copiar código
Um exemplo de utilização na prática seria este de trocar a cor do botão para azul quando o mouse estiver em cima dele:

.container__botao:hover {
  background-color: blue;
}Copiar código
Curiosidade
Lembra que na primeira aula colocamos o termo :root no styles.css? Percebe que a estrutura é bem semelhante ao que estamos vendo agora? Isso acontece porque o root também é uma pseudo-classe!

Porém, essa pseudo-classe não tem um intuito mais interativo, ou seja, não há como usar pra trocar alguma coisa quando o usuário interage. Sua especificidade é bem alta, representando o documento inteiro. É comumente usada para a declaração de variáveis CSS.

Você pode ler mais sobre pseudo-classes no MDN Web Docs, um projeto colaborativo de código aberto que documenta tecnologias de plataforma da Web, incluindo CSS, HTML, JavaScript e APIs da Web.

...............................................................................................................



Dica: No artigo "Como escrever um README incrível no seu Github", a instrutora Camila Alves explica como construir esse README, dando dicas e exemplos de referência.

...............................................................................................................


Para saber mais: Deploy
 Próxima Atividade

Esse processo que nós acabamos de fazer se chama deploy. O verbo deploy, em inglês, quer dizer implantar. Em programação, seu sentido está diretamente relacionado à sua tradução literal: fazer um deploy significa colocar no ar alguma aplicação que teve seu desenvolvimento concluído. Quando um site é finalizado por um desenvolvedor e, após seus testes, é finalmente hospedado e colocado no ar, ele passa pelo processo de deploy.

Primeiramente, hospedamos o Alura Plus no Github Pages, um serviço de hospedagem de site estático que usa arquivos HTML, CSS e JavaScript diretamente de um repositório no GitHub e, como opção, executa os arquivos por meio de um processo e publica um site. Em seguida, fizemos deploy do Alura Plus pela Vercel, uma plataforma voltada para a hospedagem gratuita de aplicações de uma forma bem simples e rápida. Ela é conhecida por ser a empresa criadora do framework Next JS, voltado para o React.

Caso você tenha interesse em conhecer mais sobre esse tipo de serviço ou conhecer outros sites, vou recomendar o artigo “Heroku, Vercel e outras opções de cloud como plataforma” do João Manoel.

https://docs.github.com/pt/pages/getting-started-with-github-pages/about-github-pages
https://vercel.com/lucios-projects-bc8ad035
https://www.alura.com.br/artigos/heroku-vercel-outras-opcoes-cloud-plataforma
...............................................................................................................

