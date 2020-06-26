você pode rodar com:  
`npx webpack`

pode também caso tenha o arquivo **webpack.config.js**, nesse projeto não tem:  
`npx webpack --config webpack.config.js`  

e usando npm:  
`npm run build`  

o arquivo **package.json** possui a configuração para o npm rodar o webpack:  
```javascript
  "scripts": {
    "build": "webpack"
  },
```

se o webpack for instalado de forma global:  
`npm install webpack -g`  

então é só chamar com:  
`webpack`  

O webpack por padrão não aceita css, e nenhum outro formato a não ser js

Esse projeto só aceita js

Na pasta **dist** está o arquivo **index.html**, ele faz referência ao bundle gerado pelo **Webpack**  
O bundle é gerado na pasta **dist** também.
