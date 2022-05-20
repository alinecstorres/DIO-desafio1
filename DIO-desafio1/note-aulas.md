# GIT Comandos básicos :keyboard:

### Windows :desktop_computer:

* Mudar de pastas:arrow_right:cd nomedapasta
* Voltar à pasta anterior:arrow_right:cd ..
* Listar as pastas:arrow_right:ls
* Criar pastas:arrow_right:mkdir
* Deletar pastas:arrow_right:del/rmdir
* Criar arquivos:arrow_right:echo >
* Limpar a tela:arrow_right:ctrl+l

# HTML5

## Definição e estrutura básica

* < !DOCTYPE html> Diz ao navegador o que vc está escrevendo
* < html> Tag abertura
* < head>Cabeçalho
  * < meta> Informações que o navegador necessita (adicionamos o atributo charset com o valor UTF-8 para dizer ao navegador qual é a codificação dos caracteres)
  * < title></title>Título na aba do navegador
* < body>Conteúdo da página

## Semântica

* < section>Seção genérica de conteúdo quando não houver um elemento mais específico para isso.
* < header>É o cabeçalho da página ou de uma seção da página e normalmente contém logotipos, menus, campos de busca.
* < article>Representa um conteúdo independente e de maior relevância dentro de uma página, como um post de blog, uma notícia em uma barra lateral ou um bloco de comentários. Um article pode conter outros elementos, como header, cabeçalhos, parágrafos e imagens.
* < aside>É uma seção que engloba conteúdos relacionados ao conteúdo principal, como artigos relacionados, biografia do autor e publicidade. Normalmente são representadas como barras laterais.
* < footer>Esse elemento representa o rodapé do conteúdo ou de parte dele, pois ele é aceito dentro de vários elementos, como article e section e até do body. Exemplos de conteúdo de um < footer> são informações de autor e *links* relacionados.
* < h1>-< h6>Eles não foram criados na versão 5 do HTML e nem são específicos para semântica, mas servem para esse propósito. São utilizados para marcar a importância dos títulos, sendo < h1> o mais importante e < h6> o menos. Uma dica: use apenas um < h1> por página, pois ele representa o objetivo da sua página.

## Textos e links

* < h1>Título da Página< /h1>
* < h2>Título da Seção< /h2>
* < h3>Título do Artigo< /h3>
* < p>Conteúdo de Artigo< /p>
* < P>Parágrafo< /P>
* < a href="link" target="_blank">palavradotexto< /a>
* < a href="mailto:@" target="_blank">palavradotexto< /a>

## Imagens

* < img>
* < img scr="caminho do objeto">
* < img alt="descrição do objeto">

:couch_and_lamp: Site para comprimir imagem: <a href="www.tinypng.com" target="_blank">Tinypng</a>

## Listas

* < ul>A ordem dos itens não importa
* < ol>A ordem dos itens é importante
* < li>É um item da lista

