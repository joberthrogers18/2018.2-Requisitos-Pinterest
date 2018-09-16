# Introdução

 A Técnica de modelagem por cenários consiste na elaboração de estruturas narrativas visando a construção de um contexto cujas informações permitam compreender ações desempenhadas no software, bem como os diversos fatores que influenciam essas ações, como o contexto, os recursos, elementos atuantes e etc. Essa técnica proporciona ainda uma forma de contextualização das funcionalidades desempenhadas em diferentes contextos de utilização do software analisado, trazendo elementos que auxiliam na compreensão da ideia abordada, permitindo uma forma direta de descrição.

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

## Criar Pasta

|Objetivo |
|--|
| Criar um local para guardar [pins](lexicos.md/#pin) de um mesmo tema de escolha do [usuário](https://joberthrogers18.github.io/2018.2-Requisitos/lexicos/#pin)|
|**Contexto** |
| Local - [Página]() de [perfil]() <br> Tempo - A qualquer momento  <br> Pré-Condição -  [Usuário](lexicos.md/#usuario) possuir [conta]() no aplicativo. |
|**Atores** |
| [Usuário]() |
|**Recursos** |
| Internet <br> Conta no aplicativo |
|**Exceção** |
| Internet cair <br> App dar crash <br> [Usuário](lexicos.md/#usuario) ter sido bloqueado pelo outro  |
|**Episódios** |
| [Usuário](lexicos.md/#usuario) abre o aplicativo <br> [Usuário](lexicos.md/#usuario) navega até seu [perfil]() <br> [Usuário](lexicos.md/#usuario) seleciona a opção de criar nova [pasta](docs/lexicos.md/#lexicos/##pasta) <br> [Usuário](lexicos.md/#usuario) digita o nome que deseja dar à [pasta](docs/lexicos.md/#lexicos/##pasta) <br> [Usuário](lexicos.md/#usuario) escolhe se torna a [pasta](docs/lexicos.md/#lexicos/##pasta) [secreta]() ou não <br> [Usuário](lexicos.md/#usuario) seleciona a opção criar <br> **Ou** <br> [Usuário](lexicos.md/#usuario) abre o aplicativo <br> [Usuário](lexicos.md/#usuario) seleciona um [pins](lexicos.md/#pin) da página inicial <br> [Usuário](lexicos.md/#usuario) seleciona a opção de [salvar]() [pin](lexicos.md/#pin)  <br> [Usuário](lexicos.md/#usuario) digita o nome que deseja dar à [pasta](docs/lexicos.md/#lexicos/##pasta) <br> [Usuário](lexicos.md/#usuario) escolhe a opção de criar [pasta](docs/lexicos.md/#lexicos/##pasta) <br> [Usuário](lexicos.md/#usuario) digita o nome que deseja dar à [pasta](docs/lexicos.md/#lexicos/##pasta) <br> [Usuário](lexicos.md/#usuario) escolhe se torna a [pasta](docs/lexicos.md/#lexicos/##pasta) [secreta]() ou não <br> [Usuário](lexicos.md/#usuario) seleciona a opção criar <br> |

## Compartilhar [Pasta](docs/lexicos.md/#lexicos/##pasta)

|Objetivo |
|--|
| Permitir que um ou mais [usuários](lexicos.md/#usuario) tenham acesso a uma [pasta](docs/lexicos.md/#lexicos/##pasta), podendo editar os [Pins](lexicos.md/#pin) existentes e adicionar novos. |
|**Contexto** |
| Local - [Página]() da [pasta](docs/lexicos.md/#lexicos/##pasta) a ser [compartilhada]() <br> Tempo - A qualquer momento  <br> Pré-Condição - O [Usuário](lexicos.md/#usuario) com quem a [pasta](docs/lexicos.md/#lexicos/##pasta) será compartilhada deverá possuir ou criar uma nova conta no Pinterest.  |
|**Atores** |
| [Usuário]() proprietário da [pasta](docs/lexicos.md/#lexicos/##pasta) <br> [Usuário](lexicos.md/#usuario) com quem a [pasta](docs/lexicos.md/#lexicos/##pasta) será [compartilhada]()|
|**Recursos** |
| Internet <br> Conta no aplicativo <br>  [Pasta](docs/lexicos.md/#lexicos/##pasta) <br>  |
|**Exceção** |
| Internet cair <br> App dar crash <br> [Usuário](lexicos.md/#usuario) ter sido bloqueado pelo outro <br> [Usuário](lexicos.md/#usuario) recusar o [convite]() para [colaborar]() |
|**Episódios** |
| [Usuário](lexicos.md/#usuario) abre o aplicativo <br> [Usuário](lexicos.md/#usuario) navega até a [pasta](docs/lexicos.md/#lexicos/##pasta) <br> [Usuário](lexicos.md/#usuario) seleciona a opção de [compartilhar]() <br> [Usuário](lexicos.md/#usuario) escolhe o outro [usuário](lexicos.md/#usuario) com quem compartilhar <br> [Usuário](lexicos.md/#usuario) envia o [convite]() para [colaboração]() |

## Organizar Pasta

|Objetivo |
|--|
| Realocar [pins](lexicos.md/#pin) em [pastas]() ou [subpastas]() e excluir [pins](lexicos.md/#pin)|
|**Contexto** |
| Local - [Página]() da [pasta](docs/lexicos.md/#lexicos/##pasta) a ser organizada <br> Tempo - A qualquer momento  <br> Pré-Condição - O [Usuário](lexicos.md/#usuario) deve possuir [pins](lexicos.md/#pin) na [pasta](docs/lexicos.md/#lexicos/##pasta) a ser organizada ou na [subpasta]() a ser organizada |
|**Atores** |
| [Usuário]() proprietário da [pasta](docs/lexicos.md/#lexicos/##pasta) <br> [Usuários](lexicos.md/#usuario) com quem a [pasta](docs/lexicos.md/#lexicos/##pasta) foi [compartilhada]()|
|**Recursos** |
| Internet <br> Conta no aplicativo <br>  [Pasta](docs/lexicos.md/#lexicos/##pasta) <br> [Subpastas]() <br> [Pins](lexicos.md/#pin) na [Pasta](docs/lexicos.md/#lexicos/##pasta) <br> |
|**Exceção** |
| Internet cair <br> App dar crash |
|**Episódios** |
| [Usuário](lexicos.md/#usuario) abre o aplicativo <br> [Usuário](lexicos.md/#usuario) navega até a [pasta](docs/lexicos.md/#lexicos/##pasta) <br> [Usuário](lexicos.md/#usuario) seleciona a opção de organizar [pasta](docs/lexicos.md/#lexicos/##pasta) <br> [Usuário](lexicos.md/#usuario) seleciona o [pin](lexicos.md/#pin) que deseja modificar <br> [Usuário](lexicos.md/#usuario) decide entre [excluir](), [mover]() para [pasta](docs/lexicos.md/#lexicos/##pasta) ou para [subpasta]()|

## Pesquisar por foto

|**Objetivo** |
|--|
| Utilizar o recurso de fotografar imagens para pesquisar por imagens semelhantes |
|**Contexto** |
| Local - [Página]() inicial do aplicativo versão mobile <br> Tempo - A Qualquer momento  <br> Pré-Condição - Celular possuir câmera  |
|**Atores** |
| [Usuário](lexicos.md/#usuario) |
|**Recursos** |
| Internet <br> Conta no aplicativo <br> Celular com câmera |
|**Exceção** |
| Câmera não funcionar <br> Internet cair <br> App dar crash <br> |
|**Episódios** |
| [Usuário](lexicos.md/#usuario) abre o aplicativo <br> [Usuário](lexicos.md/#usuario) seleciona o ícone de câmera na [barra de pesquisa]() <br> [Usuário](lexicos.md/#usuario) tira foto da imagem por qual busca semelhantes <br> Aplciativo mostra uma seleção de imagens semelhantes à enviada pelo [Usuário](lexicos.md/#usuario)  |


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
