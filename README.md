# AluraBooks — Interface de Livraria Virtual

Projeto de frontend que apresenta a página inicial de uma livraria virtual de livros sobre tecnologia, programação e desenvolvimento profissional, utilizando a identidade visual da AluraBooks.

## Sobre o projeto
A página reúne lançamentos, livros mais vendidos, recomendações de leitura e destaque de autora. O objetivo é praticar a construção de interfaces web com HTML e CSS, adaptação para diferentes tamanhos de tela e integração de carrosséis com JavaScript.

## Recursos da interface
- Cabeçalho com categorias e atalhos para favoritos, sacola e perfil.
- Banner com campo visual de pesquisa.
- Carrosséis de novos lançamentos e livros mais vendidos.
- Card de recomendação de livro.
- Seção de autora do mês.
- Lista de tópicos de interesse.
- Campo de e-mail para novidades.
- Rodapé com marcas e comunidades do Grupo Alura.
- Estilos para diferentes tamanhos de tela, com media queries em 1024 px e 1728 px.

## Tecnologias utilizadas
- **HTML5:** estrutura e conteúdo.
- **CSS3:** estilização, Flexbox, variáveis e media queries.
- **JavaScript:** inicialização dos carrosséis.
- **Swiper 11:** apresentação dos livros em slides.
- **Google Fonts:** fontes Poppins e Josefin Sans.

## Organização dos arquivos
- `index.html`: página principal e configuração do Swiper.
- `style.css`: variáveis, estilos gerais e importação dos demais estilos.
- `reset.css`: redefinição dos estilos padrão do navegador.
- `header.css`: cabeçalho e menus.
- `banner.css`: banner e campo de pesquisa.
- `carrosel.css`: carrosséis e cards.
- `topicos.css`: tópicos de interesse.
- `contato.css`: seção de novidades.
- `rodape.css`: rodapé.
- Arquivos `.svg`: capas de livros, ícones e logotipos.

## Como executar
1. Baixe e extraia o projeto.
2. Crie uma pasta `styles` e mova para ela os arquivos `header.css`, `banner.css`, `carrosel.css`, `topicos.css`, `contato.css` e `rodape.css`.
3. Crie uma pasta `img` e mova os arquivos SVG para ela.
4. Corrija as referências com nomes diferentes dos arquivos disponíveis, como:
   - `Apachekafka.svg` → `ApacheKafka.svg`.
   - `Guia Front-end.svg` → `GuiaFront-end.svg`.
   - `Scuba.svg` → `ScubaDev.svg`.
   - `Layers.svg` → `LayersTech.svg`.
   - `MenuAberto.svg` → `Menu Aberto.svg`.
5. Abra `index.html` no navegador.
Mantenha `style.css`, `reset.css` e `index.html` na pasta principal. É necessário acesso à internet para carregar o Swiper e as fontes externas.

## Status do projeto
Protótipo de interface para fins de estudo. Não possui backend, banco de dados ou processamento de compras.
Os campos de pesquisa e e-mail, assim como os atalhos de favoritos, sacola e perfil, são elementos visuais. A seção de tópicos também apresenta conteúdo fixo, sem registrar o histórico de navegação.
O código ainda contém inconsistências de marcação e seletores CSS que podem exigir ajustes para o funcionamento completo dos menus e do layout.

## Aprendizados
Prática de estruturação de páginas, organização de CSS por componentes, Flexbox, responsividade, uso de imagens SVG e integração de bibliotecas externas.
