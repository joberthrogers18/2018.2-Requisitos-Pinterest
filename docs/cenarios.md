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
