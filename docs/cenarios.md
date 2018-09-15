# Introdução

ashdaksjdhksjdhk

# Cenários

## Cadastro de usuário

|**Objetivo** |
|--|
| Cadastrar novo usuário no Pinterest |
|**Contexto** |
| Local: Página inicial do app [Pinterest](lexicos.md/#pinterest) (quando não logado) <br>  Pré-Condição: não ter cadastro  |
|**Atores** |
| [Usuário](lexicos.md/#usuario) não cadastrado|
|**Recursos** |
| Internet, aplicativo, conta de e-mail|
|**Exceção** |
| Internet cair <br> App dar crash <br> Senha inválida <br> E-mail inválido |
|**Episódios** |
| [Usuário](lexicos.md/#usuario) não cadastrado abre o aplicativo <br> [Usuário](lexicos.md/#usuario) seleciona fazer o cadastro <br> [Usuário](lexicos.md/#usuario) preenche dados de cadastro <br> [Usuário](lexicos.md/#usuario) confirma cadastro |

## Comentar em um Pin

|**Objetivo** |
|--|
| Criar comentário em um [Pin](lexicos.md/#pin) |
|**Contexto** |
| Local: Página de detalhes de um [pin](lexicos.md/#pin) <br>  Pré-Condição: o usuário deve estar autenticado em sua conta  |
|**Atores** |
| [Usuário](lexicos.md/#usuario) |
|**Recursos** |
| Internet, aplicativo, conta de e-mail|
|**Exceção** |
| Internet cair <br> App dar crash <br> [Pin](lexicos.md/#pin) ser apagado enquanto comentário é escrito |
|**Episódios** |
| [Usuário](lexicos.md/#usuario) abre o aplicativo <br> [Usuário](lexicos.md/#usuario) seleciona o [Pin](lexicos.md/#pin) em que deseja comentar <br> [Usuário](lexicos.md/#usuario) escreve seu comentário <br> [Usuário](lexicos.md/#usuario) envia comentário |

## Seguir outro usuário

|**Objetivo** |
|--|
| [Seguir](lexicos.md/#seguir) um outro [Usuário](lexicos.md/#usuario) para acompanhar sua atividade no [Pinterest](lexicos.md/#pinterest) |
|**Contexto** |
| Local: Perfil de um [usuário](lexicos.md/#usuario) <br>  Pré-Condição: o [usuário](lexicos.md/#usuario) não pode [seguir](lexicos.md/#seguir) a si mesmo  |
|**Atores** |
| [Usuário](lexicos.md/#usuario) |
|**Recursos** |
| Internet, aplicativo, conta de usuário |
|**Exceção** |
| Internet cair <br> App dar crash <br> [Usuário](lexicos.md/#usuario) ter sido bloqueado pelo outro [usuário](lexicos.md/#usuario) que deseja [seguir](lexicos.md/#seguir) |
|**Episódios** |
| [Usuário](lexicos.md/#usuario) abre o aplicativo <br> [Usuário](lexicos.md/#usuario) navega até a página do perfil de outro [Usuário](lexicos.md/#usuario) <br> [Usuário](lexicos.md/#usuario) aperta botão [seguir](lexicos.md/#seguir)|

## Definir [interesses](#interesse)

|**Objetivo** |
|--|
| Escolher assuntos que são do [interesse](#interesse) do [usuário](lexicos.md/#usuario) |
|**Contexto** |
| Local: Logo após o cadastro ou na aba de [interesses](#interesse) dentro da aba salvo <br>  Pré-Condição: estar logado |
|**Atores** |
| [Usuário](lexicos.md/#usuario) |
|**Recursos** |
| Internet, aplicativo, conta de usuário |
|**Exceção** |
| Internet cair <br> App dar crash |
|**Episódios** |
| [Usuário](lexicos.md/#usuario) abre o aplicativo <br> [Usuário](lexicos.md/#usuario) navega até a aba salvo [Usuário](lexicos.md/#usuario) <br> [Usuário](lexicos.md/#usuario) aperta botão [interesses](#interesse) <br> [Usuário](lexicos.md/#usuario) escolhe [interesses](#interesse)|

## Enviar um [Pin](lexicos.md/#pin)

|**Objetivo** |
|--|
| Enviar um [Pin](lexicos.md/#pin) para outro [usuário](lexicos.md/#usuario) do [Pinterest](lexicos.md/#pinterest) por meio de chat ou enviá-lo para outras pessoas que não utilizam o [Pinterest](lexicos.md/#pinterest) por meio de outras redes sociais (WhatsApp, Facebook) ou até por SMS e e-mail |
|**Contexto** |
| Local: Página de detalhes de um [Pin](lexicos.md/#pin) <br>  Pré-Condição: O [usuário](lexicos.md/#usuario) deverá estar logado em sua conta do [Pinterest](lexicos.md/#pinterest) |
|**Atores** |
| [Usuário](lexicos.md/#usuario) |
|**Recursos** |
| Internet, aplicativo, conta de usuário |
|**Exceção** |
| Internet cair <br> App dar crash <br> [Pin](lexicos.md/#pin) ser excluído ao ser enviado <br> [Usuário](lexicos.md/#usuario) que for receber o [Pin](lexicos.md/#pin) ter bloqueado o que for enviá-lo |
|**Episódios** |
| [Usuário](lexicos.md/#usuario) abre o aplicativo <br> [Usuário](lexicos.md/#usuario) navega pelo feed de [Pin](lexicos.md/#pin) <br> [Usuário](lexicos.md/#usuario) seleciona um [Pin](lexicos.md/#pin) <br> [Usuário](lexicos.md/#usuario) clica no botão Enviar <br> [Usuário](lexicos.md/#usuario) escolhe a forma de envio <br> [Usuário](lexicos.md/#usuario) enviar o [Pin](lexicos.md/#pin) para outra pessoa |

## Salvar um [Pin](lexicos.md/#pin)

|**Objetivo** |
|--|
| Salvar um [Pin](lexicos.md/#pin) em uma pasta criada pelo [usuário](lexicos.md/#usuario) do [Pinterest](lexicos.md/#pinterest) |
|**Contexto** |
| Local: Página de detalhes de um [Pin](lexicos.md/#pin) <br>  Pré-Condição: o [usuário](lexicos.md/#usuario) deverá estar logado em sua conta do [Pinterest](lexicos.md/#pinterest) |
|**Atores** |
| [Usuário](lexicos.md/#usuario) |
|**Recursos** |
| Internet, aplicativo, conta de usuário |
|**Exceção** |
| Internet cair <br> App dar crash <br> [Pin](lexicos.md/#pin) ser excluído ao ser salvo <br> Não existir pastas para salvá-lo |
|**Episódios** |
| [Usuário](lexicos.md/#usuario) abre o aplicativo <br> [Usuário](lexicos.md/#usuario) navega pelo feed de [Pin](lexicos.md/#pin) <br> [Usuário](lexicos.md/#usuario) seleciona um [Pin](lexicos.md/#pin) <br> [Usuário](lexicos.md/#usuario) clica no botão Salvar <br> [Usuário](lexicos.md/#usuario) escolhe a pasta para salvá-lo e se não haverem pastas criadas, cria uma pasta para poder salvar o [Pin](lexicos.md/#pin) <br> [Usuário](lexicos.md/#usuario) salvar o [Pin](lexicos.md/#pin) na pasta |
