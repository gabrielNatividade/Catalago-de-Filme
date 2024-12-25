# Catálogo de Filmes

Este é um projeto simples de catálogo de filmes que utiliza a [OMDb API](http://www.omdbapi.com/) para buscar informações sobre filmes com base em termos de pesquisa fornecidos pelo usuário.

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)
- Fetch API para requisições HTTP

## Funcionalidades

- Pesquisa de filmes por título.
- Exibição de uma lista com os filmes encontrados.
- Exibição de informações básicas dos filmes: pôster e título.

## Estrutura do Projeto

```
raiz/
├── index.html   # Arquivo principal da interface do usuário
├── style.css    # Estilo visual do projeto
├── app.js       # Lógica e integração com a API
```

## Lógica Principal (app.js)

O script realiza os seguintes passos:

1. Captura o evento de envio do formulário e impede seu comportamento padrão.
2. Faz uma requisição à OMDb API utilizando o título fornecido.
3. Processa a resposta JSON e gera dinamicamente os elementos na página.
4. Exibe uma mensagem de erro caso nenhum filme seja encontrado ou o campo de busca esteja vazio.
