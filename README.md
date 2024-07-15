Teste da API pública Viacep.

Serão realizados dois testes funcionais em nível de sistema segundo o GHERKIN com base na documentação da API. Os testes serão realizados com Cypress Documentação da API: ViaCEP - Webservice CEP e IBGE gratuito

Caso de teste 1: URL: viacep.com.br/ws/01001000/json Cenário: Confirmar a obtenção do endereço através de uma requisição GET dado que o usuário tem acesso a API quando o CEP é informado então o Status da requisição deve ser 200 OK.

Caso de teste 2: URL: viacep.com.br/ws/010010001/json Cenário: Confirmar a não obtenção do endereço através de uma requisição GET dado que o usuário tem acesso a API quando o CEP é informado tem 9 caracteres então o Status da requisição deve ser 400 Bad Request.

Caso de teste 3: URL: viacep.com.br/ws/0100100T/json Cenário: Confirmar a não obtenção do endereço através de uma requisição GET dado que o usuário tem acesso a API quando o CEP é informado tem 8 caracteres sendo o último uma letra ‘’t’’ então o Status da requisição deve ser 400 Bad Request.

Parecer técnico: A API foi aprovada com sucesso, o serviço passou em todos os testes propostos.
