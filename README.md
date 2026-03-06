# nuvem-semana3-Vitor-Bombardelli

Iniciei o projeto criando os arquivos: `index.html`,`style.css` e `script.js` com os códigos fornecido no Google Classroom.

Após isso, testei as funcionalidades básicas. As requisições GET e POST foram implementadas e funcionaram.

Depois integrei a função de buscar o clima das cidades, porém tive o segunte erro:
"Uncaught SyntaxError: Unexpected token 'catch'"

Observei o código e com auxílio  percebemos que a estrutura que coloquei as funções estava incorreta e também tinha um erro de sintaxe na função `show`.

Arrumei as posições de cada seção do código, e em seguida testei.
Mesmo após corrigir os erros o botão "Buscar clima" por cidade ainda não estava respondendo e nada aparecia no console.
Imaginei que talvez o navegador não estivesse carregando as alterações e então fechei as abas e as abri novamente, após executar o pages, tudo funcionou.

GET e POST estão funcionando, e a função de busca também, testei com Toledo e Assis Chateaubriand.
A busca de clima por cidade esta funcionando, retornando os dados por cidade.
As APIs utilizadas foram geocoding e forecast.
