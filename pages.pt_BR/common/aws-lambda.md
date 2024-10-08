# aws lambda

> Usa o AWS Lambda, um serviço de computação para executar código sem provisionar nem gerenciar servidores.
> Mais informações: <https://docs.aws.amazon.com/cli/latest/reference/lambda/>.

- Executa uma função:

`aws lambda invoke --function-name {{nome}} {{caminho/para/a/resposta.json}}`

- Executa uma função enviando um payload em formato JSON:

`aws lambda invoke --function-name {{nome}} --payload {{json}} {{caminho/para/a/resposta.json}}`

- Lista as funções:

`aws lambda list-functions`

- Exibe a configuração de uma função:

`aws lambda get-function-configuration --function-name {{nome}}`

- Lista os apelidos de uma função:

`aws lambda list-aliases --function-name {{nome}}`

- Exibe a configuração de concorrência reservada de uma função:

`aws lambda get-function-concurrency --function-name {{nome}}`

- Lista quais serviços AWS pode invocar a função:

`aws lambda get-policy --function-name {{nome}}`
