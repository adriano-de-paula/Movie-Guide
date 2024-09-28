# Guia de Filmes

Guia de Filmes é um site simples onde você pode pesquisar por filmes e obter informações detalhadas sobre eles, como título, avaliação no IMDb, classificação, duração, gênero, enredo e elenco. O site utiliza a API OMDB para fornecer os dados dos filmes, que estão disponíveis apenas em inglês.

## Funcionalidades

- Pesquisa de filmes por nome.
- Exibição de informações detalhadas do filme:
  - Título
  - Avaliação no IMDb
  - Classificação indicativa
  - Ano de lançamento
  - Duração
  - Gêneros
  - Enredo
  - Elenco
- Mensagens de erro para filmes não encontrados ou quando ocorre algum problema.

## Tecnologias Utilizadas

- **HTML5**: Estruturação do site.
- **CSS3**: Estilização do site com uso de grid e design responsivo.
- **JavaScript**: Manipulação da DOM e interação com a API OMDB.
- **OMDB API**: Fonte dos dados sobre os filmes (dados disponíveis apenas em inglês).

## Pré-requisitos

- Uma chave de API da OMDB. Você pode obtê-la em [omdbapi.com](http://www.omdbapi.com/apikey.aspx).

  Substitua a sua chave no arquivo `key.js`:

    ```javascript
    key = "sua-chave-API";
    ```

## Exemplo de Uso

Digite o nome de um filme no campo de pesquisa e veja as informações detalhadas como imagem do pôster, avaliação, ano de lançamento, classificação indicativa, duração, gêneros, enredo e elenco.

## Melhorias Futuras

- Implementar navegação entre páginas de resultados.
- Adicionar sugestões de filmes conforme o usuário digita.
- Procurar uma API de filmes em português para oferecer dados localizados.
- Melhorar a interface com novos estilos e animações.

## Créditos

Este projeto foi baseado em uma videoaula disponível no YouTube por **Coding Artist**: [Movie Guide App With Javascript | HTML, CSS & Javascript](https://youtu.be/TgE71N0q5yI?si=8OGNayLLm-IiBF8u).
