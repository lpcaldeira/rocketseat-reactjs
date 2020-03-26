# rocketseat-reactjs
Testando conhecimentos de JS com os cursos da Rocketseat

JSX são os html misturados com variáveis, que é a forma que o reactjs trabalha.

Vamos iniciar usando o pacote `create-react-app` e o yarn, que também é do Facebook, através do comando `npx create-react-app rockeseat-reactjs`.

Só rodar um npm start e acessar localhost:3000 para visualização a aplicação.

Agora, vamos adicionar o `yarn add axios` para incluir o axios no nosso projeto e trabalhar com a api criada no projeto `rocketseat-nodejs`.

O próximo passo é adicionar a api da `rockeseat-nodejs do Heroku` no projeto e consumi-la.

Para isso, vamos parar de usar a nomenclatura `StateLess` e passar a usar `{ Component }` no projeto para tratar o `state`.

Começamos a trabalhar com as routes e paga isso usamos `yarn add react-router-dom`.

Assim, criamos a rota `Main`, que é a principal/primeira e a rota `Product` passando um id da mesma forma que é no `nodejs` quando queremos trazer apenas 1 produto e direcionar para uma rota exclusiva dele.

Também adicionamos na rota primária o atributo `exact` para só cair naquela rota quando não recebermos exatamente nada na url, redirecionando assim para a `Main`.

Se não tiver esse atributo, qualquer rota que vier depois deste `Route`, vai ser ignorada.

