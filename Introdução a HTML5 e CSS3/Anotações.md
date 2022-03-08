# HTML

* <DOCTYPE html>

* <html>

* <head> Elementos que serão lidos pelo navegador    

* <body>  Todo conteúdo visível ao usuário: textos,imagens,vídeos.

* #### Semântica

* section - Seção genérica de conteúdo quando não houver elemento mais específico 

* header- Cabeçalho da página, normalmente contém logotipos,menus,campos de busca

* article- Representa um conteúdo independente e de maior relevância dentro de uma página, como um post de blog, uma notícia.

* aside- É uma seção que engloba conteúdos relacionados ao conteúdo principal, como artigos relacionados, biografia do autor.

* footer- Esse elemento representa o rodapé do conteúdo ou de parte dele, pois ele é aceito dentro de vários elementos, como article e section e até do body.

* h1-h6- São utilizados para marcar a importância dos títulos, sendo <h1> o mais importante e <h6> o menos.

* #### Textos e links

* O <p> representa um parágrafo, mas ele não suporta apenas texto, podemos adicionar imagens, código, vídeos e vários outros tipos de conteúdo dentro dele.

*  O <a> - que significa anchor/âncora, ele representa um hyperlink, é ele que interliga vários conteúdos e páginas na web.

* O href representa o *hyperlink* para onde sua âncora aponta, pode ser uma página do seu ou de outro site, um e-mail e até mesmo um telefone, os dois últimos precisam dos prefixos mailto: e tel:, respectivamente.

* O target neste momento vai servir para nos ajudar a abrir nossos links em outra aba do navegador usando o valor _blank.

* #### Imagens

* Temos o elemento <img>  não possui tag de fechamento.

* Possui 2 atributos, o src e o alt.

* src é obrigatorio e guarda o caminho da imagem.

* alt é recomendado para melhor acessibilidade, ele mostra a descrição da imagem caso ela não carregue.

* #### Listas

* Elementos <ul>, <ol> e <li>.

* ul - Cria uma lista não ordenada, representada por pontos, círculos e quadrados.

* ol - Cria listas ordenadas, representadas por números, algarismos romanos ou letras.

* li - é um item dentro de uma dessas listas.



# CSS

* ID: é representado pelo símbolo # (hash) seguido de um nome para esse ID.

* Classe: a classe é representada de forma parecida do ID, mas é precedida por um ponto em vez do hash.

* E a diferença mais importante entre eles é a forma como devem ser usados: o ID só pode ser usado uma vez em uma página HTML enquanto a classe não tem restrições.

* Podemos adicionar CSS de duas formas, com o elemento *style*, e assim suas regras ficarão no arquivo HTML, ou podemos criar um arquivo CSS e adicioná-lo na página através do elemento *link*, e é essa forma que usaremos.

* Crie um elemento *link* dentro do head do seu arquivo e adicione os atributos *rel="stylesheet"* e *href="style.css"*, o *rel* denota o tipo de arquivo que estamos incluindo na página e o *href* é o caminho para o arquivo. E na mesma pasta do arquivo *HTML* crie um arquivo chamado *style.css*.

* Agora sim vamos ao CSS, adicione um ID #title ao h1 da página, pois queremos que ele seja único, e depois adicione as classes .subtitle e .post_title ao h2 e h3, respectivamente.

* #### Box model

* Quando estamos criando o layout de um site o navegador representa cada elemento HTML como uma caixa retangular, isso é o box-model. E com CSS nós alteramos a aparência dessa caixa (largura, altura, cor de fundo, etc.). Essa caixa é composta por 4 áreas: o conteúdo, o padding, a borda e a margem.

  - As margens (margin) são espaçamentos entre elementos;
  - As bordas (border) ; {solid,dotted,dashed}
  - O padding é um espaçamento entre as bordas e o conteúdo, a diferença para as margens é que declarações de imagem de fundo funcionam nele;
  - O conteúdo (content) é o que o seu bloco representa, um texto, uma imagem, um vídeo;

* #### Estilizando textos

* font-family - Com o font-family podemos alterar a fonte dos nossos textos, como uma fonte da internet ou uma que esteja instalada no nosso computador, mas vamos nos ater às fontes seguras, chamadas de web safe fonts.

* font-size - O font-size nos ajuda a mudar o tamanho do texto, existem algumas unidades de medida para ele mas por enquanto os pixels são suficientes para nós.

* font-style - Usamos o font-style para tornar um texto itálico, na maioria das vezes você usará apenas o valor *italic* para ele, mas se precisar tirar o itálico de um texto você pode usar o valor *normal*

