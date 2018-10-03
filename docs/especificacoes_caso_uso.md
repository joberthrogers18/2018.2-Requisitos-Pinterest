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
| Usuário seleciona fazer o cadastro [FA1][FA2]<br>Usuário preenche e-mail<br>Usuário preenche senha<br>Usuário preenche confirmação de senha<br>Usuário aperta botão confirmar[FE1][FE2][FE3]|
| **Fluxos Alternativos** |
| *FA1 - Cadastro por Facebook*<br>Usuário clica no símbolo do Facebook<br>Usuário confirma solicitação do Pinterest ao Facebook<br><br>*FA2 - Cadastro por Gmail*<br>Usuário clica no símbolo do Gmail<br>Usuário confirma solicitação do Pinterest ao Gmail|
| **Fluxos de Exceção**|
| *FE1 - E-mail inexistente*<br>Sistema apresenta mensagem de erro informando que o e-mail é inexistente <br><br>*FE2 - E-mail já cadastrado*<br>Sistema apresenta mensagem de erro informando que o e-mail já está cadastrado no Pinterest<br><br>*FE3 - Senha e senha de confirmação diferentes*<br>Sistema apresenta mensagem de erro informando que as duas senhas não são iguais|
| **Pós Condições**|
|Usuário possui conta no Pinterest|

## Visualizar pin

| Descrição|
| -- |
| Ato do usuário visualizar pins de seu interesse.|
| **Atores** |
|Usuário cadastrado e não cadastrados.|
| **Pré Condições** |
| Não há. |
| **Fluxo Principal** |
| O usuário acessa a plataforma do pinterest.<br> Em seguida o feed com os pins são mostrados.<br> Procura por pins de seu interesse.<br> O usuário visualiza o pin.[FA1][FA2][FE1]|
| **Fluxos Alternativos** |
| *FA1 - Visualizar link*<br>Usuário clica no pin.<br>Usuário visita página do pin clicado.<br><br>*FA2 - Comentar pin*<br>Usuário clica no pin escolhido.<br>Usuário comenta no pin.|
| **Fluxos de Exceção**|
| *FE1 - Usuário excluir pin na hora que outro visualiza*<br>Sistema apresenta erro quando um usuário visualiza e ao mesmo momento o criador do pin apaga.|
| **Pós Condições**|
| Usuário visualiza pin. |


## Comentar em um Pin

| Descrição|
| -- |
| Ato do usuário criar um comentário em um pin. |
| **Atores** |
| Usuário cadastrado. |
| **Pré Condições** |
|  Usuário estar logado. |
| **Fluxo Principal** |
| Em qualquer Feed do Pinterest o usuário encontra um Pin compatível com comentários em que deseja comentar. <br> O usuário clica no Pin <br> O usuário clica no botão comentar <br> O usuário escreve seu comentário <br> O usuário posta seu comentário. |
| **Fluxos Alternativos** |
| - |
| **Fluxos de Exceção**|
| *FE1 - Usuário excluir pin na hora que outro está criando um comentário* <br> Sistema apresenta erro quando um usuário comenta e ao mesmo momento o criador do pin o apaga.|
| **Pós Condições**|
| Usuário cria um comentário em um pin. |

## Compartilhar Pasta


## Criar Pasta


## Definir interesses

| Descrição|
| -- |
| Escolher assuntos que são do interesse do usuário |
| **Atores** |
| Usuário cadastrado |
| **Pré Condições** |
| Usuário estar logado |
| **Fluxo Principal** |
| Usuário visualiza página principal<br>Usuário seleciona a aba "Salvos"<br>Usuário aperta aba Interesses<br>Usuário visualiza interesses previamente selecionados[FA]<br>Usuário aperta botão "Adicionar interesses"<br>Usuário procura seus interesses e os seleciona[FE]<br>Usuário aperta "Concluído"|
| **Fluxos Alternativos** |
| *FA1 - Remover interesses previamente selecionados*<br>Usuário visualiza interesse que não quer mais<br>Usuário clica em “Deixar de seguir”|
| **Fluxos de Exceção**|
| *FE1 - Intesse não encontrado*<br>Usuário não encontra seu interesse na lista oferecida pelo app<br>Usuário aperta "Concluído"|
| **Pós Condições**|
| O feed terá conteúdos que estejam de acordo com os interesses do usuário. |


## Editar um Pin



## Enviar um Pin


## Fazer login

| Descrição|
| -- |
|Fazer login na aplicação para obter acesso a todas as ferramentas exclusivas para usuários logados|
| **Atores** |
| Usuário não cadastrado|
| **Pré Condições** |
| O usuário deve ter o aplicativo do Pinterest baixado. <br> O aparelho utilizado para acessar o aplicativo deve estar conectado à internet. <br> O usuário deve ter uma conta de e-mail válida ou uma conta do Facebook ou do Google ativas.|
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

| Descrição|
| -- |
| Seguir um outro Usuário para acompanhar sua atividade no Pinterest. |
| **Atores** |
| Usuário cadastrado. |
| **Pré Condições** |
| Usuário possuir conta no Pinterest. <br> O usuário deverá estar logado. |
| **Fluxo Principal** |
| O usuário clica no nome de outro usuário. <br> A página do pergil do outro usuário é carregada. [FE1] <br> O usuário clica no botão seguir. |
| **Fluxos Alternativos** |
| - |
| **Fluxos de Exceção**|
| *FE1 - Usuário está bloqueado pelo que deseja seguir.*<br> Sistema apresenta mensagem de que não é possível completar a ação pois o outor usuário bloqueou o originatário do pedido.|
| **Pós Condições**|
|Usuário passa a seguri outro usuário. |


## Salvar um Pin



## Visualizar Feed


## Visualizar aba Seguindo


| Descrição|
| -- |
| Ato de visualizar pins de outros usuários que o usuário logado segue. |
| **Atores** |
| Usuário cadastrado. |
| **Pré Condições** |
|  Usuário estar logado. |
| **Fluxo Principal** |
| Usuário abre o app. <br> O usuário clica no ícone da aba Seguindo. <br> O usuário visualiza o conteúdo da aba Seguindo. |
| **Fluxos Alternativos** |
| - |
| **Fluxos de Exceção**|
| - |
| **Pós Condições**|
| Usuário visualizará a aba "Seguindo". |

## Enviar mensagem para outros usuários

| Descrição|
| -- |
| Enviar mensagens ou pins para outros usuários.|
| **Atores** |
|Usuário cadastrado.|
| **Pré Condições** |
| Usuário possuir conta no Pinterest <br> O usuário deverá estar logado. |
| **Fluxo Principal** |
| O usuário loga no Pinterest.<br>Após logado é direcionado para o feed. <br>Acessa a página de mensagens.[FA1] <br>O usuário procura por um usuário destinatário.[FE1] <br> A mensagem é escrita. <br> O botão “Enviar” é clicado.[FE2]|
| **Fluxos Alternativos** |
| *FA1 - Visualizar mensagem*<br>O usuário acessa a página de mensagens. <br> Usuário visualiza as mensagens.<br>|
| **Fluxos de Exceção**|
| *FE1 - Usuário não encontrado*<br>Sistema apresenta mensagem de que não há usuário com o nome pesquisado <br>*FE2 - Mensagem não entregue*<br> Sistema informa que não pode enviar mensagem devido a erro no servidor ou conexão.|
| **Pós Condições**|
|Usuário envia mensagem|

## Receber [notificações


## Classificação de pastas


## Ocultar um Pin

| Descrição|
| -- |
| Ocultar um pin de uma aba do Pinterest para que o usuário não visualize mais determinado conteúdo. |
| **Atores** |
| Usuário cadastrado.|
| **Pré Condições** |
| O usuário deverá estar logado. |
| **Fluxo Principal** |
| Usuário visualiza feed<br>Usuário navega pelo feed[FA1]<br>Usuário seleciona e segura um pin<br>Usuário seleciona item “Ocultar”<br>Pinterest informa que pins com esse tipo de conteúdo não aparecerão mais para o usuário|
| **Fluxos Alternativos** |
| *FA1 - Clicar em um pin*<br>O usuário acessa a página de detalhes do pin <br> Usuário seleciona e segura um pin <br>Usuário seleciona item “Ocultar”<br>Pinterest informa que pins com esse tipo de conteúdo não aparecerão mais para o usuário|
| **Fluxos de Exceção**|
| - |
| **Pós Condições**|
|Usuário envia mensagem|

## Denunciar um Pin


## Classificar um Pin como Experimentado

## Sair do aplicativo Pinterest


## Editar Perfil
