# API do Pokemon
API do pokemon foi um projeto desenvolvido no curso de backend da [Cubos Academy](https://cubos.academy/).
Criaremos uma API para responder informações de pokemons.Para isso, utilizaremos como fonte dos dados as funções `listarPokemons` e `detalharPokemon`, da biblioteca [utils-playground](https://www.npmjs.com/package/utils-playground), que pode ser baixada no NPM.

Deste modo, o fluxo será:

1. O usuário vai chamar a API que você vai criar atrevés do método [GET](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/GET), onde foi testado em `localhost` na porta 8000 usando o aplicativo [insomnia](https://insomnia.rest/download)
2. Como são muitos pokemons separamos dez por página, para acessar a página basta `http://localhost:8000/pokemon?page="numero da pagaina"`
3. Para procurar um pokemon específico basta `http://localhost:8000/pokemon/"nome ou id do pokemon"`

## Exemplos
 `http://localhost:8000/pokemon/1` ou `http://localhost:8000/pokemon/bulbasaur`
 ![bulbasaur](https://user-images.githubusercontent.com/141869821/271735897-0f89c6c7-cb26-49f1-a937-4b9e70f50ff0.png)

`http://localhost:8000/pokemon/2` ou `http://localhost:8000/pokemon/ivysaur`
![ivysaur](https://user-images.githubusercontent.com/141869821/271736453-da1d054b-68e9-4142-82b9-fd1f742620a5.png)

## Tecnologias utilizadas
- JavaScript

## Como executar o projeto
```Bash
# clonar repositório
git clone git@github.com:YuriBrizolara/api_pokemon.git
# entrar na pasta do projeto
cd api_pokemon
# configurar npm padrão
 npm init -y
# instalar o express
npm i express
# instalar utils-playground
npm i utils-playground
# entar na pasta do programa
cd src
# rodar programa
node --watch index.js
```
# Autor
Yuri da Cruz Brizolara
[linkedin](www.linkedin.com/in/yuribrizolara)
