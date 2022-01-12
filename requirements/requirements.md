Teste para Desenvolvedor Backend

- [ ] Construir uma Api que fará integração com o facebook para leituras de dados do usuário logado. Não é necessário
  implementar o login do facebook, porém é preciso solicitar um token já autenticado.

- [ ] Implementar um CRUD de accounts onde:

- [ ] Create - solicitar nome, email, senha, token de acesso ao facebook

- [ ] Update - permite atualizar as informações da account, incluindo token.

- [ ] Delete - Permite remover uma account

- [ ] Read - Autenticar com jwt (criar endpoint de login) onde o token ja identifica o usuario logado e traz sua account
  ja consultando o public profile no facebook e retornando num nó “public_profile”

- [ ] Adicionalmente implementar um endpoint que lista todas as accounts criadas (não necessita trazer dados do
  facebook)

- [ ] Geração de tokens do Facebook gerar token
  em https://developers.facebook.com/tools/explorer/?method=GET&path=me&version=v12.0, é preciso criar uma conta
  desenvolvedor e um app no Facebook e adicionar felipec@vendamais.ai como usuário de teste do app.

Tecnologias Pontos de atenção

-[ ] Solicitar permissões no app do Facebook: public_profile Implementação de Dockerfile e docker-composer.yml com o
 banco para uso da api com Docker é um diferencial, caso não implemente enviar dados de acesso a banco de dados. Entrega
-[ ] Publicar num repositório do Github ou Gitlab e dar acesso a felipec@vendamais.ai

curl -i -X GET \
"https://graph.facebook.com/v12.0/me?access_token=EAATZAvfDnezgBACj1ZAhIpWCdbTBgZCWZCZBdkz3NT29gshKG1l000YMPYuZC3ViuNgGmrHfnE5vwKfsWjyGjMaTrcTeWhzU58MZB5ZBeHDirfIYfcZANOvXBKkqnsV7N6ZCJSVUA9DTb2IcvL2WWIKp4JC5w6TG3JWvGmlOBRUxZB6NaoTCKo0o2jLa1cSTxYCg1WyQ5bklZCpp6XjzaSyDY9yWf0jO6O1l5qoZD"
qeqe
