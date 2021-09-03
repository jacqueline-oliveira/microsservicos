# microsservicos
Projeto feito em aula para demonstrar o uso do Feign Client e do Hystrix

Nesse exemplo, utilizamos o Feign Client para fazer uma requisição GET a um endpoint do microsserviço animais-ms, retornando os animais de um determinado dono, informado por id.

Caso o serviço não esteja ativo, o Hystrix (circuit breaker) retorna uma lista vazia como resposta alternativa.
