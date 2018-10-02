# Introdução


## Cadastro de usuário


| Descrição|
| -- |
|Cadastrar novo usuário no Pinterest|
| **Atores** |
|Usuário não cadastrado|
| **Pré Condições** |
| Usuário não possuir cadastro<br>Usuário possuir conta de e-mail |
| **Fluxo Principal** |
| Usuário não cadastrado abre o aplicativo<br>Usuário seleciona fazer o cadastro [FA1][FA2]<br>Usuário preenche e-mail<br>Usuário preenche senha<br>Usuário preenche confirmação de senha<br>Usuário aperta botão confirmar[FE1][FE2][FE3]|
| **Fluxos Alternativos ** |
| *FA1 - Cadastro por Facebook*<br>Usuário clica no símbolo do Facebook<br>Usuário confirma solicitação do Pinterest ao Facebook<br><br>*FA2 - Cadastro por Gmail*<br>Usuário clica no símbolo do Gmail<br>Usuário confirma solicitação do Pinterest ao Gmail|
| **Fluxos de Exceção**|
| *FE1 - E-mail inexistente*<br>Sistema apresenta mensagem de erro informando que o e-mail é inexistente <br>*FE2 - E-mail já cadastrado*<br>Sistema apresenta mensagem de erro informando que o e-mail já está cadastrado no Pinterest<br>*FE3 - Senha e senha de confirmação diferentes*<br>Sistema apresenta mensagem de erro informando que as duas senhas não são iguais|
| **Pós Condições**|
|Usuário possui conta no Pinterest|

## Comentar em um Pin


## Compartilhar Pasta


## Criar Pasta


## Definir interesses

## Editar um Pin



## Enviar um Pin


## Fazer login




## Ir para a fonte de um Pin


## Organizar Pasta


## Pesquisar por tema


## Pesquisar por foto


## Seguir outro usuário


## Salvar um Pin



## Visualizar Feed


## Visualizar aba Seguindo


## Enviar mensagem para outros usuários

| Descrição|
| -- |
| Enviar mensagens ou pins para outros usuários.|
| **Atores** |
|Usuário cadastrado.|
| **Pré Condições** |
| Usuário possuir conta no Pinterest <br> O usuário deverá estar logado. |
| **Fluxo Principal** |
| FP1 - O usuário loga no Pinterest.<br> FP2 - Após logado é direcionado para o feed. <br> FP3– Acessa a página de mensagens.[FA1] <br> FP4 – O usuário procura por um usuário destinatário.[FE1] <br> FP5 – A mensagem é escrita. <br> FP6 – O botão “Enviar” é clicado.[FE2]|
| **Fluxos Alternativos** |
| *FA1 - Visualizar mensagem*<br>O usuário acessa a página de mensagens. <br> Usuário visualiza as mensagens.<br>|
| **Fluxos de Exceção**|
| *FE1 - Usuário não encontrado*<br>Sistema apresenta mensagem de que não há usuário com o nome pesquisado <br>*FE2 - Mensagem não entregue*<br> Sistema informa que não pode enviar mensagem devido a erro no servidor ou conexão.|
| **Pós Condições**|
|Usuário envia mensagem|

## Receber [notificações


## Classificação de pastas


## Ocultar um Pin


## Denunciar um Pin


## Classificar um Pin como Experimentado

## Sair do aplicativo Pinterest


## Editar Perfil
