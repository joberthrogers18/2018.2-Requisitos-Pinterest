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

| Descrição|
| -- |
|Alterar descrição e a pasta de um pin.|
| **Atores** |
| Usuário |
| **Pré Condições** |
| O usuário deve ter o aplicativo do Pinterest baixado. <br> O aparelho utilizado para acessar o aplicativo deve estar conectado à internet. |
| **Fluxo Principal** |
|Usuário faz login <br> Usuário clica em Perfil [FA1] <br> Usuário seleciona a aba "pastas" <br> Usuário seleciona uma pasta [FA2] <br> Usuário seleciona um pin <br> Usuário clica em "editar" <br> Usuário faz alterações na descrição e na pasta do pin <br> Usuário clica em "concluir" <br> Usuário é redirecionado para a página de visualização do pin editado.|
| **Fluxos Alternativos** |
| *FA1 - Aba pins* <br> Usuário seleciona a aba "pins" <br> Usuário seleciona um pin <br> Usuário clica em "editar" <br> Usuário faz alterações na descrição e na pasta do pin <br> Usuário clica em "concluir" <br> Usuário é redirecionado para a página de visualização do pin editado. <br><br> *FA2 - Mouse sobre o pin* <br> Usuário passa o mouse sobre o pin <br> Usuário clica em "editar" <br> Usuário faz alterações na descrição e na pasta do pin <br> Usuário clica em "concluir" <br> Usuário é redirecionado para a página de visualização do pin editado.|
| **Fluxos de Exceção**|
| ----- |
| **Pós Condições**|
| As características modificadas serem vistas pelo usuário na descrição do pin. |


## Fazer login

| Descrição|
| -- |
|Fazer login na aplicação para obter acesso a todas as ferramentas exclusivas para usuários logados|
| **Atores** |
| Usuário não cadastrado|
| **Pré Condições** |
| O usuário deve ter o aplicativo do Pinterest baixado. <br> O aparelho utilizado para acessar o aplicativo deve estar conectado à internet. <br> O usuário deve ter uma conta de e-mail válida ou uma conta do Facebook ou do Google ativas.|
| **Fluxo Principal** |
|Usuário entra na página de login [FA1][FE2][FA2][FE3] <br> Usuário usa e-mail como forma de login [FA3] <br> Usuário insere a senha [FE1]<br> O usuário é redirecionado para a página principal da aplicação.|
| **Fluxos Alternativos** |
| *FA1 - Login com Facebook* <br> Usuário é redirecionado para a página principal <br><br> *FA2 - Login com Google* <br> Usuário é redirecionado para a página principal <br><br> *FA3 - Primeiro acesso com e-mail* <br> Usuário insere nova senha de acesso <br> Usuário é redirecionado para a página principal|
| **Fluxos de Exceção**|
| *FE1 - Senha incorreta*<br> Uma mensagem de erro é mostrada para usuário <br> Usuário volta para a página de login <br><br> *FE2 - Permissão à conta do Facebook negada* <br> Uma mensagem de erro é mostrada para usuário <br> Usuário volta para a página de login <br><br> *FE3 - Permissão à conta do Google negada*<br> Uma mensagem de erro é mostrada para usuário <br> Usuário volta para a página de login <br>|
| **Pós Condições**|
| Conseguir acessar a página principal e outras funcionalidades exclusivas para usuários logados |

## Ir para a fonte de um Pin

| Descrição|
| -- |
|Visitar a página web de onde foi tirado um determinado pin.|
| **Atores** |
|Usuário|
| **Pré Condições** |
| O usuário deve ter o aplicativo do Pinterest baixado. <br> O aparelho utilizado para acessar o aplicativo deve estar conectado à internet.|
| **Fluxo Principal** |
|Usuário faz login[FA1] <br> Usuário seleciona um pin <br> Usuário clica no link para a fonte do site <br> Usuário é redirecionado para o site|
| **Fluxos Alternativos** |
| *FA1 - Link direto* <br> Usuário passa o mouse sobre o pin <br> Usuário clica sobre o link fonte <br> Usuário é redirecionado para uma página|
| **Fluxos de Exceção**|
| ----- |
| **Pós Condições**|
| Estar na página na qual está o pin. |

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
| *FE1 - Usuário não encontrado*<br>Sistema apresenta mensagem de que não há usuário com o nome pesquisado <br><br>*FE2 - Mensagem não entregue*<br> Sistema informa que não pode enviar mensagem devido a erro no servidor ou conexão.|
| **Pós Condições**|
|Usuário envia mensagem|

## Ocultar um Pin

| Descrição |
| -- |
| Ocultar um pin de uma aba do Pinterest para que o usuário não visualize mais determinado conteúdo. |
| **Atores** |
| Usuário. |
| **Pré Condições** |
|  usuário deverá estar logado em sua conta do Pinterest . |
| **Fluxo Principal** |
| Usuário abre o aplicativo <br>Usuário entra na página inicial para visualizar e navegar pelo feed de repleto de pins<br> Usuário seleciona um Pin<br> Usuário clica no botão Ocultar<br>Pinterest informa que pins com esse tipo de conteúdo não aparecerão mais para o usuário |
| **Fluxos Alternativos** |
| - |
| **Fluxos de Exceção**|
| - |
| **Pós Condições**|
| Usuário oculta o pin. |

## Salvar um Pin

| Descrição |
| -- |
| Salvar um Pin do Pinterest |
| **Atores** |
| Usuário do Pinterest |
| **Pré Condições** |
| Usuário possuir cadastro no Pinterest <br> Usuário ter efetuado seu primeiro login <br> Usuário ter escolhido seus interesses <br> Usuário ter conexão de internet |
| **Fluxo Principal** |
| Usuário abre o Pinterest <br> Usuário efetua Login no Pinterest [FA1] <br> Usuário acessa Página Principal [FA2] <br>Usuário visualiza Feed <br>Usuário visualiza um Pin <br>Usuário clica para Salvar o Pin <br> Usuário cria uma pasta para salvar um Pin [FA3] <br>Usuário escolhe o nome da pasta <br> Usuário salva o Pin na pasta |
| **Fluxos Alternativos** |
|  *FA1 - Usuário efetuar primeiro login na aplicação* <br>  Usuário escolhe no mínimo cinco categorias de interesses <br> Usuário acessa Página Inicial <br>  Continua o Fluxo Principal a partir do 4 <br><br>  *FA2 - Usuário pesquisa por conteúdo específico* <br> Usuário visualiza um Pin <br>Continua o Fluxo Principal a partir do 6 <br><br> *FA3 - Usuário salva Pin em uma pasta já criada* <br>|
| **Fluxos de Exceção**|
| - |
| **Pós Condições**|
| Usuário salva Pin em uma pasta do Pinterest |

## Enviar um Pin

| Descrição |
| -- |
| Enviar um Pin do Pinterest |
| **Atores** |
| Usuário do Pinterest |
| **Pré Condições** |
| Usuário possuir cadastro no Pinterest <br> Usuário ter efetuado seu primeiro login <br> Usuário ter escolhido seus interesses <br> Usuário ter conexão de internet |
| **Fluxo Principal** |
| Usuário abre o Pinterest <br> Usuário efetua Login no Pinterest [FA1] <br> Usuário acessa Página Principal [FA2] <br>  Usuário visualiza Feed <br> Usuário visualiza um Pin <br> Usuário clica para Enviar o Pin <br> Usuário escolhe para que amigo do Pinterest quer enviar o Pin [FA3][FA4][FA5] <br> Usuário envia o Pin [FA6] |
| **Fluxos Alternativos** |
| *FA01 - Usuário efetuar primeiro login na aplicação* <br> Usuário escolhe no mínimo cinco categorias de interesses <br> Usuário acessa Página Inicial <br>  Continua o Fluxo Principal a partir do 4 <br><br> *FA2 - Usuário pesquisa por conteúdo específico* <br> Usuário visualiza um Pin <br>  Continua o Fluxo Principal a partir do 6 <br><br> *FA3 - Usuário copia o link do Pin para enviar por e-mail, SMS ou outra plataforma* <br><br> *FA4 - Usuário compartilha o link do Pin para o Facebook* <br><br>*FA5 - Usuário envia o link do Pin para um contato do WhatsApp* <br><br> *FA6 - Usuário escreve uma mensagem para enviar junto ao Pin para um usuário do Pinterest* <br> Usuário envia o Pin |
| **Fluxos de Exceção**|
| - |
| **Pós Condições**|
| Usuário envia o Pin para outra pessoa |

## Realizar primeiro login

| Descrição |
| -- |
| Realizar primeiro login no Pinterest |
| **Atores** |
| Usuário recém cadastrado no Pinterest |
| **Pré Condições** |
| Usuário possuir cadastro no Pinterest <br> Usuário não ter efetuado seu primeiro login <br> Usuário ter conexão de internet |
| **Fluxo Principal** |
| Usuário abre o Pinterest <br>Usuário efetua o primeiro Login no Pinterest <br> Usuário escolhe no mínimo cinco categorias de interesses [FA01] <br> Usuário acessa página principal [FA02][FA03][FA04] <br>  Usuário visualiza Feed <br> Usuário visiualiza um Pin |
| **Fluxos Alternativos** |
| *FA01 - Usuário faz o tutorial para aprender as funcionalidades do Pinterest* <br>  Usuário escolhe no mínimo cinco categorias de interesses <br> Continua o fluxo principal a partir do 4 <br><br> *FA02 - Usuário procura pessoas para seguir no Pinterest* <br><br> *FA03 Usuário procura por conteúdos específicos no Pinterest* <br><br> *FA04 - Usuário procura mais interesses para seguir* |
| **Pós Condições**|
| Usuário efetua primeiro login no Pinterest |

## Sair do aplicativo Pinterest

| Descrição |
| -- |
| O usuário sair de sua conta no pinterest caso esteja logado. |
| **Atores** |
| Usuário. |
| **Pré Condições** |
|  O usuário está logado. |
| **Fluxo Principal** |
| O usuário abre o aplicativo. <br>  acessa a aba de salvo.[FA1] <br> O usuário seleciona o ícone de engrenagem na parte superior direita.<br> Seleciona a opção sair.[FA2]<br>É redirecionado para a página de login.|
| **Fluxos Alternativos** |
| *FA1 - O usuário pode permanecer no feed.* <br><br> *FA2 – O usuário pode permanecer na aba salvos e escolher outra opção.*|
| **Fluxos de Exceção**|
| - |
| **Pós Condições**|
| O usuário deslogado. |


## Denunciar um Pin

| Descrição |
| -- |
| Denunciar um pin presente em uma aba do Pinterest. |
| **Atores** |
| Usuário. |
| **Pré Condições** |
| O usuário deverá estar logado em sua conta do Pinterest<br>O usuário deverá encontrar um pin com conteúdo que julga como impróprio. |
| **Fluxo Principal** |
| Usuário abre o aplicativo<br>Usuário entra na página inicial para visualizar e navegar pelo feed repleto de de pins<br>  Usuário encontra um pin com conteúdo impróprio<br>  Usuário seleciona um Pin<br>Usuário clica no botão Mais<br> Usuário clica no botão Denunciar<br> Pinterest informa que pins com esse tipo de conteúdo não aparecerão mais para o usuário<br>Comunidade do Pinterest avalia o conteúdo do pin denunciado e remove o conteúdo do aplicativo. |
| **Fluxos Alternativos** |
| - |
| **Fluxos de Exceção**|
| - |
| **Pós Condições**|
| O usuário deslogado. |


## Classificar um Pin como Experimentado
| Descrição |
| -- |
| Experimentar o conteúdo de um pin e classificá-lo na aba do Pinterest de Experimentados |
| **Atores** |
| Usuário |
| **Pré Condições** |
| Usuário logado<br>Usuário ter pins salvos<br>Câmera  |
| **Fluxo Principal** |
|  Usuário entra na Aba Salvos<br>Usuário seleciona a opção Experimentados<br>Pinterest apresenta em lista os pins salvos pelo usuário<br>Usuário seleciona a opção adicionar pin<br>Usuário tira foto do pin experimentado[FA]<br>Usuário seleciona a opção Concluído |
| **Fluxos Alternativos** |
|  *FA1 - Adicionar Notas*<br>Usuário adiciona nota à foto tirada<br>Usuário seleciona a opção Concluído  |
| **Fluxos de Exceção**|
| -  |
| **Pós Condições**|
|  O pin ficará salvo na aba Experimentar do Pinterest junto com uma foto do que foi experimentado.|

## Editar Perfil
| Descrição |
| -- |
| O usuário editar seu perfil com suas informações, podendo adionar novas ou mudá-las. |
| **Atores** |
| Usuário. |
| **Pré Condições** |
|  O usuário possuir uma conta no Pinterest. |
| **Fluxo Principal** |
| O usuário clica no ícone de "Reticências" na tela e vai até a seção de edição de perfil. |
| **Fluxos Alternativos** |
| *FA1* – O usuário pode mudar seu nome e/ou sobrenome. <br> *FA2* – O usuário pode mudar/adicionar sua foto de perfil. <br> *FA3* – O usuário pode mudar/adicionar seu username. <br> *FA4* – O usuário pode mudar/adicionar uma descrição sobre ele. <br> *FA5* – O usuário pode mudar/adicionar sua localização. <br> *FA6* – O usuário pode mudar/adicionar seu Website. |
| **Fluxos de Exceção**|
| *FE1* – Não salvar as alterações. |
| **Pós Condições**|
| Alteração ou adição de informações no perfil do usuário. |


## Visualizar Feed
| Descrição |
| -- |
|  Visualizar pins de interesse do usuário pelo feed|
| **Atores** |
| Usuário |
| **Pré Condições** |
|  Usuário logado<br>Usuário ter definido ao menos um interesse |
| **Fluxo Principal** |
|  Usuário seleciona aba “Página Inicial”<br>Usuário navega pelo feed de pins[FA1]<br>Usuário pesquisa pins de seu interesse<br>Usuário vizualiza o pin|
| **Fluxos Alternativos** |
| *FA1 - Mudança de aba* <br> Usuário tem a possibilidade de mudar para qualquer outra aba que não seja a do feed.|
| **Fluxos de Exceção**|
| -  |
| **Pós Condições**|
| O usuário visualizará o conteúdo oferecido pelo Pinterest |

## Receber Notificações
| Descrição |
| -- |
| O usuário recebe notificações de pins relacionados aos seus e pins salvos por amigos. |
| **Atores** |
| Usuário. |
| **Pré Condições** |
|  Seguir usuários ou ter pins salvos. |
| **Fluxo Principal** |
| Estar na tela inicial do aplicativo e ter um alerta no ícone de "notificações", então o usuário poder clicar e ver suas novas notificações. |
| **Fluxos Alternativos** |
| *FA1* – O usuário pode salvar novos pins indicados. <br> *FA2* – O usuário pode salvar pins salvos por outros amigos. <br> *FA3* – O usuário pode desabilitar opção de notificação por email. |
| **Fluxos de Exceção**|
| *FE1* – Não estar seguindo outros usuários e não ter nenhum pin salvo  |
| **Pós Condições**|
| O usuário é notificado sobre qualquer interação de novos pins ou usuários seguidos. |


## Classificação de pastas
| Descrição |
| -- |
| O usuário escolhe a forma que quer ordenar suas pastas. |
| **Atores** |
| Usuário. |
| **Pré Condições** |
|  Ter uma ou mais pastas . |
| **Fluxo Principal** |
| Ir até a página de perfil e estar na opção de "boards" . |
| **Fluxos Alternativos** |
| *FA1* – O usuário pode classificar por ordem alfabética. <br> *FA2* – O usuário pode classificar por "Salvo pela última vez". <br> *FA3* – O usuário pode classificar por "mais recentes" <br> *FA4* – O usuário pode classificar por "mais antigas" <br> *FA5* – O usuário pode classificar por "igual à Web" . |
| **Fluxos de Exceção**|
| - |
| **Pós Condições**|
| As pastas do usuário estarão ordenadas de acordo com a opção escolhida por ele. |


## Organizar Pasta
| Descrição |
| -- |
| Realocar pins em pastas ou subpastas e excluir pins |
| **Atores** |
| Usuário |
| **Pré Condições** |
| Usuário logado<br>O usuário deve possuir pins na pasta a ser organizada ou na subpasta a ser organizada  |
| **Fluxo Principal** |
|  Usuário seleciona aba “Salvos”<br>Usuário seleciona aba “Pastas”<br>Usuário seleciona uma pasta<br>Usuário clica em “Organizar”<br>Usuário seleciona pins para organizar<br>Usuário clica em “Avançar”[FA]<br>Usuário seleciona outra Pasta<br>Pinterest informa que pin foi movido |
| **Fluxos Alternativos** |
| *FA1 - Adicionar subpasta*<br>Usuário seleciona “Adicionar subpasta”<br>Usuário adiciona nome para nova subpasta<br>Usuário seleciona “Concluído” |
| **Fluxos de Exceção**|
| -  |
| **Pós Condições**|
| O usuário visualizará o conteúdo oferecido pelo Pinterest |


## Pesquisar por tema

| Descrição|
| -- |
| Encontrar imagens referentes a um tema de preferência do usuário. |
| **Atores** |
| Usuário |
| **Pré Condições** |
| Usuário ter em mente palavras-chaves relativas ao tema. |
| **Fluxo Principal** |
| Usuário abre o aplicativo <br>   Usuário escreve palavras relacionadas ao tema desejado na barra de pesquisa <br> Usuário clica "enter"<br>Aplicativo mostra uma seleção de imagens referentes ao tema<br>   Aplictivo mostra uma seleção de palavras relacionadas ao tema que direcione para pesquisas específicas|
|**Fluxos Alternativo**|
| **FA1** - Sugerir palavras chaves relacionadas.|
| **Fluxos de Exceção**|
| **FE1** - Palavras que coincidirem com outros temas. |
| **Pós Condições**|
| O usuário encontrará uma página repleta de pins de acordo com a temática desejada.  |

## Pesquisar por foto
| Descrição|
| -- |
| Utilizar uma imagem como base de pesquisa para encontrar pins semelhantes. |
| **Atores** |
| Usuário <br> Imagens semelhantes |
| **Pré Condições** |
| Usuário possuir conta no Pinterest <br> Usuário ter acesso ao aplicativo mobile <br> Usuário possuir celular com câmera |
| **Fluxo Principal** |
|Usuário acessa o aplicativo pelo celular; <br>  Abre a Página Inicial para o usuário; <br> Usuário seleciona o símbolo de Câmera na barra de pesquisa **[FA1]** ; <br>  Usuário tira foto da imagem que quer pesquisar; <br>  Imagens semelhantes são retornadas ao usuário **[FE1]** ; <br>  O Processo é finalizado com sucesso. |
| **Fluxos Alternativos** |
| **FA1** - Selecionar Imagem da Galeria <br> O Usuário acessa a galeria do celular; <br>  Usuário seleciona imagem de base para a pesquisa de pins; <br> Imagens semelhantes são retornadas ao usuário.|
| **Fluxos de Exceção**|
| **FE1** - Pins Retornados Não São Semelhantes <br> Imagens de Pins retornados não correspondem ao tema da imagem enviada;  <br> O Processo é finalizado.<br><br>  |
| **Pós Condições**|
| São retornadas imagens de Pins semelhantes à imagem usada para pesquisa pelo usuário.  |


## Compartilhar Pasta
| Descrição|
| -- |
| Permitir que um outro usuário possa editar uma pasta, adicionando e removendo pins ou criando subpastas. |
| **Atores** |
| Usuário <br> Usuário Convidado a Compartilhar Pasta |
| **Pré Condições** |
| Usuário possuir conta no Pinterest <br> Usuário Convidado possuir conta no Pinterest <br> Usuário possuir uma pasta |
| **Fluxo Principal** |
|Usuário acessa seu perfil no aplicativo; <br> Aparecem várias opções, como acessar pastas já criadas ou criar uma pasta; <br>  Usuário seleciona a pasta; <br> Usuário seleciona ícone de compartilhar pasta; <br> Usuário escolhe os outros usuários com quem compartilhar a pasta nas opções mostradas. **[FA1]** ; <br>  Usuário envia convites de compartilhamento; <br>  O Convidado a compartilhar aceita o convite. **[FE1]**; <br>  O Processo é finalizado com sucesso. |
| **Fluxos Alternativos** |
| **FA1** - Procurar por usuários <br> O Usuário acessa a barra de pesquisa na função de compartilhar pasta; <br> Usuário digita nome do outro usuário com quem vai compartilhar a pasta; <br>  Usuário seleciona a opção de escolher pasta, se já tiver pastas; <br> Usuário escolhe a opção de "Criar Pasta" <br>  Usuário envia convites de compartilhamento; <br>  O Convidado a compartilhar aceita o convite. **[FE1]**; <br>  O Processo é finalizado com sucesso. |
| **Fluxos de Exceção**|
| **FE1** - Usuário Recusa o Convite<br> O Usuário convidado recusa o convite;  <br>  O Processo é finalizado com sucesso. <br><br>  |
| **Pós Condições**|
| O Usuário Convidado agora pode modificar a pasta compartilhada.  |

## Criar Pasta

| Descrição|
| -- |
| Criar uma pasta para guardar os pins conforme desejo do usuário |
| **Atores** |
| Usuário |
| **Pré Condições** |
| Usuário possuir conta no Pinterest |
| **Fluxo Principal** |
| Usuário acessa seu perfil no aplicativo. **[FA1]** ; <br> Aparecem várias opções, como acessar pastas já criadas ou criar uma pasta; <br>  Usuário seleciona a opção "Criar Pasta". <br>  Surge uma caixa na tela, pedindo para que o usuário insira o nome de sua pasta e demais informações; <br>  Usuário insere o nome da pasta. **[FA2][FA3]** ; <br>  Usuário escolhe a opção "Criar". **[FE1]** ; <br>  O Processo é finalizado com sucesso. |
| **Fluxos Alternativos** |
| **FA1** - Criar Pasta ao Salvar Pin <br>  O Usuário acessa a página inicial; <br>  Usuário escolhe um Pin de seu interesse para salvar; <br> Usuário seleciona a opção de escolher pasta, se já tiver pastas; <br> Usuário escolhe a opção de "Criar Pasta" <br>  Usuário preenche o nome da nova pasta **[FA2][FA3]** ; <br>  Usuário seleciona a opção "Criar" **[FE1]** ; <br> O Processo é finalizado com sucesso. <br><br> **FA2** - Tornar a Pasta Secreta <br> O Usuário Ativa a opção de tornar a pasta secreta;  <br>  Usuário seleciona a opção  "Criar" **[FE1]** ; <br>  O Processo é finalizado com sucesso. <br><br> **FA3** - Compartilhar a Pasta ao Criar <br> O Usuário seleciona outros usuários com quem compartilhar a Pasta que será criada; <br> Os Convites de compartilhamento são enviados; <br> Usuário seleciona a opção  "Criar" **[FE1]**; <br>  O Processo é finalizado com sucesso.<br><br> |
| **Fluxos de Exceção**|
|  **FE1** - Nome de Pasta já existente <br> O Usuário insere um nome de uma pasta já existente; <br> O Programa não valida e informa o usuário de que aquele nome já foi utilizado; <br>  Usuário seleciona um novo nome para a pasta; <br>   Usuário seleciona a opção "Criar" **[FE1]** ; <br>  O Processo é finalizado com sucesso. |
| **Pós Condições**|
| O Usuário possui uma nova pasta para salvar seus pins. |
