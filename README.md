# Trama - Guia visual de defeitos têxteis

Guia de consulta para identificar sinais de defeitos em tecidos e costuras, conferir informações e registrar uma ocorrência antes de encaminhá-la para avaliação.

A ideia do projeto veio da minha experiência no setor de corte de uma indústria têxtil. Quis organizar a consulta em fichas curtas, aproximando o conteúdo da rotina de inspeção.

## Como abrir

Abra `dist/index.html` no navegador. Não é necessário instalar dependências ou executar um servidor. Para publicar em uma hospedagem estática, use o conteúdo da pasta `dist`.

## O que o guia apresenta

- Seis fichas: furo, fio puxado, mancha, diferença de tonalidade, franzimento e ponto falhado.
- Navegação por estrutura do tecido, superfície e cor, e costura.
- Orientações sobre o que observar, conferir e registrar.
- Quadro de critérios e roteiro de inspeção.
- Layout responsivo e estilos de impressão.

## HTML e CSS, sem JavaScript

O HTML organiza o conteúdo com `header`, `nav`, `main`, `section`, `article`, `figure` e `footer`. Os links internos levam às categorias. As fichas usam `details` e `summary`, elementos nativos do navegador que abrem e fecham sem scripts.

O CSS usa variáveis para cores, Grid para o catálogo e Flexbox para alinhamentos. As media queries adaptam o layout a telas menores. Há foco visível, link para pular a navegação e suporte à preferência por movimento reduzido.

Não há pesquisa por texto, banco de dados, login ou registro de inspeções. A proposta é consultar informações, não gerenciar a produção.

## Estrutura

- `dist/index.html`: conteúdo e estrutura da página.
- `dist/styles.css`: identidade visual, componentes, responsividade e impressão.
- `dist/assets/defeitos-atlas.png`: seis ilustrações em uma única imagem.

As imagens usam a mesma fonte, organizada em três colunas e duas linhas. O CSS posiciona o atlas dentro de cada `figure`, com `overflow: hidden`, para mostrar o recorte correspondente. O texto alternativo identifica o exemplo de cada ficha.

## Conteúdo e limites

Este é um material demonstrativo de portfólio, não um padrão industrial de inspeção. As imagens foram geradas com IA e representam exemplos ilustrativos; não são fotografias de ocorrências reais nem referências metrológicas. A imagem de ponto falhado é uma representação simplificada da irregularidade.

As orientações são exemplos gerais. Não foram estabelecidas tolerâncias, limites dimensionais, pontuação de defeitos ou classificação universal de gravidade. Para uso real, o conteúdo e as imagens precisam ser revisados pelo responsável técnico e alinhados à ficha técnica e à amostra aprovada de cada produto.

## Verificação desta versão

Foram conferidos os caminhos dos arquivos, links internos, IDs, textos alternativos, estrutura HTML e ausência de scripts. A versão não passou por testes visuais em navegador nesta entrega.

Para conferir localmente: abra as fichas com mouse e teclado, reduza a largura da janela e use a visualização de impressão. Em navegadores antigos, abra as fichas antes de imprimir caso o conteúdo fechado não seja exibido.

## O que consigo explicar com este projeto

- Como organizar um catálogo usando HTML semântico.
- Como criar interação com elementos nativos, sem JavaScript.
- Como adaptar colunas e navegação para telas pequenas.
- Como diferenciar uma orientação de consulta de uma regra de aprovação.
- Como reutilizar uma imagem com diferentes recortes no CSS.
