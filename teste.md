# Testes automatizados

Que a nossa aplicação continue funcionando independente do número de novas funcionalidades e do núme de devs no time.

1. Testes unitários (TDD)

Testam funcionalidades específicos da nossa aplicação (precisam ser funções puras).

JAMAIS: Chamada a uma API e efeito colateral.

2. Testes de integração

Testam uma funcionalidade completa, passando por várias camadas da aplicação.

Route -> Controller -> Serviço - Repositório -> ...

3. Testes E2E

Testes que simulam a ação do usuário dentro da nossa aplicação.

1. Clique no input de email
2. PReencha alcir@softsa.com.br
3. Clique no input de senha
4. Preencha 123456
5. Clique no botão "Logar"
6. Espero que a página tenha enviado o usuário para o dashboard






# TDD (Test Driven Development)

- Quando ele se cadastrar na aplicação, ele deve receber um email de boas-vindas;
