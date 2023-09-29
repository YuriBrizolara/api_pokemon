# API do Pokemon
API do pokemon foi um projeto desenvolvido no curso de backend da [Cubos Academy](https://cubos.academy/).
Criaremos uma API para responder informações de pokemons.Para isso, utilizaremos como fonte dos dados as funções `listarPokemons` e `detalharPokemon`, da biblioteca [utils-playground](https://www.npmjs.com/package/utils-playground), que pode ser baixada no NPM.

Deste modo, o fluxo será:

1. O usuário vai chamar a API que você vai criar atrevés do método [GET](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/GET), onde foi testado em `localhost` na porta 8000 usando o aplicativo [insomnia](https://insomnia.rest/download)

##Exemplos
 `http://localhost:8000/pokemon/1` ou `http://localhost:8000/pokemon/bulbasaur`
 ![bulbasaur]([https://github.com/YuriBrizolara/api_pokemon/issues/1#issue-1920007206](https://user-images.githubusercontent.com/141869821/271735897-0f89c6c7-cb26-49f1-a937-4b9e70f50ff0.png)https://user-images.githubusercontent.com/141869821/271735897-0f89c6c7-cb26-49f1-a937-4b9e70f50ff0.png)
