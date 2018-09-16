# Introdução

 A Técnica de modelagem por cenários consiste na elaboração de estruturas narrativas visando a construção de um contexto cujas informações permitam compreender ações desempenhadas no software, bem como os diversos fatores que influenciam essas ações, como o contexto, os recursos, elementos atuantes e etc. Essa técnica proporciona ainda uma forma de contextualização das funcionalidades desempenhadas em diferentes contextos de utilização do software analisado, trazendo elementos que auxiliam na compreensão da ideia abordada, permitindo uma forma direta de descrição.

# Cenários

## Cadastro de usuário

|**Objetivo** |
|--|
| Cadastrar novo usuário no Pinterest |
|**Contexto** |
| Local: Página inicial do app [Pinterest](lexicos/#pinterest) (quando não logado) <br>  Pré-Condição: não ter cadastro  |
|**Atores** |
| [Usuário](lexicos/#usuario) não cadastrado|
|**Recursos** |
| Internet, aplicativo, conta de e-mail|
|**Exceção** |
| Internet cair <br> App dar crash <br> Senha inválida <br> E-mail inválido |
|**Episódios** |
| [Usuário](lexicos/#usuario) não cadastrado abre o aplicativo <br> [Usuário](lexicos/#usuario) seleciona fazer o cadastro <br> [Usuário](lexicos/#usuario) preenche dados de cadastro <br> [Usuário](lexicos/#usuario) confirma cadastro |

## Comentar em um Pin

|**Objetivo** |
|--|
| Criar comentário em um [Pin](lexicos/#pin) |
|**Contexto** |
| Local: Página de detalhes de um [pin](lexicos/#pin) <br>  Pré-Condição: o usuário deve estar autenticado em sua conta  |
|**Atores** |
| [Usuário](lexicos/#usuario) |
|**Recursos** |
| Internet, aplicativo, conta de e-mail|
|**Exceção** |
| Internet cair <br> App dar crash <br> [Pin](lexicos/#pin) ser apagado enquanto comentário é escrito |
|**Episódios** |
| [Usuário](lexicos/#usuario) abre o aplicativo <br> [Usuário](lexicos/#usuario) seleciona o [Pin](lexicos/#pin) em que deseja comentar <br> [Usuário](lexicos/#usuario) escreve seu comentário <br> [Usuário](lexicos/#usuario) envia comentário |

## Compartilhar Pasta

|Objetivo |
|--|
| Permitir que um ou mais [usuários](lexicos/#usuario) tenham acesso a uma [pasta](lexicos/#pasta), podendo editar os [Pins](lexicos/#pin) existentes e adicionar novos. |
|**Contexto** |
| Local: [Página](lexicos/#pagina) da [pasta](lexicos/#pasta) a ser [compartilhada](lexicos/#compartilhar) <br> Tempo: A qualquer momento  <br> Pré-Condição: O [Usuário](lexicos/#usuario) com quem a [pasta](lexicos/#pasta) será compartilhada deverá possuir ou criar uma nova conta no Pinterest.  |
|**Atores** |
| [Usuário](lexicos/#usuario) proprietário da [pasta](lexicos/#pasta) <br> [Usuário](lexicos/#usuario) com quem a [pasta](lexicos/#pasta) será [compartilhada](lexicos/#compartilhar)|
|**Recursos** |
| Internet <br> Conta no aplicativo <br>  [Pasta](lexicos/#pasta) <br>  |
|**Exceção** |
| Internet cair <br> App dar crash <br> [Usuário](lexicos/#usuario) ter sido bloqueado pelo outro <br> [Usuário](lexicos/#usuario) recusar o [convite](lexicos/#convite) para [colaborar](lexicos/#colaborar) |
|**Episódios** |
| [Usuário](lexicos/#usuario) abre o aplicativo <br> [Usuário](lexicos/#usuario) navega até a [pasta](lexicos/#pasta) <br> [Usuário](lexicos/#usuario) seleciona a opção de [compartilhar](lexicos/#compartilhar) <br> [Usuário](lexicos/#usuario) escolhe o outro [usuário](lexicos/#usuario) com quem compartilhar <br> [Usuário](lexicos/#usuario) envia o [convite](lexicos/#convite) para [colaboração](lexicos/#colaborar) |

## Criar Pasta

|Objetivo |
|--|
| Criar um local para guardar [pins](lexicos/#pin) de um mesmo tema de escolha do [usuário](lexicos/#usuario)|
|**Contexto** |
| Local: [Página](lexicos/#pagina) de [perfil](lexicos/#perfil) <br> Tempo: A qualquer momento  <br> Pré-Condição:  [Usuário](lexicos/#usuario) possuir [conta](lexicos/#conta) no aplicativo. |
|**Atores** |
| [Usuário](lexicos/#usuario) |
|**Recursos** |
| Internet <br> Conta no aplicativo |
|**Exceção** |
| Internet cair <br> App dar crash <br> [Usuário](lexicos/#usuario) ter sido bloqueado pelo outro  |
|**Episódios** |
| [Usuário](lexicos/#usuario) abre o aplicativo <br> [Usuário](lexicos/#usuario) navega até seu [perfil](lexicos/#perfil) <br> [Usuário](lexicos/#usuario) seleciona a opção de criar nova [pasta](lexicos/#pasta) <br> [Usuário](lexicos/#usuario) digita o nome que deseja dar à [pasta](lexicos/#pasta) <br> [Usuário](lexicos/#usuario) escolhe se torna a [pasta](lexicos/#pasta) [secreta](lexicos/#pastaPrivada) ou não <br> [Usuário](lexicos/#usuario) seleciona a opção criar <br> **Ou** <br> [Usuário](lexicos/#usuario) abre o aplicativo <br> [Usuário](lexicos/#usuario) seleciona um [pins](lexicos/#pin) da página inicial <br> [Usuário](lexicos/#usuario) seleciona a opção de [salvar](lexicos/#salvar) [pin](lexicos/#pin)  <br> [Usuário](lexicos/#usuario) digita o nome que deseja dar à [pasta](lexicos/#pasta) <br> [Usuário](lexicos/#usuario) escolhe a opção de criar [pasta](lexicos/#pasta) <br> [Usuário](lexicos/#usuario) digita o nome que deseja dar à [pasta](lexicos/#pasta) <br> [Usuário](lexicos/#usuario) escolhe se torna a [pasta](lexicos/#pasta) [secreta](lexicos/#pastaPrivada) ou não <br> [Usuário](lexicos/#usuario) seleciona a opção criar <br> |

## Definir [interesses](#lexicos/#interesse)

|**Objetivo** |
|--|
| Escolher assuntos que são do [interesse](#lexicos/#interesse) do [usuário](lexicos/#usuario) |
|**Contexto** |
| Local: Logo após o cadastro ou na aba de [interesses](#lexicos/#interesse) dentro da aba salvo <br>  Pré-Condição: estar logado |
|**Atores** |
| [Usuário](lexicos/#usuario) |
|**Recursos** |
| Internet, aplicativo, conta de [usuário](#lexicos/#usuario) |
|**Exceção** |
| Internet cair <br> App dar crash |
|**Episódios** |
| [Usuário](lexicos/#usuario) abre o aplicativo <br> [Usuário](lexicos/#usuario) navega até a aba salvo [Usuário](lexicos/#usuario) <br> [Usuário](lexicos/#usuario) aperta botão [interesses](#interesse) <br> [Usuário](lexicos/#usuario) escolhe [interesses](#lexicos/#interesse)|

## Editar um Pin

|**Objetivo** |
|--|
| Modificar um [Pin](lexicos/#pin) de acordo com a necessidade e desejo do dono da [conta](#lexicos/#conta)|
|**Contexto** |
| Local: Página de perfil do [usuário](lexicos/#usuario) <br>  Pré-Condição: Conexão com a internet <br> Ter, pelo menos, um [pin](lexicos/#pin) próprio <br> O [usuário](lexicos/#usuario) deve estar autenticado em sua [conta](#lexicos/#conta) |
|**Atores** |
| [Usuário](lexicos/#usuario) |
|**Recursos** |
| Internet, aplicativo, [pin](lexicos/#pin)|
|**Exceção** |
| Internet cair <br> App dar crash <br>
|**Episódios** |
| [Usuário](lexicos/#usuario) abre o aplicativo <br> [Usuário](lexicos/#usuario) faz [login](lexicos/#login) <br> [Usuário](lexicos/#usuario) clica em sua página de [perfil](#lexicos/#perfil) no canto superior direito da tela <br> [Usuário](lexicos/#usuario) seleciona a aba [Pins](#lexicos/#pin) <br> [Usuário](lexicos/#usuario) seleciona o [pin](lexicos/#pin) que deseja editar <br> [Usuário](lexicos/#usuario) clica no ícone de editar simbolizado por um lápis no canto superior esquerdo da tela. <br> **ou** <br> [Usuário](lexicos/#usuario) abre o aplicativo <br> [Usuário](lexicos/#usuario) faz [login](lexicos/#login) <br> [Usuário](lexicos/#usuario) clica em sua página de [perfil](#lexicos/#perfil) no canto superior direito da tela <br> [Usuário](lexicos/#usuario) seleciona a aba [Pins](#lexicos/#pin) <br> [Usuário](lexicos/#usuario) passa o mouse sobre o [pin](lexicos/#pin) que deseja editar <br> [Usuário](lexicos/#usuario) clica no ícone de editar simbolizado por um lápis na parte superior do [pin](lexicos/#pin). <br> **ou** <br> [Usuário](lexicos/#usuario) abre o aplicativo <br> [Usuário](lexicos/#usuario) faz [login](lexicos/#login) <br> [Usuário](lexicos/#usuario) clica em sua página de [perfil](#lexicos/#perfil) no canto superior direito da tela <br> [Usuário](lexicos/#usuario) seleciona a [aba](#lexicos/#aba) Pastas <br> [Usuário](lexicos/#usuario) clica na pasta que está o [pin](lexicos/#pin) que deseja editar <br> [Usuário](lexicos/#usuario) passa o mouse sobre o [pin](lexicos/#pin) que deseja editar <br> [Usuário](lexicos/#usuario) clica no ícone de editar simbolizado por um lápis na parte superior do [pin](lexicos/#pin). <br> **ou** <br> [Usuário](lexicos/#usuario) abre o aplicativo <br> [Usuário](lexicos/#usuario) faz [login](lexicos/#login) <br> [Usuário](lexicos/#usuario) clica em sua página de [perfil](#lexicos/#perfil) no canto superior direito da tela <br> [Usuário](lexicos/#usuario) seleciona a [aba](#lexicos/#aba) Pastas <br> [Usuário](lexicos/#usuario) clica na [pasta](#lexicos/#pasta) que está o [pin](lexicos/#pin) que deseja [editar](#lexicos/#editar) <br> [Usuário](lexicos/#usuario) seleciona o [pin](lexicos/#pin) que deseja [editar](#lexicos/#pin) <br> [Usuário](lexicos/#usuario) clica no ícone de [editar](#lexicos/#editar) simbolizado por um lápis no canto superior esquerdo da tela.|

## Enviar um [Pin](lexicos/#pin)

|**Objetivo** |
|--|
| Enviar um [Pin](lexicos/#pin) para outro [usuário](lexicos/#usuario) do [Pinterest](lexicos/#pinterest) por meio de chat ou enviá-lo para outras pessoas que não utilizam o [Pinterest](lexicos/#pinterest) por meio de outras redes sociais (WhatsApp, Facebook) ou até por SMS e e-mail |
|**Contexto** |
| Local: Página de detalhes de um [Pin](lexicos/#pin) <br>  Pré-Condição: O [usuário](lexicos/#usuario) deverá estar logado em sua conta do [Pinterest](lexicos/#pinterest) |
|**Atores** |
| [Usuário](lexicos/#usuario) |
|**Recursos** |
| Internet, aplicativo, conta de usuário |
|**Exceção** |
| Internet cair <br> App dar crash <br> [Pin](lexicos/#pin) ser excluído ao ser enviado <br> [Usuário](lexicos/#usuario) que for receber o [Pin](lexicos/#pin) ter bloqueado o que for enviá-lo |
|**Episódios** |
| [Usuário](lexicos/#usuario) abre o aplicativo <br> [Usuário](lexicos/#usuario) navega pelo feed de [Pin](lexicos/#pin) <br> [Usuário](lexicos/#usuario) seleciona um [Pin](lexicos/#pin) <br> [Usuário](lexicos/#usuario) clica no botão Enviar <br> [Usuário](lexicos/#usuario) escolhe a forma de envio <br> [Usuário](lexicos/#usuario) enviar o [Pin](lexicos/#pin) para outra pessoa |

## Ir para a fonte de um pin

|**Objetivo** |
|--|
| Saber qual a fonte dos [pins](#lexicos/#pin) |
|**Contexto** |
| Local: Ao clicar em um [pin](lexicos/#pin) ou passar o mouse sobre ele <br> Pré-Condição: Estar conectado à internet <br> Ser cadastrado no [Pinterest](#lexicos/#pinterest)|
|**Atores** |
| [Usuário](lexicos/#usuario)|
|**Recursos** |
| Internet, aplicativo, [conta](#lexicos/#conta) de [usuário](lexicos/#usuario) |
|**Exceção** |
| Falta de internet <br> Página fonte excluída antes do clique no [link](lexicos/#link) da página|
|**Episódios** |feed
| [Usuário](lexicos/#usuario) abre o aplicativo  <br> [Usuário](lexicos/#usuario) faz o [login](lexicos/#login)<br> [Usuário](lexicos/#usuario) clica em um [pin](lexicos/#pin)<br> [Usuário](lexicos/#usuario) clica no botão com o link para o site fonte no canto inferior direito da página <br> **ou** <br>  [Usuário](lexicos/#usuario) abre o aplicativo  <br> [Usuário](lexicos/#usuario) faz o [login](lexicos/#login)<br> [Usuário](lexicos/#usuario) passa o mouse sobre um [pin](lexicos/#pin)<br> [Usuário](lexicos/#usuario) clica no botão com o link para o site fonte no canto inferior direito da [pin](lexicos/#pin)<br>|

## Organizar Pasta

|Objetivo |
|--|
| Realocar [pins](lexicos/#pin) em [pastas](#lexicos/#pasta) ou [subpastas](#lexicos/#subpasta) e excluir [pins](lexicos/#pin)|
|**Contexto** |
| Local: [Página](#lexicos/#pagina) da [pasta](#lexicos/#pasta) a ser organizada <br> Tempo - A qualquer momento  <br> Pré-Condição: O [Usuário](lexicos/#usuario) deve possuir [pins](lexicos/#pin) na [pasta](#lexicos/#pasta) a ser organizada ou na [subpasta](#lexicos/#subpasta) a ser organizada |
|**Atores** |
| [Usuário](#lexicos/#usuario) proprietário da [pasta](#lexicos/#pasta) <br> [Usuários](lexicos/#usuario) com quem a [pasta](#lexicos/#pasta) foi [compartilhada](#lexicos/#compartilhar)|
|**Recursos** |
| Internet <br> Conta no aplicativo <br>  [Pasta](#lexicos/#pasta) <br> [Subpastas](#lexicos/#subpasta) <br> [Pins](lexicos/#pin) na [Pasta](#lexicos/#pasta) <br> |
|**Exceção** |
| Internet cair <br> App dar crash |
|**Episódios** |
| [Usuário](lexicos/#usuario) abre o aplicativo <br> [Usuário](lexicos/#usuario) navega até a [pasta](#lexicos/#pasta) <br> [Usuário](lexicos/#usuario) seleciona a opção de organizar [pasta](#lexicos/#pasta) <br> [Usuário](lexicos/#usuario) seleciona o [pin](lexicos/#pin) que deseja modificar <br> [Usuário](lexicos/#usuario) decide entre [excluir](#lexicos/#excluir), [mover](#lexicos/#mover) para [pasta](#lexicos/#pasta) ou para [subpasta](#lexicos/#subpasta)|

## Pesquisar por foto

|**Objetivo** |
|--|
| Utilizar o recurso de fotografar imagens para pesquisar por imagens semelhantes |
|**Contexto** |
| Local: [Página](#lexicos/#pagina) inicial do aplicativo versão mobile <br> Tempo - A Qualquer momento  <br> Pré-Condição: Celular possuir câmera  |
|**Atores** |
| [Usuário](lexicos/#usuario) |
|**Recursos** |
| Internet <br> Conta no aplicativo <br> Celular com câmera |
|**Exceção** |
| Câmera não funcionar <br> Internet cair <br> App dar crash <br> |
|**Episódios** |
| [Usuário](lexicos/#usuario) abre o aplicativo <br> [Usuário](lexicos/#usuario) seleciona o ícone de câmera na [barra de pesquisa](#lexicos/#barraDepesquisa) <br> [Usuário](lexicos/#usuario) tira foto da imagem por qual busca semelhantes <br> Aplciativo mostra uma seleção de imagens semelhantes à enviada pelo [Usuário](lexicos/#usuario)  |

## Seguir outro usuário

|**Objetivo** |
|--|
| [Seguir](lexicos/#seguir) um outro [Usuário](lexicos/#usuario) para acompanhar sua atividade no [Pinterest](lexicos/#pinterest) |
|**Contexto** |
| Local: Perfil de um [usuário](lexicos/#usuario) <br>  Pré-Condição: o [usuário](lexicos/#usuario) não pode [seguir](lexicos/#seguir) a si mesmo  |
|**Atores** |
| [Usuário](lexicos/#usuario) |
|**Recursos** |
| Internet, aplicativo, conta de usuário |
|**Exceção** |
| Internet cair <br> App dar crash <br> [Usuário](lexicos/#usuario) ter sido bloqueado pelo outro [usuário](lexicos/#usuario) que deseja [seguir](lexicos/#seguir) |
|**Episódios** |
| [Usuário](lexicos/#usuario) abre o aplicativo <br> [Usuário](lexicos/#usuario) navega até a página do perfil de outro [Usuário](lexicos/#usuario) <br> [Usuário](lexicos/#usuario) aperta botão [seguir](lexicos/#seguir)|

## Salvar um [Pin](lexicos/#pin)

|**Objetivo** |
|--|
| Salvar um [Pin](lexicos/#pin) em uma pasta criada pelo [usuário](lexicos/#usuario) do [Pinterest](lexicos/#pinterest) |
|**Contexto** |
| Local: Página de detalhes de um [Pin](lexicos/#pin) <br>  Pré-Condição: o [usuário](lexicos/#usuario) deverá estar logado em sua conta do [Pinterest](lexicos/#pinterest) |
|**Atores** |
| [Usuário](lexicos/#usuario) |
|**Recursos** |
| Internet, aplicativo, conta de usuário |
|**Exceção** |
| Internet cair <br> App dar crash <br> [Pin](lexicos/#pin) ser excluído ao ser salvo <br> Não existir pastas para salvá-lo |
|**Episódios** |
| [Usuário](lexicos/#usuario) abre o aplicativo <br> [Usuário](lexicos/#usuario) navega pelo feed de [Pin](lexicos/#pin) <br> [Usuário](lexicos/#usuario) seleciona um [Pin](lexicos/#pin) <br> [Usuário](lexicos/#usuario) clica no botão Salvar <br> [Usuário](lexicos/#usuario) escolhe a pasta para salvá-lo e se não haverem pastas criadas, cria uma pasta para poder salvar o [Pin](lexicos/#pin) <br> [Usuário](lexicos/#usuario) salvar o [Pin](lexicos/#pin) na pasta |

## Vizualizar [Feed](lexicos/#feed)

|**Objetivo** |
|--|
| Vizualizar [pins](lexicos/#pin) de [interesse](lexicos/#interesse) do [usuário](lexicos/#usuario) pelo [feed](lexicos/#feed) |
|**Contexto** |
| Local: [Página](#lexicos/#pagina) incial do [Pinterest](lexicos/#pinterest) <br>  Pré-Condição: O [usuário](lexicos/#usuario) deverá acessar o [Pinterest](lexicos/#pinterest) caso queira vizualizar algo de seu [interesse](lexicos/#interesse)|
|**Atores** |
| [Usuário](lexicos/#usuario) |
|**Recursos** |
| Internet, aplicativo |
|**Exceção** |
| Internet cair <br> App dar crash <br> O App não está atualizado frequentemente|
|**Episódios** |
| [Usuário](lexicos/#usuario) acessa o [pinterest](lexicos/#pinterest)  <br> [Usuário](lexicos/#usuario) navega pelo [feed](lexicos/#feed) de [pins](lexicos/#pin) <br> [Usuário](lexicos/#usuario) pesquisa [pins](lexicos/#pin) de seu [interesse](lexicos/#interesse) <br> [Usuário](lexicos/#usuario) vizualiza o [pin](lexicos/#pin) <br> |

## Enviar mensagem para outros [usuários](lexicos/#usuário)

|**Objetivo** |
|--|
| Poder se comunicar com outros [usuários](lexicos/#usuario) por meio do [Pinterest](lexicos/#pinterest) sendo por mensagens ou enviando [pins](lexicos/#pin) |
|**Contexto** |
| Local: [Página](#lexicos/#pagina) de mensagens <br>  Pré-Condição: O [usuário](lexicos/#usuario) está [logado](lexicos/#login) em sua conta do [Pinterest](lexicos/#pinterest)|
|**Atores** |
| [Usuário](lexicos/#usuario) e [usuários](lexicos/#usuario) conhecidos|
|**Recursos** |
| Internet, aplicativo |
|**Exceção** |
| Internet cair <br> App dar crash <br> mensagem não se entregue|
|**Episódios** |
| [Usuário](lexicos/#usuario) [loga](lexicos/#login) em seu [perfil](lexicos/#perfil)  <br> [Usuário](lexicos/#usuario) navega até o icone de mensagem <br> [Usuário](lexicos/#usuario) procura por outro [usuários](lexicos/#usuario) <br> [Usuário](lexicos/#usuario) envia a mensagem <br> |
