# Introdução

Este artefato busca ligar cada requisito levantado aos respectivos métodos de elicitação e modelagem utilizados na disciplina.

# Backward-From

## Legenda

#### Modelagem

| Código | Significado |
|  :------: | ------ |
|  IS | iStar |
|  NFR | NFR Framework |
|  BL | Backlog do Produto |
|  ECU | Especificações de Caso de Uso |
|  DCU | Diagramas de Caso de Uso |
|  L | Léxicos |
|  C | Cenários |

#### Elicitação

| Código | Significado |
|  :------: | ------ |
|  AP | Análise de Protocolo |
|  AD | Análise de Discurso |
|  ENT | Entrevista |
|  Q | Questionário |
|  INT | Introspecção |
|  ST | Storytelling |


## Tabela de Requisitos Funcionais

|  Código | Descrição | Elicitação | Modelagem | Elo |
|  :------: | :------: | :------: | :------: | :------: |
|  RF1 | O app deve apresentar opções de micro-serviço (Facebook ou Google) e e-mail como forma de login e cadastro. | [AP1](analise_protocolo.md#resultado-dos-requisitos) | [L - Login](lexicos.md#login); <br> [C - Fazer Login](cenarios.md#fazer-login); <br> [DC - Realizar Primeiro Login](diagramas_caso_uso.md#realizar-primeiro-login); <br> [DC Fazer Login](diagramas_caso_uso.md#fazer-login); <br>[DC - Cadastro de Usuário](diagramas_caso_uso.md#cadastro-de-usuario) ;<br> [ECU - Fazer login](especificacoes_caso_uso.md#fazer-login); <br> [IStar- Cadastro no Pinterest](iStar.md#cadastro-no-pinterest) <br> [US12](backlog.md#us12); | [EF1](#ef1) |
|  RF2 | Ter um feed baseado nos interesses do usuário. | [AP3](analise_protocolo.md#resultado-dos-requisitos) | [C- Definir interesses](cenarios.md#definir-interesses); <br> [L - Interesses](lexicos.md#interesse); <br> [DC - Definir Interesses](diagramas_caso_uso.md#definir-interesses); <br> [ECU - Definir Interesses](especificacoes_caso_uso.md#definir-interesses); <br> [IStar - Definir interesses](iStar.md#definir-interesses) <br> [US15](backlog.md#us15); | [EF2](#ef2) |
|  RF3 | O usuário deve poder visualizar os interesses a qualquer momento, de acordo com uma opção em seu perfil | [AD2](analise_discurso.md#requisitos-elicitados); <br> [AD7](analise_discurso.md#requisitos-elicitados); <br> [AP3](analise_protocolo.md#resulyado-dos-requisitos);  | [L - Interesse](lexicos.md#interesse); <br> [C - Definir Interessse](cenarios.md#definir-interesse); <br> [IS - Definir Interesses (Usuário)](iStar.md#definir-interesses); <br> [ DCU - Definir Interesses](diagramas_caso_uso.md#definir-interesses); <br> [US36](backlog.md#us36); | [EF3](#ef3) |
|  RF4 | O usuário deve ter a opção de salvar pins em um pasta | [ST2.4](storytelling.md#storytelling-2-aprendendo-receitas-no-pinterest) | [C - Salvar um Pin](cenarios.md#salvar-um-Pin); <br> [L - Pinar](lexicos.md#pinar)<br> [DC - Salvar um Pin ](diagramas_caso_uso.md#salvar-um-pin); <br> [ECU - Salvar um Pin](especificacoes_caso_uso.md#salvar-um-pin); <br> [US22](backlog.md#us22); | [EF4](#ef4) |
|  RF5 | O app deve possuir uma barra para pesquisa por texto. | [AP13](analise_protocolo.md#resultado-dos-requisitos) | [C - Pesquisar por tema](cenarios.md#pesquisar-por-tema); <br> [L - Pesquisa](lexicos.md#pesquisa); <br> [DC - Pesquisar por tema ](diagramas_caso_uso.md#pesquisar-por-tema); <br> [ECU - Pesquisar por tema](especificacoes_caso_uso.md#pesquisar-por-tema); <br> [IStar - Pesquisar Pins](iStar.md#pesquisar-pins); <br> [US34](backlog.md#us34); | [EF5](#ef5) |
|  RF6 | O App deve possibilitar a transferência de Pins entre pastas. | [ENT11](entrevista.md#requisitos-elicitados) | [DCU - Organizar Pastas](diagramas_caso_uso.md#organizar-pastas); <br> [L- Organizar](lexicos.md#organizar); <br> [C - Organizar Pastas](cenarios.md#organizar-pastas); <br> [US31](backlog.md#us31); | [EF6](#ef6) |
|  RF7 | O App deve permitir que o usuário impeça que determinado tipo de conteúdo seja mostrado em seu feed. | [AD2](analise_discurso.md#requisitos-elicitados); | [L - Interesse](lexicos.md#interesse); <br> [C - Definir Interessse](cenarios.md#definir-interesse); <br> [L - Ocultar](lexicos.md#ocultar); <br> [C - Ocultar um Pin](cenarios.md#ocultar-um-pin); [DCU - Ocultar um Pin](diagramas_caso_uso.md#ocultar-um-pin); <br> [US20](backlog.md#us20); | [EF7](#ef7) |
|  RF8 | O App deve obter vários dados de Pins bloqueados para identificar com precisão o tipo de conteúdo que o usuário não deseja visualizar. | [ENT15](entrevista.md#requisitos-elicitados) | [L - Ocultar](lexicos.md#ocultar); <br> [C - Ocultar um Pin](cenarios.md#ocultar-um-pin); <br>  [DCU - Ocultar um Pin](diagramas_caso_uso.md#ocultar-um-pin); <br> [ECU - Ocultar um Pin](especificacoes_caso_uso.md#ocultar-um-pin); <br> [US20](backlog.md#us20); | [EF8](#ef8) |
|  RF9 | O app deve absorver a informação das categorias dos pins mais visualizados para usar nas próximas recomendações | [INT1.5](introspeccao.md#introspeccao-1) | [L - Interesse](lexicos.md#interesse); <br> [US24](backlog.md#us24); | [EF9](#ef9) |
|  RF10 | O app deve separar os pins por categorias | [INT1.6](introspeccao.md#introspeccao-1) | [L - Pin](lexicos.md#pin); <br> [L - Pesquisa](lexicos.md#pesquisa); <br> [US34](backlog.md#us34); | [EF10](#ef10) |
|  RF11 | O usuário deve ter a opção de avaliar pins e essa avaliação deve ser aberta a outros usuários | [INT1.8](introspeccao.md#introspeccao-1) | [L - Comentar](lexicos.md#comentar); <br> [C - Comentar em um Pin](cenarios.md#comentar-em-um-pin); <br> [DCU - Comentar em um Pin](diagramas_caso_uso.md#comentar-em-um-pin); <br> [US15](backlog.md#us15); | [EF11](#ef11) |
|  RF12 | O App deve possibilitar que o usuário reorganize os Pins salvos em diferentes subpastas. | [ENT10](entrevista.md#requisitos-elicitados) | [L - Organizar](lexicos.md#organizar); <br> [L - Subpasta](lexicos.md#subpasta); <br> [US30](backlog.md#us30); <br> [US31](backlog.md#us31); <br> [C- Orgaizar Pasta](cenarios.md#organizar-pasta); <br> [DCU - Organizar Pasta](diagramas_caso_uso.md#organizar-pasta); | [EF12](#ef12) |
|  RF13 | Ao clicar no pin o usuário deve conseguir ver mais informações sobre ele, como uma pequena ou grande descrição | [ST2.3](storytelling.md#storytelling-2-aprendendo-receitas-no-pinterest); <br> [INT2.4](introspeccao.md#introspeccao-2); | [DCU - Visualizar Pin](diagramas_caso_uso.md#visualizar-pin); <br> [ECU - Visualizar Pin](especificacoes_caso_uso.md#visualizar-pin); <br> [US15](backlog.md#us15); | [EF13](#ef13) |
|  RF14 | O usuário deve poder adicionar novos interesses a qualquer momento após o cadastro, através de uma opção em seu perfil | [ST1.3](storytelling.md#storytelling-1-definindo-interesses-no-pinterest); | [C - Definir Interesses](cenarios.md#definir-interesses); <br> [L - Interesses](lexicos.md#definir-interesses); <br> [DCU - Definir Interesses](diagramas_caso_uso.md#definir-interesses); <br> [US36](backlog.md#us36); <br> [IS - Definir Interesses](iStar.md#definir-interesses); | [EF14](#ef14) |
|  RF15 | O usuário deve poder salvar seus pins no seu dispositivo | [AP4](analise_protocolo.md#resultado-dos-requisitos) | [US22](backlog.md#usa22); <br> [L - Pinar](lexicos.md#pinar); <br> [C- Salvar um Pin](cenarios.md#salvar-um-pin); <br> [DCU - Salvar um Pin](diagramas_caso_uso.md#salvar-um-pin); | [EF15](#ef15) |
|  RF16 | Manter pastas | [ENT11](entrevista.md#requisitos-elicitados); <br> [ST2.5](storytelling.md#storytelling-2-aprendendo-receitas-no-pinterest); <br> [ENT3](entrevista.md#requisitos-elicitados);   | [US29](backlog.md#us29); <br> [US31](backlog.md#us31); <br> [L - Pasta](lexicos.md#pasta); <br> [L - Organizar](lexicos.md#organizar); <br> [L - Excluir](lexicos.md#excluir); <br> [C - Criar Pasta](cenarios.md#criar-pasta); <br> [C - Organizar Pastas](cenarios.md#organizar-pastas); <br>  [DCU - Criar Pasta](diagramas_caso_uso.md#criar-pasta); <br> [DCU - Organizar Pasta](diagramas_caso_uso.md#organizar-pasta); | [EF16](#ef16) |
|  RF17 | Manter subpastas | [ENT10](entrevista.md#requisitos-elicitados) | [US30](backlog.md#us30); <br> [L - Subpasta](lexicos.md#subpasta); <br> [US31](backlog.md#us31); <br> [L - Organizar](lexicos.md#organizar); <br> [L - Excluir](lexicos.md#excluir); <br> [C - Criar Pasta](cenarios.md#criar-pasta); <br> [C - Organizar Pastas](cenarios.md#organizar-pastas); <br>  [DCU - Criar Pasta](diagramas_caso_uso.md#criar-pasta); <br> [DCU - Organizar Pasta](diagramas_caso_uso.md#organizar-pasta); | [EF17](#ef17) |
|  RF18 | A plataforma deve disponibilizar uma forma de pesquisa por imagem. | [AP12](analise_protocolo.md#resultado-dos-requisitos); <br> [AD14](analise_discurso.md#requisitos-elicitados) | [US35](backlog.md#us35); [L - Pesquisar](lexicos.md#pesquisar); <br> [C - Pesquisar por Foto](cenarios.md#pesquisar-por-foto); <br> [DCU - Pesquisar por Foto](diagramas_caso_uso.md#pesquisar-por-foto); | [EF18](#ef18) |
|  RF19 | O usuário deve poder ser redirecionado para o link da imagem de um pin, caso haja um. | [AP14](analise_protocolo.md#resultado-dos-requisitos) | [US16](backlog.md#us16); <br> [L - Link](lexicos.md#link); <br> [C - Ir para a fonte de um Pin](cenarios.md#ir-para-a-fonte-de-um-pin);  | [EF19](#ef19) |
|  RF20 | O usuário deve conseguir compartilhar pins com outros usuários | [AD12](analise_discurso.md#requisitos-elicitados) | [US17](backlog.md#us17); <br> [L - Compartilhar](lexicos.md#compartilhar); <br> [L - Usuário](lexicos.md#usuario); <br> [C - Enviar um Pin](cenarios.md#enviar-um-pin); <br> [IS - Enviar Pin (Usuário)](iStar.md#enviar-pin); <br> [DCU - Enviar um Pin](diagramas_caso_uso.md#enviar-um-pin); | [EF20](#ef20) |
|  RF21 | O usuário deve conseguir compartilhar pins em redes sociais | [INT2.2](introspeccao.md#introspeccao-2) | [L - Compartilhar](lexicos.md#compartilhar); <br>  [C - Enviar um Pin](cenarios.md#enviar-um-pin); <br> [DCU - Enviar um Pin](diagramas_caso_uso.md#enviar-um-pin); <br><br/>[ECU - Enviar um Pin](especificacoes_caso_uso.md#enviar-um-pin); <br> [US17](backlog.md#us17); <br> [IS - Enviar Pin](iStar.md#enviar-pin) | [EF21](#ef21) |
|  RF22 | A aplicação deve colocar nos pins a opção de "comentários" | [INT2.3](introspeccao.md#introspeccao-2) | [L - Comentar](lexicos.md#comentar); <br>  [C - Comentar em um Pin](cenarios.md#comentar-em-um-pin); <br> [DCU - Comentar em um Pin](diagramas_caso_uso.md#comentar-em-um-pin); <br> [ECU -  Comentar em um Pin](especificacoes_caso_uso.md#comentar-em-um-pin); <br> [US15](backlog.md#us15); | [EF22](#ef22) |
|  RF23 | O Pinterest deve oferecer a opção de seguir usuários | [INT2.7](introspeccao.md#introspeccao-2) | [L - Seguir](lexicos.md#seguir); <br> [C - Seguir outro usuário](cenarios.md#seguir-outro-usuario); <br> [ECU - Seguir outro usuário](especificacoes_caso_uso.md#seguir-outro-usuario); <br> [DCU - Seguir outro usuário](diagramas_caso_uso.md#seguir-outro-usuario); <br> [US23](backlog.md#us23); <br> [IS - Seguir usuário](iStar.md#seguir-usuario) | [EF23](#ef23) |
|  RF24 | O usuário deve poder ocultar e denunciar pins. | [ST1.5](storytelling.md#storytelling-1-definindo-interesses-no-pinterest); |  [L - Denunciar](lexicos.md#denunciar); <br> [C - Denunciar Pin](cenarios.md#denunciar-pin); <br> [ECU - Ocultar um Pin](especificacoes_caso_uso.md#ocultar-um-pin); <br> [DCU - Ocultar um Pin](diagramas_caso_uso.md#ocultar-um-pin); <br> [ECU - Denunciar um Pin](especificacoes_caso_uso.md#denunciar-um-pin); <br>[DCU - Denunciar Pin](diagramas_caso_uso.md#denuncar-pin); <br> [US20](backlog.md#us20); <br>  [US21](backlog.md#us21);  | [EF24](#ef24) |
|  RF25 | O aplicativo deve apresentar um navegador interno para redirecionamento de links presentes em pins. | [AP8](analise_protocolo.md#resultado-dos-requisitos) | [US16](backlog.md#us16); | [EF25](#ef25) |
|  RF26 | O app deve possuir a função de compartilhar a edição de pastas com outros usuários. | [ENT3](entrevista.md#requisitos-elicitados) | [L - Colaborar](lexicos.md#colaborar); <br> [C - Compartilhar Pasta](cenarios.md#compartilhar-pasta); <br> [DCU - Compartilhar Pasta](diagramas_caso_uso.md#compartilhar-pasta); <br> [ECU - Compartilhar Pasta](especificacoes_caso_uso.md#compartilhar-pasta); <br> [US32](backlog.md#us32); <br> [US33](backlog.md#us33);  | [EF26](#ef26) |
|  RF27 | As receitas devem ser pins especiais que ofereçam tempo, porções e ingredientes para instigar o usuário a fazê-la. | [INT2.4](introspeccao.md#introspeccao-2); | [US15](backlog.md#us15); | [EF27](#ef27) |
|  RF28 | O Aplicativo deve ser capaz de extrapolar dados de pesquisa de outras fontes para trazer itens mais relevantes para o usuário. | [AD4](analise_discurso.md#requisitos-elicitados) | [US39](backlog.md#us39); | [EF28](#ef28) |
|  RF29 | O usuário deve poder enviar mensagem para outros usuários. | [AD10](analise_discurso.md#requisitos-elicitados); <br> [AD11](analise_discurso.md#requsiitos-elicitados); | [L - Mensagem](lexicos.md#mensagem); <br> [C - Enviar mensagem para outros usuários](cenarios.md#enviar-mensagem-para-outro-usuario); <br> [ECU - Enviar um Pin](especificacoes_caso_uso.md#enviar-um-pin); <br> [ECU - Enviar Mensagem para outros usuários](especificacoes_caso_uso.md#enviar-mensagem-para-outros-usuarios); <br>  [DCU - Enviar Mensagem](diagramas_caso_uso.md#enviar-mensagem); <br> [IS - Enviar Pin (Usuário)](iStar.md#enviar-pin); <br> [DCU - Enviar Pin](diagramas_caso_uso.md#enviar-um-pin); <br> [US28](backlog.md#us28); | [EF29](#ef29) |
|  RF30 | O usuário deve receber notificações sobre novidades no app. | [AD8](analise_discurso.md#requisitos-elicitados);  | [L - Notificação](lexicos.md#notificacao); <br> [C - Receber notificações](cenarios.md#receber-notificacoes); <br> [DCU - Receber notificações](diagramas_caso_uso.md#receber-notificacoes); <br> [ECU - Receber notificações](especificacoes_caso_uso.md#receber-notificacoes); <br> [US24](backlog.md#us24); | [EF30](#ef30) |
|  RF31 | O usuário deve poder editar seu perfil. | - | [C - Editar Perfil](cenarios.md#editar-perfil); <br> [ECU - Editar perfil](especificacoes_caso_uso.md#editar-perfil); <br> [DCU - Editar Perfil](diagramas_caso_uso.md#editar-perfil); <br> [US37](backlog.md#us37); <br> [IS - Editar configurações de conta](iStar.md#editar-configuracoes-de-conta) | [EF31](#ef31) |
|  RF32 | Os pins que se referem a aplicativos devem mostrar a opção de instalar. | [INT2.4](introspeccao.md#introspeccao-2); | <br> [US16](backlog.md#us16); | [EF32](#ef32) |
|  RF33 | O pinterest deve manter algum canal de comunicação com usuário no caso de dúvidas ou problemas ocorridos com o usuário. | - | [NFR - Suporte](nfr.md#usuporte); <br> [C - Denunciar um Pin](cenarios.md#denunciar-um-pin); <br> [L - Denunciar](lexicos.md#denunciar); <br> [DCU - Denunciar um Pin](diagramas_caso_uso.md#denunciar-um-pin); <br> [US21](backlog.md#us21) | [EF33](#ef33) |
|  RF34 | O Usuário deve poder remover interesses em qualquer momento após o cadastro, acessando essa opção na aba de perfil | [ST1.3](storytelling.md#storytelling-1-definindo-interesses-no-pinterest); | [C - Definir Interesses](cenarios.md#definir-interesses); <br> [L - Interesses](lexicos.md#definir-interesses); <br> [DCU - Definir Interesses](diagramas_caso_uso.md#definir-interesses); <br> (US36)[backlog.md#us36); <br> [IS - Definir Interesses](iStar.md#definir-interesses); <br> [US36](backlog.md#us36); | [EF34](#ef34) |
|  RF35 | O Usuário deve possuir mais de uma opção de formas de ordenação das pastas na página de perfil, como ordem alfabética, últimos salvos, mais antigas, mais recentes ou pelo arraste dos elementos. | [ST2.5](storytelling.md#storytelling-2-aprendendo-receitas-no-pinterest);  |  [L - Organizar](lexicos.md#organizar); <br> [C - Organizar Pasta](cenarios.md#organizar-pasta); <br> [ECU - Classificação de Pastas](especificacoes_caso_uso.md#classificacao-de-pastas); <br> [ECU - Organizar Pasta](especificacoes_caso_uso.md#organizar-pasta); <br> [IS - Classificar Pastas](iStar.md#classificar-pastas); <br> [DCU - Classificar Pastas](diagramas_caso_uso.md#classificar-pastas); <br> [US31](backlog.md#us31); <br> [US25](backlog.md#us2); | [EF35](#ef35) |
|  RF36 | O Pinterest deve notificar usuários de outros usuários com interesses semelhantes | - | [L - Notificação](lexicos.md#notificacao); <br> [C - Receber notificações](cenarios.md#receber-notificacoes); <br> [IS- Seguir Usuário](iStar.md#seguir-usuario) <br> [US24](backlog.md#us24); | [EF36](#ef36) |
|  RF37 | O Usuário deve poder ocultar seu perfil e seus dados de mecanismos de pesquisa | - | [US37](backlog.md#us37); <br> [IS - Editar Configurações de Conta](iStar.md#editar-configuracoes-de-conta) | [EF37](#ef37) |
|  RF38 | O Pinterest deve poder utilizar dados, como cookies, para identificar informações de perfil do usuário e direcionar recomendações de pins | [AD4](analise_discurso.md#requisitos-elicitados);  | [IS - Editar Configurações de Conta](iStar.md#editar-configuracoes-de-conta) <br> [US39](backlog.md#us39) | [EF38](#ef38) |
|  RF39 | O Usuário deve poder definir informações pessoais, como seu gênero, nome de usuário, imagem de perfil e descrição, por meio de uma opção ao editar perfil ou se cadastrar | - | [US37](backlog.md#us37); <br> [IS - Cadastro no Pinterest](iStar.md#cadastro-no-pinterest); <br> [DCU - Editar Perfil](diagramas_caso_uso.md#editar-perfil); <br> [ECU - Editar Perfil](especificacoes_caso_uso.md#editar-perfil); <br> [C - Editar Perfil](cenarios.md#editar-perfil) <br> [US38](backlog.md#us38); | [EF39](#ef39) |
|  RF40 | O Usuário deve poder definir em qual língua irá utilizar o aplicativo, seja na edição do perfil ou no cadastro | [AD6](analise_discurso.md#requisitos-elicitados);  | [IS - Cadastro no Pinterest](iStar.md#cadastro-no-pinterest);  <br> [DCU - Editar Perfil](diagramas_caso_uso.md#editar-perfil); <br> [US38](backlog.md#us38); | [EF40](#ef40) |
|  RF41 | O Usuário deve poder postar e editar posteriormente um Pin | - | [C - Editar um Pin](cenarios.md#editar-um-pin); <br> [DCU - Editar um Pin](diagramas_caso_uso.md#editar-um-pin); <br> [ECU - Editar um Pin](especificacoes_caso_uso.md#editar-um-pin); <br> [IS - Enviar Pin (Outro Usuário)](iStar.md#enviar-pin); <br> [US18](backlog.md#us18) | [EF41](#ef41) |
|  RF42 | O Usuário deve poder postar pins a partir de imagens da galeria do dispositivo | - | [IS - Enviar Pin (Outro Usuário)](iStar.md#enviar-pin) <br> [US18](backlog.md#us18) | [EF42](#ef42) |
|  RF43 | O Usuário deve definir informações do pin postado, como categorias, título e descrição | [INT2.4](introspeccao.md#introspeccao-2); | [C - Editar um Pin](cenarios.md#editar-um-pin); <br> [DCU - Editar um Pin](diagramas_caso_uso.md#editar-um-pin); <br> [ECU - Editar um Pin](especificacoes_caso_uso.md#editar-um-pin); <br> [IS - Enviar Pin (Outro Usuário)](iStar.md#enviar-pin) <br> [US15](backlog.md#us15); | [EF43](#ef43) |
|  RF44 | O Usuário deve possuir formas de alterar escolhas em qualquer momento, como informações de perfil ou de postagem de pins, permitindo a correção de erros | - | [NFR - Usabilidade](nfr.md#usabilidade); <br> [US37](backlog.md#us37); <br> [US38](backlog.md#us38); | [EF44](#ef44) |

## Tabela de Requisitos Não Funcionais

|  Código | Descrição | Elicitação | Modelagem | Elo |
|  :------: | :------: | :------: | :------: | :------: |
|  RNF1 | O app deve permitir a escolha de interesses no primeiro acesso (no mínimo 5, obrigatoriamente), para que o Pinterest possa mapear os interesses do usuário. | [AP2](analise_protocolo.md#resultado-dos-requisitos); <br> [ST1.1](storytelling.md#storytelling-1-definindo-interesses-no-pinterest); | [DCU - Realizar Primeiro Login](diagramas_caso_uso.md#realizar-primeiro-login); <br>  [ECU - Realizar primeiro login](especificacoes_caso_uso.md#realizar-primeiro-login); <br> [IS - Cadastro no Pinterest](iStar.md#cadastro-no-pinterest); | [ENF1](#enf1) |
|  RNF2 | A aplicação deve conter um sistema de scroll infinito que possibilite ao usuário uma visualização mais orgânica do feed. | [AP7](analise_protocolo.md#resultado-dos-requisitos) | [L - Feed](lexicos.md#feed); <br> [DCU - Visualizar fedd](diagramas_caso_uso.md#visualizar-feed); <br> [C - Visualizar Feed](cenarios.md#visualizar-feed); <br> [ECU - Visualizar Feed](especificacoes_caso_uso.md#visualizar-feed); <br> | [ENF2](#enf2) |
|  RNF3 | O App deve sugerir Pins sobre assuntos pesquisados recentemente pelo usuário. | [AD5](analise_discurso.md#requisitos-elicitados)<br> [ENT12](entrevista.md#requisitos-elicitados) | [US15](backlog.md#us15); <br> [US36](backlog.md#us36); [C - Definir Interesses](cenarios.md#definir-interesses); <br> [C - Pesquisar por Tema](cenarios.md#pesquisar-por-tema); <br> [C - Pesquisar por Foto](cenarios.md#pesquisar-por-foto); <br> [L - Explorar](lexicos.md#explorar); <br>  [DCU - Definir Interesses](diagramas_caso_uso.md#definir-interesses); <br> [DCU - Pesquisar por Tema](diagramas_caso_uso.md#pesquisar-por-tema); <br> [DCU - Pesquisar por Foto](diagramas_caso_uso.md#pesquisar-por-foto); <br> [ECU - Pesquisar por Tema](especificacoes_caso_uso.md#pesquisar-por-tema); <br> [ECU - Pesquisar por Foto](especificacoes_caso_uso.md#pesquisar-por-foto); <br> [NFR - Definir Interesses](nfr.md#definir-interesses); <br> [NFR - Pesquisar Pins](nfr.md#pesquisar-pins) | [ENF3](#enf3) |
|  RNF4 | Ao pesquisar sobre algo, o Pinterest deve mostrar opções de filtro sobre o assunto, para que o usuário apenas clique em um e receba um resultado mais selecionado | [INT2.5](introspeccao.md#introspeccao-2) | [C - Pesquisar por tema](cenarios.md#pesquisar-por-tema); <br> [ECU - Pesquisar por tema](especificacoes_caso_uso.md#pesquisar-por-tema); <br> [DCU - Pesquisar por tema](diagramas_caso_uso.md#pesquisar-por-tema); <br> [IS - Pesquisar Pins](iStar.md#pesquisar-pins); <br> [C - Pesquisar por Foto](cenarios.md#pesquisar-por-foto); <br> [DCU - Pesquisar por Foto](diagramas_caso_uso.md#pesquisar-por-foto); <br> [ECU - Pesquisar por Foto](especificacoes_caso_uso.md#pesquisar-por-foto) | [ENF4](#enf4) |
|  RNF5 | Os pins devem oferecer informações sobre o motivo dele estar aparecendo para o usuário. | [ST1.4](storytelling.md#storytelling-1-definindo-interesses-no-pinterest) | [US19](backlog.md#us19); | [ENF5](#enf5) |
|  RNF6 | O app deve oferecer mais conteúdo relacionado às atividades recentes. | [ENT12](entrevista.md#requisitos-elicitados); <br> [ST2.1](storytelling.md#storytelling-2-aprendendo-receitas-no-pinterest) | [L - Explorar](lexicos.md#explorar); <br> [L - Recomendar](lexicos.md#recomendar); | [ENF6](#enf6) |
|  RNF7 | O usuário deve ter o ferramental necessário para realizar as etapas de uma receita sem precisar sair do app | [INT1.10](introspeccao.md#introspeccao-1) | [DCU - Visualizar Pin](diagramas_caso_uso.md#visualizar-pin); <br> [L - Experimentar](lexicos.md#experimentar);  | [ENF7](#enf7) |
|  RNF8 | A interface do usuário deve ser agradável para melhorar as experiências e torná-las excelentes. | [Q4](questionario.md#requisitos-elicitados); <br> | [NFR - Usabilidade](nfr.md#usabilidade); <br> [NFR - Usabilidade Design](nfr.md#usabilidade-design); <br> [NFR - Desempenho](nfr.md#desempenho); <br> [BL - US26](backlog.md#us26) | [ENF8](#enf8) |
|  RNF9 | A rede social deve incluir sempre novos conteúdos sobre os temas mais pesquisados em busca de mantê-los atualizados, mas também procurar abranger temas diferentes para atrair novos públicos específicos, como os praticantes de esportes, por exemplo. | [Q5](questionario.md#requisitos-elicitados); <br> | [L - Explorar])(lexicos.md#explorar); <br> [L - Interesses])(lexicos.md#interesses); <br> [IS - Outro Usuário](iStar.md#outro-usuario); <br> [IS - Geral](iStar.md#geral) | [ENF9](#enf9) |
|  RNF10 | O Aplicativo deve identificar a perda de interesse do usuário por um tema pela frequência de pesquisas. | [AD7](analise_discurso.md#requisitos-elicitados); <br> | [US15](backlog.md#us15); <br> [US36](backlog.md#us36); [C - Definir Interesses](cenarios.md#definir-interesses); <br> [C - Pesquisar por Tema](cenarios.md#pesquisar-por-tema); <br> [C - Pesquisar por Foto](cenarios.md#pesquisar-por-foto); <br> [L - Explorar](lexicos.md#explorar); <br>  [DCU - Definir Interesses](diagramas_caso_uso.md#definir-interesses); <br> [DCU - Pesquisar por Tema](diagramas_caso_uso.md#pesquisar-por-tema); <br> [DCU - Pesquisar por Foto](diagramas_caso_uso.md#pesquisar-por-foto); <br> [ECU - Pesquisar por Tema](especificacoes_caso_uso.md#pesquisar-por-tema); <br> [ECU - Pesquisar por Foto](especificacoes_caso_uso.md#pesquisar-por-foto); <br> [NFR - Definir Interesses](nfr.md#definir-interesses); <br> [NFR - Pesquisar Pins](nfr.md#pesquisar-pins) | [ENF10](#enf10) |
|  RNF11 | O app deve ser de rápida aprendizagem. | - | [NFR - Suporte](nfr.md#suporte); <br> [NFR - Conectividade](nfr.md#conectividade) | [ENF11](#enf11) |
|  RNF12 | O Usuário deve possuir a possibilidade de personalizar a ordem em que suas pastas serão visualizadas | [ST2.5](storytelling.md#storytelling-2-aprendendo-receitas-no-pinterest) | [IS - Classificar Pastas](iStar.md#classificar-pastas); <br> [L - Classificar](lexicos.md#classificar); | [ENF12](#enf12) |
|  RNF13 | O Pinterest deve identificar gostos de usuários em diferentes ambientes ou aplicativos, permitindo um conteúdo mais personalizado e direcionado, aumentando a identificação com os interesses definidos | [AD7](analise_discurso.md#requisitos-elicitados); | [IS - Editar Configurações de Conta](iStar.md#editar-configuracoes-de-conta) | [ENF13](#enf13) |
|  RNF14 | O Pinterest deve possuir feedbacks objetivos para informar o usuário da realização de tarefas pouco visuais, como copiar um link, aplicados principalmente para a versão mobile | - | [IS - Enviar Pin (Usuário)](iStar.md#enviar-pin); <br> [NFR - Usabilidade](nfr.md#usabilidade); | [ENF14](#enf14) |
|  RNF15 | O pinterest deve possuir interação fluida entre as funcionalidades, de modo que em poucos clique a ação seja feita. | - | [IS - Enviar Pin (Outro Usuário)](iStar.md#enviar-pin); | [ENF15](#enf15) |
|  RNF16 | O pinterest deve possuir o menor tempo possivel para responder as ações requisitada pelo usuário.  | - | [NFR - Desempenho](nfr.md#desempenho); <br> [IS - Geral](iStar.md#geral) | [ENF16](#enf16) |
|  RNF17 | O pinterest deve manter políticas de moderação de seu conteúdo dentro da aplicação. | - | [NFR - Segurança](nfr.md#seguranca); [C - Ocultar Pin](cenarios.md#ocultar-pin); <br> [C - Denunciar um Pin](cenarios.md#denunciar-um-pin) | [ENF17](#enf17) |
|  RNF18 | O pinterest deve manter a integridade dos dados fornecidos pelo usuário em sua conta. | - | [NFR - Segurança](nfr.md#seguranca); | [ENF18](#enf18) |

# Elos Funcionais

## EF1
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L - Login](lexicos.md#login); <br>
 [C - Fazer Login](cenarios.md#fazer-login); <br>
 [DC - Realizar Primeiro Login](diagramas_caso_uso.md#realizar-primeiro-login); <br>
[DC Fazer Login](diagramas_caso_uso.md#fazer-login); <br>
[DC - Cadastro de Usuário](diagramas_caso_uso.md#cadastro-de-usuario) ; <br>
[ECU - Fazer login](especificacoes_caso_uso.md#fazer-login); <br>
[IStar- Cadastro no Pinterest](iStar.md#cadastro-no-pinterest)
### Elo
**Representação**: [DC Fazer Login](diagramas_caso_uso.md#fazer-login) representa [C - Fazer Login](cenarios.md#fazer-login);
**Representação**: [IStar- Cadastro no Pinterest](iStar.md#cadastro-no-pinterest) representa [DC - Cadastro de Usuário](diagramas_caso_uso.md#cadastro-de-usuario) ;
**Agregação**:   [C - Fazer Login](cenarios.md#fazer-login),  [DC - Realizar Primeiro Login](diagramas_caso_uso.md#realizar-primeiro-login) e [DC Fazer Login](diagramas_caso_uso.md#fazer-login) são compostos por C - Fazer Login](cenarios.md#fazer-login);




## EF2
### Categoria
Desenvolvimento

### Elementos Rastreáveis
[C- Definir interesses](cenarios.md#definir-interesses); <br>
 [L - Interesses](lexicos.md#interesse); <br>
[DC - Definir Interesses](diagramas_caso_uso.md#definir-interesses); <br>
 [ECU - Definir Interesses](especificacoes_caso_uso.md#definir-interesses); <br>
[IStar - Definir interesses](iStar.md#definir-interesses)
### Elo
**Agregação**: [C- Definir interesses](cenarios.md#definir-interesses), [DC - Definir Interesses](diagramas_caso_uso.md#definir-interesses), [ECU - Definir Interesses](especificacoes_caso_uso.md#definir-interesses) e [IStar - Definir interesses](iStar.md#definir-interesses) são compostos por [L - Interesses](lexicos.md#interesse)
**Representação**:  [ECU - Definir Interesses](especificacoes_caso_uso.md#definir-interesses) representa [DC - Definir Interesses](diagramas_caso_uso.md#definir-interesses) e [C- Definir interesses](cenarios.md#definir-interesses)
**Representação**: [IStar - Definir interesses](iStar.md#definir-interesses) representa [ECU - Definir Interesses](especificacoes_caso_uso.md#definir-interesses)


## EF3
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[AD2](analise_discurso.md#requisitos-elicitados); <br> [AD7](analise_discurso.md#requisitos-elicitados); <br> [AP3](analise_protocolo.md#resultado-dos-requisitos); <br>
[L - Interesse](lexicos.md#interesse); <br>
 [C - Definir Interessse](cenarios.md#definir-interesse); <br>
 [IS - Definir Interesses (Usuário)](iStar.md#definir-interesses); <br>
 [ DCU - Definir Interesses](diagramas_caso_uso.md#definir-interesses);
### Elo
**Satisfação**: [NFR - Segurança](nfr.md#seguranca);

**Representação**:   [IStar - Definir interesses](iStar.md#definir-interesses) representa [ECU - Definir Interesses](especificacoes_caso_uso.md#definir-interesses)




## EF4
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[C - Salvar um Pin](cenarios.md#salvar-um-Pin); <br>
[L - Pinar](lexicos.md#pinar)<br>
[DC - Salvar um Pin ](diagramas_caso_uso.md#salvar-um-pin); <br>
[ECU - Salvar um Pin](especificacoes_caso_uso.md#salvar-um-pin); <br>
### Elo
**Representação**: [ECU - Salvar um Pin](especificacoes_caso_uso.md#salvar-um-pin) representa [DC - Salvar um Pin ](diagramas_caso_uso.md#salvar-um-pin) e [C - Salvar um Pin](cenarios.md#salvar-um-Pin)
**Satisfação**: [C - Salvar um Pin](cenarios.md#salvar-um-Pin), [DC - Salvar um Pin ](diagramas_caso_uso.md#salvar-um-pin) e [ECU - Salvar um Pin](especificacoes_caso_uso.md#salvar-um-pin satisfazem  [L - Pinar](lexicos.md#pinar),

## EF5
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[AP13](analise_protocolo.md#resultado-dos-requisitos); <br>
[C - Pesquisar por tema](cenarios.md#pesquisar-por-tema); <br>
 [L - Pesquisa](lexicos.md#pesquisa); <br>
 [DC - Pesquisar por tema ](diagramas_caso_uso.md#pesquisar-por-tema); <br>
 [ECU - Pesquisar por tema](especificacoes_caso_uso.md#pesquisar-por-tema); <br> [IStar - Pesquisar Pins](iStar.md#pesquisar-pins);
### Elo
**Representação**: [ECU - Pesquisar por tema](especificacoes_caso_uso.md#salvar-um-pin),  [DC - Pesquisar por tema ](diagramas_caso_uso.md#pesquisar-por-tema) representa [C - Pesquisar por tema](cenarios.md#pesquisar-por-tema)


## EF6
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[ENT11](entrevista.md#requisitos-elicitados)<br>
[DCU - Organizar Pastas](diagramas_caso_uso.md#organizar-pastas); <br>
 [L- Organizar](lexicos.md#organizar); <br>
[C - Organizar Pastas](cenarios.md#organizar-pastas); <br>
[US31](backlog.md#us31);
### Elo
**Alocação** : [ECU - Organizar Pastas](especificacoes_caso_uso.md#organizar-pasta) alocado em [US31](backlog.md#us31)
**Representação**: [DCU - Organizar Pastas](diagramas_caso_uso.md#organizar-pastas), [DCU - Organizar Pastas](diagramas_caso_uso.md#organizar-pastas) representa [C - Organizar Pastas](cenarios.md#organizar-pastas)


## EF7
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[AD2](analise_discurso.md#requisitos-elicitados); <br>
[L - Interesse](lexicos.md#interesse); <br>
[C - Definir Interessse](cenarios.md#definir-interesse); <br>
 [L - Ocultar](lexicos.md#ocultar); <br>
 [C - Ocultar um Pin](cenarios.md#ocultar-um-pin); <br> [DCU - Ocultar um Pin](diagramas_caso_uso.md#ocultar-um-pin); <br> [US20](backlog.md#us20);
### Elo


## EF8
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L - Denunciar](lexicos.md#denunciar); <br>
[C - Denunciar Pin](cenarios.md#denunciar-pin); <br>
[DCU - Denunciar um Pin](diagramas_caso_uso.md#denunciar-um-pin); <br>
 [ECU - Denunciar um Pin](especificacoes_caso_uso.md#denunciar-um-pin);
### Elo
**Representação**:  [ECU - Denunciar um Pin](especificacoes_caso_uso.md#denunciar-um-pin) representa [DCU - Denunciar um Pin](diagramas_caso_uso.md#denunciar-um-pin) e [C - Denunciar Pin](cenarios.md#denunciar-pin)
**Agregação**:   [ECU - Denunciar um Pin](especificacoes_caso_uso.md#denunciar-um-pin),   [DCU - Denunciar um Pin](diagramas_caso_uso.md#denunciar-um-pin) e [C - Denunciar Pin](cenarios.md#denunciar-pin) são compostos por [L - Denunciar](lexicos.md#denunciar)

## EF9
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L - Interesse](lexicos.md#interesse);
### Elo

## EF10
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L - Pin](lexicos.md#pin); <br>
[L - Pesquisa](lexicos.md#pesquisa);
### Elo
**Agregação**: [L - Pesquisa](lexicos.md#pesquisa) é composto por [L - Pin](lexicos.md#pin)

## EF11
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L - Comentar](lexicos.md#comentar); <br>
[C - Comentar em um Pin](cenarios.md#comentar-em-um-pin); <br>
[DCU - Comentar em um Pin](diagramas_caso_uso.md#comentar-em-um-pin);
### Elo
**Representação**: [DCU - Comentar em um Pin](diagramas_caso_uso.md#comentar-em-um-pin) representa [C - Comentar em um Pin](cenarios.md#comentar-em-um-pin)
**Agregação**: [DCU - Comentar em um Pin](diagramas_caso_uso.md#comentar-em-um-pin) e [C - Comentar em um Pin](cenarios.md#comentar-em-um-pin) são compostos por [L - Comentar](lexicos.md#comentar)

## EF12
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L - Organizar](lexicos.md#organizar); <br>
[L - Subpasta](lexicos.md#subpasta); <br>
[US30](backlog.md#us30); <br>
 [US31](backlog.md#us31); <br>
 [C- Orgaizar Pasta](cenarios.md#organizar-pasta); <br>
[DCU - Organizar Pasta](diagramas_caso_uso.md#organizar-pasta);
### Elo
**Representação**: [DCU - Organizar Pasta](diagramas_caso_uso.md#organizar-pasta) representa  [C- Orgaizar Pasta](cenarios.md#organizar-pasta)
**Alocação**: [DCU - Organizar Pasta](diagramas_caso_uso.md#organizar-pasta) está alocado em [US30](backlog.md#us30) e [US31](backlog.md#us31)


## EF13
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[ST2.3](storytelling.md#storytelling-2-aprendendo-receitas-no-pinterest); <br> [INT2.4](introspeccao.md#introspeccao-2); <br>
[DCU - Visualizar Pin](diagramas_caso_uso.md#visualizar-pin); <br>
 [ECU - Visualizar Pin](especificacoes_caso_uso.md#visualizar-pin);
### Elo


## EF14
### Categoria
Desenvolvimento
### Elementos Rastreáveis
### Elo

## EF15
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[AP4](analise_protocolo.md#resultado-dos-requisitos)<br>
[US22](backlog.md#usa22); <br>
 [L - Pinar](lexicos.md#pinar); <br>
[C- Salvar um Pin](cenarios.md#salvar-um-pin); <br>
[DCU - Salvar um Pin](diagramas_caso_uso.md#salvar-um-pin);
### Elo
**Representação**: [L - Pinar](lexicos.md#pinar), [DCU - Salvar um Pin](diagramas_caso_uso.md#salvar-um-pin) representa [C- Salvar um Pin](cenarios.md#salvar-um-pin)
**Alocação**: [DCU - Salvar um Pin](diagramas_caso_uso.md#organizar-pasta) está alocado em [US30](backlog.md#us30);  


## EF16
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[ENT11](entrevista.md#requisitos-elicitados); <br> [ST2.5](storytelling.md#storytelling-2-aprendendo-receitas-no-pinterest); <br> [ENT3](entrevista.md#requisitos-elicitados);  <br>
[US29](backlog.md#us29); <br>
 [US31](backlog.md#us31); <br>
 [L - Pasta](lexicos.md#pasta); <br>
 [L - Organizar](lexicos.md#organizar); <br>
 [L - Excluir](lexicos.md#excluir); <br>
[C - Criar Pasta](cenarios.md#criar-pasta); <br>
[C - Organizar Pastas](cenarios.md#organizar-pastas); <br>
[DCU - Criar Pasta](diagramas_caso_uso.md#criar-pasta); <br>
 [DCU - Organizar Pasta](diagramas_caso_uso.md#organizar-pasta);

### Elo


## EF17
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[ENT10](entrevista.md#requisitos-elicitados)<br>
[US30](backlog.md#us30); <br>
 [L - Subpasta](lexicos.md#subpasta); <br>
[US31](backlog.md#us31); <br>
 [L - Organizar](lexicos.md#organizar); <br>
[L - Excluir](lexicos.md#excluir); <br>
 [C - Criar Pasta](cenarios.md#criar-pasta); <br>
[C - Organizar Pastas](cenarios.md#organizar-pastas); <br>
 [DCU - Criar Pasta](diagramas_caso_uso.md#criar-pasta); <br>
 [DCU - Organizar Pasta](diagramas_caso_uso.md#organizar-pasta);
### Elo

## EF18
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[AP12](analise_protocolo.md#resultado-dos-requisitos); <br> [AD14](analise_discurso.md#requisitos-elicitados); <br>
[US35](backlog.md#us35); <br>
 [L - Pesquisar](lexicos.md#pesquisar); <br>
 [C - Pesquisar por Foto](cenarios.md#pesquisar-por-foto); <br>
[DCU - Pesquisar por Foto](diagramas_caso_uso.md#pesquisar-por-foto);
### Elo
**Representação**:  [DCU - Pesquisar por Foto](diagramas_caso_uso.md#pesquisar-por-foto) representa  [C - Pesquisar por Foto](cenarios.md#pesquisar-por-foto)
**Alocação**: [DCU - Pesquisar por Foto](diagramas_caso_uso.md#pesquisar-por-foto) está alocado em [US35](backlog.md#us35);
**Agregação** :   [C - Pesquisar por Foto](cenarios.md#pesquisar-por-foto),
[DCU - Pesquisar por Foto](diagramas_caso_uso.md#pesquisar-por-foto) são compostos por  [L - Pesquisar](lexicos.md#pesquisar);

## EF19
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[AP14](analise_protocolo.md#resultado-dos-requisitos);<br>
[US16](backlog.md#us16); <br>
 [L - Link](lexicos.md#link); <br>
 [C - Ir para a fonte de um Pin](cenarios.md#ir-para-a-fonte-de-um-pin);
### Elo
**Representação**:  [DCU - Pesquisar por Foto](diagramas_caso_uso.md#pesquisar-por-foto) representa  [C - Pesquisar por Foto](cenarios.md#pesquisar-por-foto)
**Alocação**: [DCU - Pesquisar por Foto](diagramas_caso_uso.md#pesquisar-por-foto) está alocado em [US35](backlog.md#us35);
**Agregação** :   [C - Pesquisar por Foto](cenarios.md#pesquisar-por-foto),
[DCU - Pesquisar por Foto](diagramas_caso_uso.md#pesquisar-por-foto) são compostos por  [L - Pesquisar](lexicos.md#pesquisar);

## EF20
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[AD12](analise_discurso.md#requisitos-elicitados); <br>
[US17](backlog.md#us17); <br>
 [L - Compartilhar](lexicos.md#compartilhar); <br>
 [L - Usuário](lexicos.md#usuario); <br>
[C - Enviar um Pin](cenarios.md#enviar-um-pin); <br>
 [IS - Enviar Pin (Usuário)](iStar.md#enviar-pin); <br>
[DCU - Enviar um Pin](diagramas_caso_uso.md#enviar-um-pin);
### Elo

## EF21
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[INT2.2](introspeccao.md#introspeccao-2); <br>
[L - Compartilhar](lexicos.md#compartilhar); <br>
 [C - Enviar um Pin](cenarios.md#enviar-um-pin); <br>
[DCU - Enviar um Pin](diagramas_caso_uso.md#enviar-um-pin); <br>
[ECU - Enviar um Pin](especificacoes_caso_uso.md#enviar-um-pin); <br>
[US17](backlog.md#us17); <br> [IS - Enviar Pin](iStar.md#enviar-pin)
### Elo

## EF22
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[INT2.3](introspeccao.md#introspeccao-2);<br>
[L - Comentar](lexicos.md#comentar); <br>
[C - Comentar em um Pin](cenarios.md#comentar-em-um-pin); <br>
[DCU - Comentar em um Pin](diagramas_caso_uso.md#comentar-em-um-pin); <br>
 [ECU - Comentar em um Pin](especificacoes_caso_uso.md#comentar-em-um-pin);
### Elo

## EF23
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[INT2.7](introspeccao.md#introspeccao-2); <br>
[L - Seguir](lexicos.md#seguir); <br>
[C - Seguir outro usuário](cenarios.md#seguir-outro-usuario); <br>
 [ECU - Seguir outro usuário](especificacoes_caso_uso.md#seguir-outro-usuario); <br>
[DCU - Seguir outro usuário](diagramas_caso_uso.md#seguir-outro-usuario); <br> [US23](backlog.md#us23); <br> [IS - Seguir usuário](iStar.md#seguir-usuario);
### Elo

## EF24
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[ST1.5](storytelling.md#storytelling-1-definindo-interesses-no-pinterest);<br>
 [L - Denunciar](lexicos.md#denunciar); <br>
[C - Denunciar Pin](cenarios.md#denunciar-pin); <br>
[ECU - Ocultar um Pin](especificacoes_caso_uso.md#ocultar-um-pin); <br>
 [DCU - Ocultar um Pin](diagramas_caso_uso.md#ocultar-um-pin); <br>
[ECU - Denunciar um Pin](especificacoes_caso_uso.md#denunciar-um-pin); <br>
[DCU - Denunciar Pin](diagramas_caso_uso.md#denuncar-pin); <br>
[US20](backlog.md#us20); <br> [US21](backlog.md#us21);
### Elo

## EF25
### Categoria
Desenvolvimento
### Elementos Rastreáveis[AP8](analise_protocolo.md#resultado-dos-requisitos); <br>
[US16](backlog.md#us16);
### Elo

## EF26
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[ENT3](entrevista.md#requisitos-elicitados); <br>
[L - Colaborar](lexicos.md#colaborar); <br>
[C - Compartilhar Pasta](cenarios.md#compartilhar-pasta); <br>
 [DCU - Compartilhar Pasta](diagramas_caso_uso.md#compartilhar-pasta); <br>
 [ECU - Compartilhar Pasta](especificacoes_caso_uso.md#compartilhar-pasta); <br> [US32](backlog.md#us32); <br> [US33](backlog.md#us33);
### Elo

## EF27
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[INT2.4](introspeccao.md#introspeccao-2);
### Elo

## EF28
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[AD4](analise_discurso.md#requisitos-elicitados);
### Elo

## EF29
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[AD10](analise_discurso.md#requisitos-elicitados); <br> [AD11](analise_discurso.md#requsiitos-elicitados); <br>
[L - Mensagem](lexicos.md#mensagem); <br>
[C - Enviar mensagem para outros usuários](cenarios.md#enviar-mensagem-para-outro-usuario); <br>
 [ECU - Enviar um Pin](especificacoes_caso_uso.md#enviar-um-pin); <br>
 [ECU - Enviar Mensagem para outros usuários](especificacoes_caso_uso.md#enviar-mensagem-para-outros-usuarios); <br>
 [DCU - Enviar Mensagem](diagramas_caso_uso.md#enviar-mensagem); <br>
 [IS - Enviar Pin (Usuário)](iStar.md#enviar-pin); <br>
[DCU - Enviar Pin](diagramas_caso_uso.md#enviar-um-pin);
### Elo

## EF30
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[AD8](analise_discurso.md#requisitos-elicitados); <br>
[L - Notificação](lexicos.md#notificacao); <br>
[C - Receber notificações](cenarios.md#receber-notificacoes); <br>
[DCU - Receber notificações](diagramas_caso_uso.md#receber-notificacoes); <br>
[ECU - Receber notificações](especificacoes_caso_uso.md#receber-notificacoes); <br> [US24](backlog.md#us24);
### Elo
