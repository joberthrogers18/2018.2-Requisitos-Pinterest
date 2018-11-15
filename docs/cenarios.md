# Introdução

 A Técnica de modelagem por cenários consiste na elaboração de estruturas narrativas visando a construção de um contexto cujas informações permitam compreender ações desempenhadas no software, bem como os diversos fatores que influenciam essas ações, como o contexto, os recursos, elementos atuantes e etc. Essa técnica proporciona ainda uma forma de contextualização das funcionalidades desempenhadas em diferentes contextos de utilização do software analisado, trazendo elementos que auxiliam na compreensão da ideia abordada, permitindo uma forma direta de descrição.

# Cenários

## Cadastro de [usuário](lexicos.md#l14)

|**Objetivo** |
|--|
| Cadastrar novo usuário no Pinterest |
|**Contexto** |
| Local: Página inicial do app [Pinterest](lexicos.md#l9) (quando não logado) <br>  Pré-Condição: não ter cadastro <br>  Pós-Condição: [usuário](lexicos.md#l14) cadastrado  |
|**Atores** |
| [Usuário](lexicos.md#l14) não cadastrado|
|**Recursos** |
| Internet, aplicativo, conta de e-mail|
|**Restrição**|
|O [usuário](lexicos.md#l14) ter conta do facebook <br>  O [usuário](lexicos.md#l14) ter conta no Google|
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) <br> Senha inválida <br> E-mail inválido <br> Gmail ou Facebook fora do ar <br> Conta de Gmail ou Facebook inexistente |
|**Episódios** |
| [Usuário](lexicos.md#l14) não cadastrado abre o aplicativo <br> [Usuário](lexicos.md#l14) seleciona fazer o cadastro <br>  Se o [usuário](lexicos.md#l14) tiver conta no Gmail , então selecionar cadastro pelo Gmail  <br> Se o [usuário](lexicos.md#l14) tiver conta no Facebook , então selecionar cadastro pelo Facebook <br> Senão [usuário](lexicos.md#l14) preenche e-mail, senha e confirmação da senha <br>[Usuário](lexicos.md#l14) confirma cadastro no e-mail e é redirecionado para a página principal do [Pinterest](lexicos.md#l9)|

## Comentar em um [Pin](lexicos.md#l1)

|**Objetivo** |
|--|
| Criar comentário em um [Pin](lexicos.md#l1) |
|**Contexto** |
| Local: Página de detalhes de um [pin](lexicos.md#l1) <br>  Pré-Condição: o [usuário](lexicos.md#l14) deve estar autenticado em sua conta  <br>  Pós-Condição: [usuário](lexicos.md#l14) comentou e interagiu com o [pin](lexicos.md#l1) de outro [usuário](lexicos.md#l14)|
|**Atores** |
| [Usuário](lexicos.md#l14) |
|**Recursos** |
| Internet, aplicativo, conta de e-mail, [pin](lexicos.md#l1) |
|**Restrição**|
| - |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) <br> [Pin](lexicos.md#l1) ser apagado enquanto comentário é escrito |
|**Episódios** |
| [Usuário](lexicos.md#l14) abre o aplicativo <br> [Usuário](lexicos.md#l14) seleciona o [Pin](lexicos.md#l1) em que deseja comentar <br> [Usuário](lexicos.md#l14) escreve seu comentário <br> [Usuário](lexicos.md#l14) envia comentário |

## Compartilhar [Pasta](lexicos.md#l3)

|Objetivo |
|--|
| Permitir que um ou mais [usuários](lexicos.md#l14) tenham acesso a uma [pasta](lexicos.md#l3), podendo editar os [Pins](lexicos.md#l1) existentes e adicionar novos. |
|**Contexto** |
| Local: [Página](lexicos.md#l7) da [pasta](lexicos.md#l3) a ser [compartilhada](lexicos.md#l12) <br> Tempo: A qualquer momento  <br> Pré-Condição: O [Usuário](lexicos.md#l14) com quem a [pasta](lexicos.md#l3) será compartilhada deverá possuir ou criar uma nova conta no Pinterest. <br>  Pós-Condição: Outro [usuário](lexicos.md#l14) tem acesso ao conteúdo da [pasta](lexicos.md#l3) compartilhada, podendo [organizar](lexicos.md#l33) os [Pins](lexicos.md#l1) dessa [pasta](lexicos.md#l3).|
|**Atores** |
| [Usuário](lexicos.md#l14) proprietário da [pasta](lexicos.md#l3) <br> [Usuário](lexicos.md#l14) com quem a [pasta](lexicos.md#l3) será [compartilhada](lexicos.md#l12)|
|**Recursos** |
| Internet <br> Conta no aplicativo <br>  [Pasta](lexicos.md#l3) <br>  |
|**Restrição**|
| O [usuário](lexicos.md#l14) [seguir outro usuário](#seguir-outro-usuario). |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) <br> [Usuário](lexicos.md#l14) ter sido bloqueado pelo outro <br> [Usuário](lexicos.md#l14) recusar o [convite](lexicos.md#convite) para [colaborar](lexicos.md#l26) |
|**Episódios** |
| [Usuário](lexicos.md#l14) abre o aplicativo <br> [Usuário](lexicos.md#l14) navega até a [pasta](lexicos.md#l3) <br> [Usuário](lexicos.md#l14) seleciona a opção de [compartilhar](lexicos.md#l12) <br> [Usuário](lexicos.md#l14) escolhe o outro [usuário](lexicos.md#l14) com quem compartilhar <br> [Usuário](lexicos.md#l14) envia o [convite](lexicos.md#convite) para [colaboração](lexicos.md#l26) |

## Criar [Pasta](lexicos.md#l3)

|Objetivo |
|--|
| Criar um local para guardar [pins](lexicos.md#l1) de um mesmo tema de escolha do [usuário](lexicos.md#l14)|
|**Contexto** |
| Local: [Página](lexicos.md#l7) de [perfil](lexicos.md#l17) <br> Tempo: A qualquer momento  <br> Pré-Condição:  [Usuário](lexicos.md#l14) possuir [conta](lexicos.md#conta) no aplicativo. <br>  Pós-Condição: O [usuário](lexicos.md#l14) agora contém uma [pasta](lexicos.md#l3) para guardar seus [pins](lexicos.md#l1) de acordo com a classificação desejada.|
|**Atores** |
| [Usuário](lexicos.md#l14) |
|**Recursos** |
| Internet <br> Conta no aplicativo |
|**Restrição**|
| - |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) <br> [Usuário](lexicos.md#l14) ter sido bloqueado pelo outro  |
|**Episódios** |
| [Usuário](lexicos.md#l14) abre o aplicativo <br> [Usuário](lexicos.md#l14) navega até seu [perfil](lexicos.md#l17) <br> [Usuário](lexicos.md#l14) seleciona a opção de criar nova [pasta](lexicos.md#l3) <br> [Usuário](lexicos.md#l14) digita o nome que deseja dar à [pasta](lexicos.md#l3) <br> [Usuário](lexicos.md#l14) escolhe se torna a [pasta](lexicos.md#l3) [secreta](lexicos.md#pastaPrivada) ou não <br> [Usuário](lexicos.md#l14) seleciona a opção criar <br> **Ou** <br> [Usuário](lexicos.md#l14) abre o aplicativo <br> [Usuário](lexicos.md#l14) seleciona um [pins](lexicos.md#l1) da página inicial <br> [Usuário](lexicos.md#l14) seleciona a opção de [salvar](lexicos.md#salvar) [pin](lexicos.md#l1)  <br> [Usuário](lexicos.md#l14) digita o nome que deseja dar à [pasta](lexicos.md#l3) <br> [Usuário](lexicos.md#l14) escolhe a opção de criar [pasta](lexicos.md#l3) <br> [Usuário](lexicos.md#l14) digita o nome que deseja dar à [pasta](lexicos.md#l3) <br> [Usuário](lexicos.md#l14) escolhe se torna a [pasta](lexicos.md#l3) [secreta](lexicos.md#pastaPrivada) ou não <br> [Usuário](lexicos.md#l14) seleciona a opção criar <br> |

## Definir [interesses](lexicos.md#l10)

|**Objetivo** |
|--|
| Escolher assuntos que são do [interesse](lexicos.md#l10) do [usuário](lexicos.md#l14) |
|**Contexto** |
| Local: Logo após o cadastro ou na aba de [interesses](lexicos.md#l10) dentro da aba salvo <br>  Pré-Condição: estar [logado](lexicos.md#l6) <br>  Pós-Condição: [usuário](lexicos.md#l14) recebe [pins](lexicos.md#l1) que são do seu [interesse](lexicos.md#l10) no seu [feed](lexicos.md#l15)|
|**Atores** |
| [Usuário](lexicos.md#l14) |
|**Recursos** |
| Internet, aplicativo, [conta de usuário](lexicos.md#l32) |
|**Restrição**|
| - |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) <br> [Pinterest](lexicos.md#l9) não oferecer o interesse que o [usuário](lexicos.md#l14) procura |
|**Episódios** |
| [Usuário](lexicos.md#l14) abre o aplicativo <br>[Usuário](lexicos.md#l14) visualiza página principal <br> [Usuário](lexicos.md#l14) seleciona a aba "Salvos" <br> [Usuário](lexicos.md#l14) aperta botão [interesses](lexicos.md#l10) <br> [Usuário](lexicos.md#l14) aperta botão "Adicionar [interesses](lexicos.md#l10)" <br> [Usuário](lexicos.md#l14) procura seus [interesses](lexicos.md#l10) e os seleciona <br> [Usuário](lexicos.md#l14) aperta "Concluído" |

## Editar um [Pin](lexicos.md#l1)

|**Objetivo** |
|--|
| Modificar um [pin](lexicos.md#l1) de acordo com a necessidade e desejo do dono da [conta](lexicos.md#l17)|
|**Contexto** |
| Local: [Página](lexicos.md#página) de perfil do [usuário](lexicos.md#l14) <br>  Pré-Condição: Conexão com a internet <br> Ter [pinado](lexicos.md#pinado), pelo menos, um [pin](lexicos.md#l1) <br> O [usuário](lexicos.md#l14) deve estar [autenticado](lexicos.md#l6) em sua [conta](lexicos.md#conta) <br>  Pós-Condição: O [usuário](lexicos.md#l14) contém um [pin](lexicos.md#l1) personalizado de acordo com seu interesse.|
|**Atores** |
| [Usuário](lexicos.md#l14) |
|**Recursos** |
| Internet, aplicativo, [pin](lexicos.md#l1)|
|**Restrição**|
| - |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20)
|**Episódios** |
| [Fazer login](#fazer-login) <br> [Usuário](lexicos.md#l14) clica em sua página de [perfil](lexicos.md#l17) no canto superior direito da tela <br> [Usuário](lexicos.md#l14) seleciona a aba [Pins](lexicos.md#l1) <br> [Usuário](lexicos.md#l14) seleciona o [pin](lexicos.md#l1) que deseja editar <br> [Usuário](lexicos.md#l14) clica no ícone de editar simbolizado por um lápis no canto superior esquerdo da tela. <br> **ou** <br> [Fazer login](#fazer-login) <br> [Usuário](lexicos.md#l14) clica em sua página de [perfil](lexicos.md#l17) no canto superior direito da tela <br> [Usuário](lexicos.md#l14) seleciona a aba [Pins](lexicos.md#l1) <br> [Usuário](lexicos.md#l14) passa o mouse sobre o [pin](lexicos.md#l1) que deseja editar <br> [Usuário](lexicos.md#l14) clica no ícone de editar simbolizado por um lápis na parte superior do [pin](lexicos.md#l1). <br> **ou** <br> [Fazer login](#fazer-login) <br> [Usuário](lexicos.md#l14) clica em sua página de [perfil](lexicos.md#l17) no canto superior direito da tela <br> [Usuário](lexicos.md#l14) seleciona a [aba](lexicos.md#l7) Pastas <br> [Usuário](lexicos.md#l14) clica na pasta que está o [pin](lexicos.md#l1) que deseja editar <br> [Usuário](lexicos.md#l14) passa o mouse sobre o [pin](lexicos.md#l1) que deseja editar <br> [Usuário](lexicos.md#l14) clica no ícone de editar simbolizado por um lápis na parte superior do [pin](lexicos.md#l1). <br> **ou** <br> [Fazer login](#fazer-login) <br> [Usuário](lexicos.md#l14) clica em sua página de [perfil](lexicos.md#l17) no canto superior direito da tela <br> [Usuário](lexicos.md#l14) seleciona a [aba](lexicos.md#l7) "pastas" <br> [Usuário](lexicos.md#l14) clica na [pasta](lexicos.md#l3) que está o [pin](lexicos.md#l1) que deseja [editar](lexicos.md#editar) <br> [Usuário](lexicos.md#l14) seleciona o [pin](lexicos.md#l1) que deseja [editar](lexicos.md#l1) <br> [Usuário](lexicos.md#l14) clica no ícone de [editar](lexicos.md#editar) simbolizado por um lápis no canto superior esquerdo da tela.|

## Enviar um [Pin](lexicos.md#l1)

|**Objetivo** |
|--|
| Enviar um [Pin](lexicos.md#l1) para outro [usuário](lexicos.md#l14) do [Pinterest](lexicos.md#l9) por meio de chat ou enviá-lo para outras pessoas que não utilizam o [Pinterest](lexicos.md#l9) por meio de outras redes sociais (WhatsApp, Facebook) ou até por SMS e e-mail |
|**Contexto** |
| Local: Página de detalhes de um [Pin](lexicos.md#l1) <br>  Pré-Condição: O [usuário](lexicos.md#l14) deverá estar [logado](lexicos.md#l6) em sua conta do [Pinterest](lexicos.md#l9) <br> [Usuário](lexicos.md#l14) estar com o aplicativo Pinterest aberto <br> Pós-Condição: O [Pin](lexicos.md#l1) é enviado a outro usuário. |
|**Atores** |
| [Usuário](lexicos.md#l14) |
|**Recursos** |
| Internet, aplicativo, conta de usuário, [pin](lexicos.md#l1) |
|**Restrição**|
| - |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) <br> [Pin](lexicos.md#l1) ser excluído ao ser enviado <br> [Usuário](lexicos.md#l14) que for receber o [Pin](lexicos.md#l1) ter bloqueado o que for enviá-lo |
|**Episódios** |
| [Usuário](lexicos.md#l14) entra na página inicial para visualizar e navegar pelo [feed](lexicos.md#l15) de [Pins](lexicos.md#l1) <br> [Usuário](lexicos.md#l14) seleciona um [Pin](lexicos.md#l1) <br> [Usuário](lexicos.md#l14) clica no botão Enviar <br> [Usuário](lexicos.md#l14) escolhe a forma de envio <br> [Usuário](lexicos.md#l14) enviar o [Pin](lexicos.md#l1) para outra pessoa |

## Fazer [login](lexicos.md#l16)

|**Objetivo**|
|--|
|Utilizar todas as ferramentas exclusivas para usuários [logados](lexicos.md#l16)|
|**Contexto**|
|Local: Pagina inicial do [Pinterest](lexicos.md#l9) <br> Pré-Condição: Estar [cadastrado](), inserir o e-mail e a senha corretos <br>  Pós-Condição: O [usuário](lexicos.md#l14) está [logado](lexicos.md#l6)|
|**Atores**|
|[Usuário](lexicos.md#l14) cadastrado|
|**Recursos**|
|E-mail válido|
|**Restrição**|
| - |
|**Exceção**|
|Esquecer a senha <br> Esquecer o e-mail <br> Não ter cadastro|
|**Episódios**|
|Inicializar o [Pinterest](lexicos.md#l9) <br> Inserir e-mail <br> Clicar em "Continuar"|


## Ir para a fonte de um [Pin](lexicos.md#l1)

|**Objetivo** |
|--|
| Saber de qual site o [pin](lexicos.md#l1) está sendo enviado|
|**Contexto** |
| Local: Ao clicar em um [pin](lexicos.md#l1) ou passar o mouse sobre ele <br> Pré-Condição: Estar conectado à internet <br> Ser cadastrado no [Pinterest](lexicos.md#l9) <br>  Pós-Condição: O [usuário](lexicos.md#l14) é direcionado para outra página na Internet que publicou o conteúdo do [pin](lexicos.md#l1) originalmente.|
|**Atores** |
| [Usuário](lexicos.md#l14)|
|**Recursos** |
| Internet, aplicativo, [conta](lexicos.md#conta) de [usuário](lexicos.md#l14) |
|**Restrição**|
| Ser um [link](lexicos.md#l5) válido |
|**Exceção** |
| Falta de internet <br> Página fonte excluída antes do clique no [link](lexicos.md#l5) da página|
|**Episódios** |feed
| [Usuário](lexicos.md#l14) abre o aplicativo  <br> [Usuário](lexicos.md#l14) faz o [login](lexicos.md#l16)<br> [Usuário](lexicos.md#l14) clica em um [pin](lexicos.md#l1)<br> [Usuário](lexicos.md#l14) clica no botão com o link para o site fonte no canto inferior direito da página <br> **ou** <br>  [Usuário](lexicos.md#l14) abre o aplicativo  <br> [Usuário](lexicos.md#l14) faz o [login](lexicos.md#l16)<br> [Usuário](lexicos.md#l14) passa o mouse sobre um [pin](lexicos.md#l1)<br> [Usuário](lexicos.md#l14) clica no botão com o link para o site fonte no canto inferior direito da [pin](lexicos.md#l1)<br>|

## Organizar [Pasta](lexicos.md#l3)

|Objetivo |
|--|
| Realocar [pins](lexicos.md#l1) em [pastas](lexicos.md#l3) ou [subpastas](lexicos.md#l4) e excluir [pins](lexicos.md#l1)|
|**Contexto** |
| Local: [Página](lexicos.md#l7) da [pasta](lexicos.md#l3) a ser organizada <br> Tempo - A qualquer momento  <br> Pré-Condição: O [Usuário](lexicos.md#l14) deve possuir [pins](lexicos.md#l1) na [pasta](lexicos.md#l3) a ser organizada ou na [subpasta](lexicos.md#l4) a ser organizada  <br>  Pós-Condição: A [pasta](lexicos.md#l3) e/ou a [subpasta](lexicos.md#l3) estão organizadas de acordo com o interesse do [usuário](lexicos.md#l14)|
|**Atores** |
| [Usuário](lexicos.md#l14) proprietário da [pasta](lexicos.md#l3) <br> [Usuários](lexicos.md#l14) com quem a [pasta](lexicos.md#l3) foi [compartilhada](lexicos.md#l12)|
|**Recursos** |
| Internet <br> Conta no aplicativo <br>  [Pasta](lexicos.md#l3) <br> [Subpastas](lexicos.md#l4) <br> [Pins](lexicos.md#l1) na [Pasta](lexicos.md#l3) <br> |
|**Restrição**|
| - |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) |
|**Episódios** |
| [Usuário](lexicos.md#l14) abre o aplicativo <br> [Usuário](lexicos.md#l14) navega até a [pasta](lexicos.md#l3) <br> [Usuário](lexicos.md#l14) seleciona a opção de organizar [pasta](lexicos.md#l3) <br> [Usuário](lexicos.md#l14) seleciona o [pin](lexicos.md#l1) que deseja modificar <br> [Usuário](lexicos.md#l14) decide entre [excluir](lexicos.md#l28), [mover](lexicos.md#mover) para [pasta](lexicos.md#l3) ou para [subpasta](lexicos.md#l4)|

## [Pesquisar](lexicos.md#l31) por tema

|**Objetivo** |
|--|
| Encontrar imagens referentes a um tema de preferência do usuário |
|**Contexto** |
| Local: [Página](lexicos.md#l7) inicial do aplicativo versão mobile <br> Tempo: a qualquer momento  <br> Pré-Condição: usuário ter em mente palavras-chaves relativas ao tema  <br>  Pós-Condição: O [usuário](lexicos.md#l14) encontrará uma [página](lexicos.md#l7) repleta de [pins](lexicos.md#l1) de acordo com a temática desejada|
|**Atores** |
| [Usuário](lexicos.md#l14) |
|**Recursos** |
| Internet <br> Conta no aplicativo <br>|
|**Restrição**|
| O conteúdo retornado pela pesquisa deve ter relação com o termo [pesquisado](lexicos.md#l31). |
|**Exceção** |
| Palavras que coincidirem com outros temas <br> Internet cair <br> App dar [crash](lexicos.md#l20) <br> |
|**Episódios** |
| [Usuário](lexicos.md#l14) abre o aplicativo <br> [Usuário](lexicos.md#l14) escreve palavras relacionadas ao tema desejado na [barra de pesquisa](lexicos.md#barraDepesquisa) <br> [Usuário](lexicos.md#l14) clica "enter" <br> Aplicativo mostra uma seleção de imagens referentes ao tema <br> Aplictivo mostra uma seleção de palavras relacionadas ao tema que direcione para pesquisas específicas|

## [Pesquisar](lexicos.md#l31) por foto

|**Objetivo** |
|--|
| Utilizar o recurso de fotografar imagens para [pesquisar](lexicos.md#l31) por imagens semelhantes |
|**Contexto** |
| Local: [Página](lexicos.md#l7) inicial do aplicativo versão mobile <br> Tempo - A Qualquer momento  <br> Pré-Condição: Celular possuir câmera <br>  Pós-Condição: O [usuário](lexicos.md#l14) encontrará uma [página](lexicos.md#l7) repleta de [pins](lexicos.md#l1) que possuam semelhança com as características da foto detectadas pelo [Pinterest](lexicos.md#l9)|
|**Atores** |
| [Usuário](lexicos.md#l14) |
|**Recursos** |
| Internet <br> Conta no aplicativo <br> Celular com câmera |
|**Restrição**|
| O conteúdo retornado pela [pesquisa](lexicos.md#l31) deve estar relacionado à foto pesquisada. <br> A Foto possuir boa qualidade gráfica. <br> Existirem muitos [pins](#lexicos.md#l1) semelhantes à foto tirada.  |
|**Exceção** |
| Câmera não funcionar <br> Internet cair <br> App dar [crash](lexicos.md#l20) <br> |
|**Episódios** |
| [Usuário](lexicos.md#l14) abre o aplicativo <br> O [usuário](lexicos.md#l14) visualiza [pagina](lexicos.md#l7) inical. <br> [Usuário](lexicos.md#l14) seleciona o ícone de câmera na [barra de pesquisa](lexicos.md#barraDepesquisa) <br> [Usuário](lexicos.md#l14) tira foto da imagem por qual busca semelhantes <br> Aplicativo mostra uma seleção de imagens semelhantes à enviada pelo [Usuário](lexicos.md#l14)  |

## Seguir outro [usuário](lexicos.md#l14)

|**Objetivo** |
|--|
| [Seguir](lexicos.md#l8) um outro [Usuário](lexicos.md#l14) para acompanhar sua atividade no [Pinterest](lexicos.md#l9) |
|**Contexto** |
| Local: Perfil de um [usuário](lexicos.md#l14) <br>  Pré-Condição: o [usuário](lexicos.md#l14) não pode [seguir](lexicos.md#l8) a si mesmo  <br>  Pós-Condição: O [usuário](lexicos.md#l14) [logado](lexicos.md#l6) poderá acompanhar os [pins](lexicos.md#l1) de outro [usuário](lexicos.md#l14)|
|**Atores** |
| [Usuário](lexicos.md#l14) |
|**Recursos** |
| Internet, aplicativo, conta de usuário |
|**Restrição**|
| - |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) <br> [Usuário](lexicos.md#l14) ter sido bloqueado pelo outro [usuário](lexicos.md#l14) que deseja [seguir](lexicos.md#l8) |
|**Episódios** |
| [Usuário](lexicos.md#l14) abre o aplicativo <br> [Usuário](lexicos.md#l14) navega até a página do perfil de outro [Usuário](lexicos.md#l14) <br> [Usuário](lexicos.md#l14) aperta botão [seguir](lexicos.md#l8)|

## [Salvar](lexicos.md#l2) um [Pin](lexicos.md#l1)

### Versão 1.0

|**Objetivo** |
|--|
| [Salvar](lexicos.md#l2) um [Pin](lexicos.md#l1) em uma [pasta](lexicos.md#l3) criada pelo [usuário](lexicos.md#l14) do [Pinterest](lexicos.md#l9) |
|**Contexto** |
| Local: Página de detalhes de um [Pin](lexicos.md#l1) <br>  Pré-Condição: o [usuário](lexicos.md#l14) deverá estar [logado](lexicos.md#l6) em sua conta do [Pinterest](lexicos.md#l9) <br>  Pós-Condição: O [Pin](lexicos.md#l1) é [salvo](lexicos.md#salvar) em uma [pasta](lexicos.md#l3). |
|**Atores** |
| [Usuário](lexicos.md#l14) |
|**Recursos** |
| Internet, aplicativo, [conta de usuário](lexicos.md#l32), [pin](lexicos.md#l1) |
|**Restrição**|
| - |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) <br> [Pin](lexicos.md#l1) ser excluído ao ser [salvo](lexicos.md#salvar) <br> Não existir [pastas](lexicos.md#l3) para [salvá-lo](lexicos.md#salvar) |
|**Episódios** |
| [Usuário](lexicos.md#l14) abre o aplicativo <br> [Usuário](lexicos.md#l14) entra na [página](lexicos.md#l7) inicial para visualizar e [navegar](lexicos.md#l36) pelo [feed](lexicos.md#l15) de [Pins](lexicos.md#l1) <br> [Usuário](lexicos.md#l14) seleciona um [Pin](lexicos.md#l1) <br> [Usuário](lexicos.md#l14) clica no botão [Salvar](lexicos.md#salvar) <br> [Usuário](lexicos.md#l14) escolhe a [pasta](lexicos.md#l3) para [salvá-lo](lexicos.md#salvar) e se não houverem [pastas](lexicos.md#l3) criadas, cria uma [pasta](lexicos.md#l3) para poder [salvar](lexicos.md#salvar) o [Pin](lexicos.md#l1) <br> [Usuário](lexicos.md#l14) [salvar](lexicos.md#salvar) o [Pin](lexicos.md#l1) na [pasta](lexicos.md#l3) |

### Versão 2.0

|**Objetivo** |
|--|
| [Salvar](lexicos.md#l2) um [Pin](lexicos.md#l1) em uma [pasta](lexicos.md#l3) criada pelo [usuário](lexicos.md#l14) do [Pinterest](lexicos.md#l9) |
|**Contexto** |
| Local: Página de detalhes de um [Pin](lexicos.md#l1) <br>  Pré-Condição: o [usuário](lexicos.md#l14) deverá estar [logado](lexicos.md#l6) em sua conta do [Pinterest](lexicos.md#l9) <br> [Usuário](lexicos.md#l14) estar com o aplicativo Pinterest aberto <br>  Pós-Condição: O [Pin](lexicos.md#l1) é [salvo](lexicos.md#salvar) em uma [pasta](lexicos.md#l3). |
|**Atores** |
| [Usuário](lexicos.md#l14) |
|**Recursos** |
| Internet, aplicativo, [conta de usuário](lexicos.md#l32), [pin](lexicos.md#l1) |
|**Restrição**|
| - |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) <br> [Pin](lexicos.md#l1) ser excluído ao ser [salvo](lexicos.md#salvar) <br> Não existir [pastas](lexicos.md#l3) para [salvá-lo](lexicos.md#salvar) |
|**Episódios** |
| [Usuário](lexicos.md#l14) entra na [página](lexicos.md#l7) inicial para visualizar e [navegar](lexicos.md#l36) pelo [feed](lexicos.md#l15) de [Pins](lexicos.md#l1) <br> [Usuário](lexicos.md#l14) seleciona um [Pin](lexicos.md#l1) <br> [Usuário](lexicos.md#l14) clica no botão [Salvar](lexicos.md#salvar) <br> [Usuário](lexicos.md#l14) escolhe a [pasta](lexicos.md#l3) para [salvá-lo](lexicos.md#salvar) e se não houverem [pastas](lexicos.md#l3) criadas, cria uma [pasta](lexicos.md#l3) para poder [salvar](lexicos.md#salvar) o [Pin](lexicos.md#l1) <br> [Usuário](lexicos.md#l14) [salvar](lexicos.md#salvar) o [Pin](lexicos.md#l1) na [pasta](lexicos.md#l3) |

## Visualizar [Feed](lexicos.md#l15)

|**Objetivo** |
|--|
| Visualizar [pins](lexicos.md#l1) de [interesse](lexicos.md#l10) do [usuário](lexicos.md#l14) pelo [feed](lexicos.md#l15) |
|**Contexto** |
| Local: [Página](lexicos.md#l7) incial do [Pinterest](lexicos.md#l9) <br>  Pré-Condição: O [usuário](lexicos.md#l14) deverá acessar o [Pinterest](lexicos.md#l9) caso queira visualizar algo de seu [interesse](lexicos.md#l10) <br>  Pós-Condição: O [usuário](lexicos.md#l14) visualizará o conteúdo da [página](lexicos.md#l7) inicial do [Pinterest](lexicos.md#l9)|
|**Atores** |
| [Usuário](lexicos.md#l14) |
|**Recursos** |
| Internet, aplicativo |
|**Restrição**|
| Os [pins](lexicos.md#l1) devem obedecer os interesses do [usuário](lexicos.md#l14) |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) <br> O App não está atualizado frequentemente|
|**Episódios** |
| [Usuário](lexicos.md#l14) acessa o [pinterest](lexicos.md#l9)  <br> [Usuário](lexicos.md#l14) navega pelo [feed](lexicos.md#l15) de [pins](lexicos.md#l1) <br> [Usuário](lexicos.md#l14) pesquisa [pins](lexicos.md#l1) de seu [interesse](lexicos.md#l10) <br> [Usuário](lexicos.md#l14) vizualiza o [pin](lexicos.md#l1) <br> |

## Visualizar aba [Seguindo](lexicos.md#l15)

|**Objetivo** |
|--|
| Visualizar [pins](lexicos.md#l1) de outros usuários que o [usuário](lexicos.md#l14) [logado](lexicos.md#l6) segue
|**Contexto** |
| Local: [Aba](lexicos.md#l7) [seguindo](lexicos.md#seguindo) do [Pinterest](lexicos.md#l9) <br>  Pré-Condição: O [usuário](lexicos.md#l14) deverá acessar o [Pinterest](lexicos.md#l9) caso queira publicado pelos demais usuários que segue <br>  Pós-Condição: O [usuário](lexicos.md#l14) [logado](lexicos.md#l6) visualizará o conteúdo publicado pelos [usuários](lexicos.md#l14) que está [seguindo](lexicos.md#l8)|
|**Atores** |
| [Usuário](lexicos.md#l14) [logado](lexicos.md#l6) <br> Usuários [seguidos](lexicos.md#l8) pelo [usuário](lexicos.md#l14) [logado](lexicos.md#l6)|
|**Recursos** |
| Internet, aplicativo |
|**Restrição**|
| - |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) <br>|
|**Episódios** |
| [Usuário](lexicos.md#l14) acessa o [pinterest](lexicos.md#l9)  <br> [Usuário](lexicos.md#l14) navega pela [aba](lexicos.md#l7) [seguindo](lexicos.md#l8)<br>  [Usuário](lexicos.md#l14) vizualiza o conteúdo de cada [pin](lexicos.md#l1) <br> |

## Enviar mensagem para outros [usuários](lexicos.md#l14)

|**Objetivo** |
|--|
| Poder se comunicar com outros [usuários](lexicos.md#l14) por meio do [Pinterest](lexicos.md#l9) sendo por [mensagens](lexicos.md#l18) ou enviando [pins](lexicos.md#l1) |
|**Contexto** |
| Local: [Página](lexicos.md#l7) de [mensagens](lexicos.md#l18) <br>  Pré-Condição: O [usuário](lexicos.md#l14) está [logado](lexicos.md#l16) em sua conta do [Pinterest](lexicos.md#l9) <br>  Pós-Condição: O [usuário](lexicos.md#l14) [logado](lexicos.md#l6) interagiu com outro [usuário](lexicos.md#l14) que também está cadastrado no [Pinterest](lexicos.md#l9)|
|**Atores** |
| [Usuário](lexicos.md#l14) e [usuários](lexicos.md#l14) conhecidos|
|**Recursos** |
| Internet, aplicativo |
|**Restrição**|
| - |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) <br> [mensagem](lexicos.md#l18) não se entregue|
|**Episódios** |
| [Usuário](lexicos.md#l14) [loga](lexicos.md#l16) em seu [perfil](lexicos.md#l17)  <br> [Usuário](lexicos.md#l14) navega até o icone de [mensagem](lexicos.md#l18) <br> [Usuário](lexicos.md#l14) procura por outro [usuários](lexicos.md#l14) <br> [Usuário](lexicos.md#l14) envia a [mensagem](lexicos.md#l18) <br> |

## Receber [notificações](lexicos.md#l19)

|**Objetivo** |
|--|
| Ser [notificado](lexicos.md#l19) sobre alguma interação de outros [usuários](lexicos.md#l14) ou novos [pins](lexicos.md#l1) relacionados a um [pin](lexicos.md#l1) [pinado](lexicos.md#pinado) |
|**Contexto** |
| Local: [Página](lexicos.md#l7) de [notificações](lexicos.md#l19) <br> Pré-Condição: O [Usuário](lexicos.md#l14) deve estar [logado](lexicos.md#l16) na sua conta do [Pinterest](lexicos.md#l9) e ter algum [pin](lexicos.md#l1) [pinado](lexicos.md#pinado) ou [seguir](lexicos.md#l8) algum outro [usuário](lexicos.md#l14) <br>  Pós-Condição: O [usuário](lexicos.md#l14) [logado](lexicos.md#l6) será [notificado](lexicos.md#l19) quando um outro [usuário](lexicos.md#l14) interagir com ele|
|**Autores** |
| [Usuários](lexicos.md#l14), [usuários](lexicos.md#l14) seguido e o [Pinterest](lexicos.md#l9) |
|**Recursos** |
|Internet <br> Browser <br> Aplicativo <br>  [Seguir](lexicos.md#l8) outro [usuário](lexicos.md#l14) <br> [Pin](lexicos.md#l1) [pinado](lexicos.md#pinado) |
|**Restrição**|
| [Usuário](lexicos.md#l14) não ter o app silenciado. |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) <br>  [Usuários](lexicos.md#l14) [seguidos](lexicos.md#l8) por um [usuário](lexicos.md#l14) deixarem de segui-lo |
|**Episódios** |
|[Usuário](lexicos.md#l14) acessa o [Pinterest](lexicos.md#l9) <br> [Usuário](lexicos.md#l14) [pina](lexicos.md#l2) um [pin](lexicos.md#l1) <br> [Usuário](lexicos.md#l14) [segue](lexicos.md#l8) outro [usuário](lexicos.md#l14) <br> [Usuário](lexicos.md#l14) clica em [notificações](lexicos.md#l19)  <br> [Usuário](lexicos.md#l14) vê novas interações de outros [usuários](lexicos.md#l14) e novos [pins](lexicos.md#l1) relacionados a um [pin](lexicos.md#l1) [pinado](lexicos.md#l2)

## [Classificação](lexicos.md#l30) de [pastas](#lexicos.md#pastas)
|**Objetivo** |
|--|
|Poder classificar as [pastas](lexicos.md#l3) em cincos opções da preferência do [usuário](lexicos.md#l14), sendo elas "Salvo pela última vez", "A a Z", "Igual à Web", "Mais antigas" e "Mais recentes" e assim as [pastas](lexicos.md#l3) serão reorganizadas
| Local: Conjunto de [pastas](lexicos.md#l3) <br> Pré-Condição: O [Usuário](lexicos.md#l14) deve estar [logado](lexicos.md#l16) na sua conta do [Pinterest](lexicos.md#l9) e ter mais de uma  [pasta](lexicos.md#l3)  <br>  Pós-Condição: O [usuário](lexicos.md#l14) consegue classificar suas [pastas](lexicos.md#l3)|
|**Autores** |
| [Usuários](lexicos.md#l14) |
|**Recursos** |
|Internet <br> Browser <br> Aplicativo <br> Ter mais de uma [pasta](lexicos.md#l3) <br>  |
|**Restrição**|
| Ter mais de uma [pasta](lexicos.md#l3) |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) <br> |
|**Episódios** |
|[Usuário](lexicos.md#l14) acessa o [Pinterest](lexicos.md#l9) <br> [Usuário](lexicos.md#l14) clica no ícone de [perfil](lexicos.md#l17) <br> [Usuário](lexicos.md#l14) clica em um ícone <br> [Usuário](lexicos.md#l14) clica no ícone de seta para baixo na parte superior direita da tela  <br> [Usuário](lexicos.md#l14) escolhe entre as opções de classificação ("Salvo pela última vez", "A a Z", "Igual à Web", "Mais antigas" e "Mais recentes") |

## [Ocultar](lexicos.md#l13) um [Pin](lexicos.md#l1)

|**Objetivo** |
|--|
| [Ocultar](lexicos.md#l13) um [pin](lexicos.md#l1) de uma [aba](lexicos.md#l7) do [Pinterest](lexicos.md#l9) para que o [usuário](lexicos.md#l14) não visualize mais determinado conteúdo|
|**Contexto** |
| Local: Página de detalhes de um [Pin](lexicos.md#l1) <br>  Pré-Condição: o [usuário](lexicos.md#l14) deverá estar [logado](lexicos.md#l6) em sua conta do [Pinterest](lexicos.md#l9) <br>  Pós-Condição: O [pin](lexicos.md#l1) não aparecerá mais para o [usuário](lexicos.md#l14) em nenhuma das [abas](lexicos.md#l7) do [Pinterest](lexicos.md#l9) |
|**Atores** |
| [Usuário](lexicos.md#l14) |
|**Recursos** |
| Internet, aplicativo, conta de usuário, [pin](lexicos.md#l1) |
|**Restrição**|
| Que o [pin](lexicos.md#l1) não seja do interesse do [usuário](lexicos.md#l14). |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) <br> [Pin](lexicos.md#l1) ser excluído ao ser [ocultado](lexicos.md#l13) <br> |
|**Episódios** |
| [Usuário](lexicos.md#l14) abre o aplicativo <br> [Usuário](lexicos.md#l14) entra na página inicial para visualizar e navegar pelo [feed](lexicos.md#l15) de repleto de [pins](lexicos.md#l1) <br> [Usuário](lexicos.md#l14) seleciona um [Pin](lexicos.md#l1) <br> [Usuário](lexicos.md#l14) clica no botão [Ocultar](lexicos.md#l13) <br> [Pinterest](lexicos.md#l9) informa que [pins](lexicos.md#l1) com esse tipo de conteúdo não aparecerão mais para o [usuário](lexicos.md#l14) <br> |

## [Denunciar](lexicos.md#l34) um [Pin](lexicos.md#l1)

|**Objetivo** |
|--|
| [Denunciar](lexicos.md#l34) um [pin](lexicos.md#l1) presente em uma [aba](lexicos.md#l7) do [Pinterest](lexicos.md#l9)|
|**Contexto** |
| Local: Página de detalhes de um [Pin](lexicos.md#l1), na opção "Mais"<br>  Pré-Condição: o [usuário](lexicos.md#l14) deverá estar [logado](lexicos.md#l6) em sua conta do [Pinterest](lexicos.md#l9) <br> O [usuário](lexicos.md#l14) deverá encontrar um [pin](lexicos.md#l1) com conteúdo que julga como impróprio <br> Pós-Condição: O [pin](lexicos.md#l1) será encaminhado para a [comunidade](lexicos.md#l35) do [Pinterest](lexicos.md#l9) avaliar o conteúdo e não aparecerá mais para o [usuário](lexicos.md#l14) em nenhuma das [abas](lexicos.md#l7) do [Pinterest](lexicos.md#l9) |
|**Atores** |
| [Usuário](lexicos.md#l14) |
|**Recursos** |
| Internet, aplicativo, conta de usuário, [pin](lexicos.md#l1) |
|**Restrição**|
| O [pin](lexicos.md#l1) ser inapropriado. |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) <br> |
|**Episódios** |
| [Usuário](lexicos.md#l14) abre o aplicativo <br> [Usuário](lexicos.md#l14) entra na página inicial para visualizar e navegar pelo [feed](lexicos.md#l15) repleto de de [pins](lexicos.md#l1) <br>  [Usuário](lexicos.md#l14) encontra um [pin](lexicos.md#l1) com conteúdo impróprio <br> [Usuário](lexicos.md#l14) seleciona um [Pin](lexicos.md#l1) <br> [Usuário](lexicos.md#l14) clica no botão Mais <br>  [Usuário](lexicos.md#l14) clica no botão [Denunciar](lexicos.md#l34) <br>  [Pinterest](lexicos.md#l9) informa que [pins](lexicos.md#l1) com esse tipo de conteúdo não aparecerão mais para o [usuário](lexicos.md#l14) <br> [Comunidade](lexicos.md#l35) do [Pinterest](lexicos.md#l9) avalia o conteúdo do [pin](lexicos.md#l1) [denunciado](lexicos.md#denunciado) e remove o conteúdo do aplicativo |

## Classificar um [Pin](lexicos.md#l1) como [Experimentado](lexicos.md#l22)

|**Objetivo** |
|--|
| [Experimentar](lexicos.md#l22) o conteúdo de um [pin](lexicos.md#l1) e classificá-lo na [aba](lexicos.md#l7) do [Pinterest](lexicos.md#l9) de [Experimentados](lexicos.md#l22)|
|**Contexto** |
| Local: [Aba de Salvos](lexicos.md#abasalvos) do [Pinterest](lexicos.md#l9), na opção [Experimentados](lexicos.md#l22)<br>  Pré-Condição: o [usuário](lexicos.md#l14) deverá estar [logado](lexicos.md#l6) em sua conta do [Pinterest](lexicos.md#l9) <br> O [usuário](lexicos.md#l14) deverá [experimentar](lexicos.md#l22) na prática um [pin](lexicos.md#l1)<br> Pós-Condição: O [pin](lexicos.md#l1) ficará [salvo](lexicos.md#l2) na [aba](lexicos.md#l7) [Experimentar](lexicos.md#l22) do [Pinterest](lexicos.md#l9) junto com uma foto do que foi [experimentado](lexicos.md#l22)|
|**Atores** |
| [Usuário](lexicos.md#l14) |
|**Recursos** |
| Internet, aplicativo, conta de usuário, [pin](lexicos.md#l1), câmera de celular e recursos do conteúdo a ser [experimentado](lexicos.md#l22) do [pin](lexicos.md#l1)|
|**Restrição**|
| O [usuário](lexicos.md#l14) ter experimentado o conteúdo do pin na vida real. |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) <br> [Usuário](lexicos.md#l14) não ter os recursos exigidos pelo [pin](lexicos.md#l1) para [experimentá-lo](lexicos.md#l22)|
|**Episódios** |
| [Usuário](lexicos.md#l14) abre o aplicativo <br> [Usuário](lexicos.md#l14) entra na [Aba Salvos](lexicos.md#abasalvos) <br>  [Usuário](lexicos.md#l14) seleciona a opção [Experimentados](lexicos.md#l22) <br> [Pinterest](lexicos.md#l9) apresenta em lista os [pins](lexicos.md#l1) [salvos](lexicos.md#l2) pelo [usuário](lexicos.md#l14) <br>[Usuário](lexicos.md#l14) seleciona a opção adicionar [pin](lexicos.md#l1)  <br> [Usuário](lexicos.md#l14) tira foto do [pin](lexicos.md#l1) [experimentado](lexicos.md#l22) <br>  [Usuário](lexicos.md#l14) inclui uma anotação a respeito de sua experiência <br> [Usuário](lexicos.md#l14) seleciona a opção Concluído  |

## Sair do aplicativo [Pinterest](lexicos.md#l9)

|**Objetivo** |
|--|
| Sair de uma conta [logada](lexicos.md#l6)|
|**Contexto** |
| Local: [Aba de Salvos](lexicos.md#abasalvos) do [Pinterest](lexicos.md#l9), na opção da ignição <br>  Pré-Condição: o [usuário](lexicos.md#l14) deverá estar [logado](lexicos.md#l6) em sua conta do [Pinterest](lexicos.md#l9) <br> Pós-Condição: O [usuário](lexicos.md#l14) não estará mais [logado](lexicos.md#l6) no [Pinterest](lexicos.md#l9)|
|**Atores** |
| [Usuário](lexicos.md#l14) |
|**Recursos** |
| Internet, aplicativo, conta de usuário|
|**Restrição**|
| - |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) <br>|
|**Episódios** |
| [Usuário](lexicos.md#l14) abre o aplicativo <br> [Usuário](lexicos.md#l14) entra na [Aba Salvos](lexicos.md#abasalvos) <br>  [Usuário](lexicos.md#l14) seleciona a opção Ignição <br>[Usuário](lexicos.md#l14) seleciona a opção Sair <br> [Usuário](lexicos.md#l14) visualiza a [página](lexicos.md#l7) inicial de [login](lexicos.md#l6) do [Pinterest](lexicos.md#l9)<br>

## Editar [Perfil](lexicos.md#l17)

|**Objetivo** |
|--|
| Alterar ou atualizar algum dado sobre o perfil do [usuário](lexicos.md#l14)|
|**Contexto** |
| Local: [Página](lexicos.md#l7) de edição do [Pinterest](lexicos.md#l9) <br> Pré-Condição: Estar conectado à internet <br> Ser cadastrado no [Pinterest](lexicos.md#l9) <br>  Pós-Condição: O [usuário](lexicos.md#l14) tem seus dados atualizados na sua [página](lexicos.md#l7) de perfil|
|**Atores** |
| [Usuário](lexicos.md#l14) |
|**Recursos** |
| Internet, aplicativo, [conta](lexicos.md#l16) de usuário|
|**Restrição**|
| - |
|**Exceção** |
| Internet cair <br> App dar [crash](lexicos.md#l20) <br>|
|**Episódios** |
|[Fazer login](#fazer-login) <br> [Usuário](lexicos.md#l14) clica na ignição superior direito da tela <br> [Usuário](lexicos.md#l14) seleciona a opção [perfil](lexicos.md#pefil) no canto superior esquerdo da [página](lexicos.md#pagina) de edição <br> O [Usuário](lexicos.md#l14) muda seu nome e/ou sobrenome <br> **ou** <br> O [Usuário](lexicos.md#l14) muda sua foto de [perfil](lexicos.md#l17) <br> **ou**  <br> O [Usuário](lexicos.md#l14) muda seu username <br> **ou** <br> O [Usuário](lexicos.md#l14) adiciona ou muda a descrição sobre ele <br> **ou** <br> O [Usuário](lexicos.md#l14) muda ou adiciona sua localização <br> **ou** <br> O [Usuário](lexicos.md#l14) muda ou adiciona seu website, caso ele possua um
