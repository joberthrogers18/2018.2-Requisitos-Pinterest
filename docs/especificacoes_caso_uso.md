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

| Descrição|
| -- |
|Fazer [login](lexicos.md#login) na aplicação para obter acesso a todas as ferramentas exclusivas para [usuários](lexicos.md#usuario) [logados](lexicos.md#logado).|
| **Atores** |
|[Usuário](lexicos.md#usuario) não cadastrado|
| **Pré Condições** |
| O [usuário](lexicos.md#usuario) deve ter o aplicativo do [Pinterest](lexicos.md#pinterest) baixado. <br> O aparelho utilizado para acessar o aplicativo deve estar conectado à internet. <br> O [usuário](lexicos.md#usuario) deve ter uma conta de e-mail válida ou uma conta do Facebook ou do Google ativas.|
| **Fluxo Principal** |
|Usuário abre o app [FA1][FA2] <br> Usuário usa e-mail como forma de login [FA3] <br> Usuário insere a senha <br> O usuário é redirecionado para a página principal da aplicação.|
| **Fluxos Alternativos ** |
| *FA1 - Login com Facebook* <br> Usuário é redirecionado para a página principal <br><br> *FA2 - Login com Google* <br> Usuário é redirecionado para a página principal <br><br> *FA3 - Primeiro acesso com e-mail* <br> Usuário insere nova senha de acesso <br> Usuário é redirecionado para a página principal|
| **Fluxos de Exceção**|
| *FE1 - Senha incorreta* <br><br> *FE2 - Permissão à conta do Facebook negada* <br><br> *FE3 - Permissão à conta do Google negada*|
| **Pós Condições**|
| Conseguir acessar a página principal e outras funcionalidades exclusivas para usuários logados |

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
