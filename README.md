# Exercicio_MVC

## Nessa seção serão respondidos questões de sala, durante a instrução de computação

### Resposta: Aula 05

Models: É a seção onde será dado comando ao banco de dados, como deletar uma informação de uma tabela, adicionar informação a uma tabela, modificar informações de uma tabela, etc. É comum usar programação assíncrona para garantir que todos os comando sejam utilizados.

Controller: É a parte que cuida do back do site, portanto haverá funções que rodam/chamam os comandos. Como delete, update, etc. Basicamente controlando o fluxo de informações que podem ou não ser comandos do usuário.

Endpoint: É a parte que reúne as informações de todas as outras seções, como: models; controller e views. Além de servir de host para o site. Observação: é muito utilizado o comando require() tanto para chamar funções do node como para chamar os outros arquivos.


### Resposta: Aula 06

1. O Model é utilizado para criar as funções de comando sql.No controller é usado para chamar as funções criadas no Model, como o próprio nome pressupõe, ele controla a api. Por fim, o view é a parte que será vista pelo usuário na web usando html ou ejs.

2. o envio e recebimento de dados ocrroe por meio das requisições http feitas pela api como req.body. Há a rota "GET /alunos" que basicamente exibe as informações do caminho aluno.

3. Facilita a visualização das situações, uma vez que o seu não uso exige outros comando como res.render() para o entendimento, além disso caso não se usasse html seria necessário usar ferramentas como postman para conseguir interagir com o código e interpretá-lo.