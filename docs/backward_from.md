# Introdução

Este artefato busca ligar cada requisito levantado aos respectivos métodos de elicitação e modelagem utilizados na disciplina.

# Backward-From

## Legenda

#### Modelagem

| Código | Significado |
|  :------: | ------ |
|  IS | iStar |
|  NFR | NFR Framework |
|  US | User Story |
|  ECU | Especificações de Caso de Uso |
|  DCU| Diagramas de Caso de Uso |
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

|  Código | Descrição | Fonte | Elicitação | Modelagem | Elo |
|  :------: | :------: | :------: | :------: | :------: | :------: |
|  RF1 | O app deve apresentar opções de micro-serviço (Facebook ou Google) e e-mail como forma de login e cadastro. | [Vincular suas Redes Sociais](backward_from.md#vincular-suas-redes-sociais) | [AP1](analise_protocolo.md#resultado-dos-requisitos) | [L16](lexicos.md#l16); <br> [C8](cenarios.md#c8); <br> [DCU10](diagramas_caso_uso.md#dcu-10); <br> [DCU11](diagramas_caso_uso.md#dcu-11); <br>[DCU3](diagramas_caso_uso.md#dcu-3) ;<br> [ECU - Fazer login](especificacoes_caso_uso.md#fazer-login); <br> [IStar- Cadastro no Pinterest](iStar.md#cadastro-no-pinterest) <br> [US12](backlog.md#us12); | [EF1](#ef1) |
|  RF2 | Ter um feed baseado nos interesses do usuário. | [Interesses do Pinterest](backward_from.md#interesses-no-pinterest) | [AP3](analise_protocolo.md#resultado-dos-requisitos) | [C- Definir interesses](cenarios.md#c5); <br> [L10](lexicos.md#l10); <br> [DCU7](diagramas_caso_uso.md#dcu-7); <br> [ECU - Definir Interesses](especificacoes_caso_uso.md#definir-interesses); <br> [IStar - Definir interesses](iStar.md#definir-interesses) <br> [US15](backlog.md#us15); | [EF2](#ef2) |
|  RF3 | O usuário deve poder visualizar os interesses a qualquer momento, de acordo com uma opção em seu perfil | [Interesses do Pinterest](backward_from.md#interesses-no-pinterest) | [AD2](analise_discurso.md#requisitos-elicitados); <br> [AD7](analise_discurso.md#requisitos-elicitados); <br> [AP3](analise_protocolo.md#resulyado-dos-requisitos);  | [L10](lexicos.md#l10); <br> [C5](cenarios.md#c5); <br> [IS - Definir Interesses (Usuário)](iStar.md#definir-interesses); <br> [DCU7](diagramas_caso_uso.md#dcu-7); <br> [US36](backlog.md#us36); | [EF3](#ef3) |
|  RF4 | O usuário deve ter a opção de salvar pins em um pasta | [Salvar Pins no Pinterest](backward_from.md#salvar-pins-no-pinterest) | [ST2.4](storytelling.md#storytelling-2-aprendendo-receitas-no-pinterest) | [C14](cenarios.md#c14); <br> [L2](lexicos.md#l2)<br> [DCU17](diagramas_caso_uso.md#dcu-17); <br> [ECU - Salvar um Pin](especificacoes_caso_uso.md#salvar-um-pin); <br> [US22](backlog.md#us22); | [EF4](#ef4) |
|  RF5 | O app deve possuir uma barra para pesquisa por texto. | [Produtos do Pinterest](backward_from.md#produtos-do-pinterest) | [AP13](analise_protocolo.md#resultado-dos-requisitos) | [C11](cenarios.md#c11); <br> [L31](lexicos.md#l31); <br> [DCU14](diagramas_caso_uso.md#dcu-14); <br> [ECU - Pesquisar por tema](especificacoes_caso_uso.md#pesquisar-por-tema); <br> [IS3](iStar.md#is3-pesquisar-pins); <br> [US34](backlog.md#us34); | [EF5](#ef5) |
|  RF6 | O App deve possibilitar a transferência de Pins entre pastas. | [Mover Pins para outra Pasta](backward_from.md#mover-pins-para-outra-pasta) | [ENT11](entrevista.md#requisitos-elicitados) | [DCU13](diagramas_caso_uso.md#dcu-13); <br> [L33](lexicos.md#l33); <br>[C10](cenarios.md#c10); <br> [US31](backlog.md#us31); | [EF6](#ef6) |
|  RF7 | O App deve permitir que o usuário impeça que determinado tipo de conteúdo seja mostrado em seu feed. | [Ocultar um Pin](backward_from.md#ocultar-um-pin) | [AD2](analise_discurso.md#requisitos-elicitados); | [L10](lexicos.md#l10); <br> [C5](cenarios.md#c5); <br> [L13](lexicos.md#l13); <br> [C20](cenarios.md#c20);<br> [DCU22](diagramas_caso_uso.md#dcu-22); <br> [US20](backlog.md#us20); | [EF7](#ef7) |
|  RF8 | O App deve obter vários dados de Pins bloqueados para identificar com precisão o tipo de conteúdo que o usuário não deseja visualizar. | [Ocultar um Pin](backward_from.md#ocultar-um-pin) | [ENT15](entrevista.md#requisitos-elicitados) | [L13](lexicos.md#l13); <br> [C20](cenarios.md#c20); <br>  [DCU22](diagramas_caso_uso.md#dcu-22); <br> [ECU - Ocultar um Pin](especificacoes_caso_uso.md#ocultar-um-pin); <br> [US20](backlog.md#us20); | [EF8](#ef8) |
|  RF9 | O app deve absorver a informação das categorias dos pins mais visualizados para usar nas próximas recomendações | [Política de Cookies](backward_from.md#politica-de-cookies) | [INT1.5](introspeccao.md#introspeccao-1) | [L10](lexicos.md#l10); <br> [US24](backlog.md#us24); | [EF9](#ef9) |
|  RF10 | O app deve separar os pins por categorias | [Interesses do Pinterest](backward_from.md#interesses-no-pinterest) | [INT1.6](introspeccao.md#introspeccao-1) | [L1](lexicos.md#l1); <br> [L31](lexicos.md#l31); <br> [US34](backlog.md#us34); | [EF10](#ef10) |
|  RF11 | O usuário deve ter a opção de avaliar pins e essa avaliação deve ser aberta a outros usuários | [Interesses do Pinterest](backward_from.md#interesses-no-pinterest) | [INT1.8](introspeccao.md#introspeccao-1) | [L23](lexicos.md#l23); <br> [C2](cenarios.md#c2); <br> [DCU4](diagramas_caso_uso.md#dcu-4); <br> [US15](backlog.md#us15); | [EF11](#ef11) |
|  RF12 | O App deve possibilitar que o usuário reorganize os Pins salvos em diferentes subpastas. | [Organizar Pastas no Pinterest](backward_from.md#organizar-pastas-no-pinterest) | [ENT10](entrevista.md#requisitos-elicitados) | [L33](lexicos.md#l33); <br> [L4](lexicos.md#l4); <br> [US30](backlog.md#us30); <br> [US31](backlog.md#us31); <br> [C- Orgaizar Pasta](cenarios.md#c10); <br> [DCU13](diagramas_caso_uso.md#dcu-13); | [EF12](#ef12) |
|  RF13 | Ao clicar no pin o usuário deve conseguir ver mais informações sobre ele, como uma pequena ou grande descrição | [Pins patrocinados](backward_from.md#pins-patrocinados) | [ST2.3](storytelling.md#storytelling-2-aprendendo-receitas-no-pinterest); <br> [INT2.4](introspeccao.md#introspeccao-2); | [DCU3](diagramas_caso_uso.md#dcu-3); <br> [ECU - Visualizar Pin](especificacoes_caso_uso.md#visualizar-pin); <br> [US15](backlog.md#us15); | [EF13](#ef13) |
|  RF14 | O usuário deve poder adicionar novos interesses a qualquer momento após o cadastro, através de uma opção em seu perfil | [Interesses do Pinterest](backward_from.md#interesses-no-pinterest) | [ST1.3](storytelling.md#storytelling-1-definindo-interesses-no-pinterest); | [C5](cenarios.md#c5); <br> [L10](lexicos.md#l10); <br> [DCU7](diagramas_caso_uso.md#dcu-7); <br> [US36](backlog.md#us36); <br> [IS1](iStar.md#is1-definir-interesses); | [EF14](#ef14) |
|  RF15 | O usuário deve poder salvar seus pins no seu dispositivo | [Pinterest Labs](backward_from.md#pinterest-labs) | [AP4](analise_protocolo.md#resultado-dos-requisitos) | [US22](backlog.md#us22); <br> [L2](lexicos.md#l2); <br> [C- Salvar um Pin](cenarios.md#c14); <br> [DCU17](diagramas_caso_uso.md#dcu-17); | [EF15](#ef15) |
|  RF16 | Manter pastas | [Organizar Pastas no Pinterest](backward_from.md#organizar-pastas-no-pinterest) | [ENT11](entrevista.md#requisitos-elicitados); <br> [ST2.5](storytelling.md#storytelling-2-aprendendo-receitas-no-pinterest); <br> [ENT3](entrevista.md#requisitos-elicitados);   | [US29](backlog.md#us29); <br> [US31](backlog.md#us31); <br> [L3](lexicos.md#l3); <br> [L33](lexicos.md#l33); <br> [L28](lexicos.md#l28); <br> [C4](cenarios.md#c4); <br>[C10](cenarios.md#c10); <br>  [DCU6](diagramas_caso_uso.md#dcu-6); <br> [DCU13](diagramas_caso_uso.md#dcu-13); | [EF16](#ef16) |
|  RF17 | Manter subpastas | [Organizar Pastas no Pinterest](backward_from.md#organizar-pastas-no-pinterest) | [ENT10](entrevista.md#requisitos-elicitados) | [US30](backlog.md#us30); <br> [L4](lexicos.md#l4); <br> [US31](backlog.md#us31); <br> [L33](lexicos.md#l33); <br> [L28](lexicos.md#l28); <br> [C4](cenarios.md#c4); <br>[C10](cenarios.md#c10); <br>  [DCU6](diagramas_caso_uso.md#dcu-6); <br> [DCU13](diagramas_caso_uso.md#dcu-13); <br> [ECU - Criar Pasta](especificacoes_caso_uso.md#criar-pasta); <br> [ECU - Organizar Pasta](especificacoes_caso_uso.md#organizar-pasta); | [EF17](#ef17) |
|  RF18 | A plataforma deve disponibilizar uma forma de pesquisa por imagem. | [Produtos do Pinterest](backward_from.md#produtos-do-pinterest) | [AP12](analise_protocolo.md#resultado-dos-requisitos); <br> [AD14](analise_discurso.md#requisitos-elicitados) | [US35](backlog.md#us35); [L31](lexicos.md#l31); <br> [C12](cenarios.md#c12); <br> [DCU15](diagramas_caso_uso.md#dcu-15); | [EF18](#ef18) |
|  RF19 | O usuário deve poder ser redirecionado para o link da imagem de um pin, caso haja um. | [Pins patrocinados](backward_from.md#pins-patrocinados) | [AP14](analise_protocolo.md#resultado-dos-requisitos) | [US16](backlog.md#us16); <br> [L5](lexicos.md#l5); <br> [C9](cenarios.md#c9);  | [EF19](#ef19) |
|  RF20 | O usuário deve conseguir compartilhar pins com outros usuários | [Enviar pins, pastas e perfis](backward_from.md#enviar-pins-pastas-e-perfis) | [AD12](analise_discurso.md#requisitos-elicitados) | [US17](backlog.md#us17); <br> [L12](lexicos.md#l12); <br> [L14](lexicos.md#l14); <br> [C7](cenarios.md#c7); <br> [IS7](iStar.md#is7-enviar-pin); <br> [DCU9](diagramas_caso_uso.md#dcu-9); | [EF20](#ef20) |
|  RF21 | O usuário deve conseguir compartilhar pins em redes sociais | [Compartilhar Pins e Pastas em redes sociais](backward_from.md#compartilhar-pins-e-pastas-em-redes-sociais) | [INT2.2](introspeccao.md#introspeccao-2) | [L12](lexicos.md#l12); <br>  [C7](cenarios.md#c7); <br> [DCU9](diagramas_caso_uso.md#dcu-9); <br><br/>[ECU - Enviar um Pin](especificacoes_caso_uso.md#enviar-um-pin); <br> [US17](backlog.md#us17); <br> [IS9](iStar.md#is9-enviar-pin) | [EF21](#ef21) |
|  RF22 | A aplicação deve colocar nos pins a opção de "comentários" | [Comentar em um Pin](backward_from.md#comentar-em-um-pin) | [INT2.3](introspeccao.md#introspeccao-2) | [L23](lexicos.md#l23); <br>  [C2](cenarios.md#c2); <br> [DCU4](diagramas_caso_uso.md#dcu-4); <br> [ECU -  Comentar em um Pin](especificacoes_caso_uso.md#comentar-em-um-pin); <br> [US15](backlog.md#us15); | [EF22](#ef22) |
|  RF23 | O Pinterest deve oferecer a opção de seguir usuários | [Encontrar e seguir amigos](backward_from.md#encontrar-e-seguir-amigos) | [INT2.7](introspeccao.md#introspeccao-2) | [L8](lexicos.md#l8); <br> [C13](cenarios.md#c13); <br> [ECU - Seguir outro usuário](especificacoes_caso_uso.md#seguir-outro-usuario); <br> [DCU16](diagramas_caso_uso.md#dcu-16); <br> [US23](backlog.md#us23); <br> [IS4](iStar.md#is4-seguir-usuario) | [EF23](#ef23) |
|  RF24 | O usuário deve poder ocultar e denunciar pins. | [Ocultar um Pin](backward_from.md#ocultar-um-pin) e [Denunciar algo no Pinterest](backward_from.md#denunciar-algo-no-pinterest) | [ST1.5](storytelling.md#storytelling-1-definindo-interesses-no-pinterest); |  [L34](lexicos.md#l34); <br> [C21](cenarios.md#c21); <br> [ECU - Ocultar um Pin](especificacoes_caso_uso.md#ocultar-um-pin); <br> [DCU22](diagramas_caso_uso.md#dcu-22); <br> [ECU - Denunciar um Pin](especificacoes_caso_uso.md#denunciar-um-pin); <br>[DCU23](diagramas_caso_uso.md#dcu-23); <br> [US20](backlog.md#us20); <br>  [US21](backlog.md#us21);  | [EF24](#ef24) |
|  RF25 | O aplicativo deve apresentar um navegador interno para redirecionamento de links presentes em pins. | [Navegador do Pinterest](backward_from.md#navegador-do-pinterest) | [AP8](analise_protocolo.md#resultado-dos-requisitos) | [US16](backlog.md#us16); | [EF25](#ef25) |
|  RF26 | O app deve possuir a função de compartilhar a edição de pastas com outros usuários. | [Convidar amigos para uma pasta](backward_from.md#convidar-amigos-para-uma-pasta)<code>&#124;</code> [ENT3](entrevista.md#requisitos-elicitados) | [ENT3](entrevista.md#requisitos-elicitados) | [L26](lexicos.md#l26); <br> [C3](cenarios.md#c3); <br> [DCU5](diagramas_caso_uso.md#dcu-5); <br> [ECU - Compartilhar Pasta](especificacoes_caso_uso.md#compartilhar-pasta); <br> [US32](backlog.md#us32); <br> [US33](backlog.md#us33);  | [EF26](#ef26) |
|  RF27 | As receitas devem ser pins especiais que ofereçam tempo, porções e ingredientes para instigar o usuário a fazê-la. | [Experimentar um Pin](backward_from.md#experimentar-um-pin) | [INT2.4](introspeccao.md#introspeccao-2); | [US15](backlog.md#us15); | [EF27](#ef27) |
|  RF28 | O Aplicativo deve ser capaz de extrapolar dados de pesquisa de outras fontes para trazer itens mais relevantes para o usuário. | [Política de Cookies](backward_from.md#politica-de-cookies) | [AD4](analise_discurso.md#requisitos-elicitados) | [US39](backlog.md#us39); | [EF28](#ef28) |
|  RF29 | O usuário deve poder enviar mensagem para outros usuários. | [Enviar mensagens](backward_from.md#enviar-mensagens) | [AD10](analise_discurso.md#requisitos-elicitados); <br> [AD11](analise_discurso.md#requsiitos-elicitados); | [L18](lexicos.md#l18); <br> [C17](cenarios.md#enviar-mensagem-para-outro-usuario); <br> [ECU - Enviar um Pin](especificacoes_caso_uso.md#enviar-um-pin); <br> [ECU - Enviar Mensagem para outros usuários](especificacoes_caso_uso.md#enviar-mensagem-para-outros-usuarios); <br>  [DCU1](diagramas_caso_uso.md#dcu-1); <br> [IS7](iStar.md#is7-enviar-pin); <br> [DCU9](diagramas_caso_uso.md#dcu-9); <br> [US28](backlog.md#us28); | [EF29](#ef29) |
|  RF30 | O usuário deve receber notificações sobre novidades no app. | [Pinterest Labs](backward_from.md#pinterest-labs) | [AD8](analise_discurso.md#requisitos-elicitados);  | [L19](lexicos.md#l19); <br> [C18](cenarios.md#c18); <br> [DCU20](diagramas_caso_uso.md#dcu-20); <br> [ECU - Receber notificações](especificacoes_caso_uso.md#receber-notificacoes); <br> [US24](backlog.md#us24); | [EF30](#ef30) |
|  RF31 | O usuário deve poder editar seu perfil. | [Perfil no Pinterest](backward_from.md#perfil-no-pinterest) | - | [C24](cenarios.md#c24); <br> [ECU - Editar perfil](especificacoes_caso_uso.md#editar-perfil); <br> [DCU26](diagramas_caso_uso.md#dcu-26); <br> [US37](backlog.md#us37); <br> [IS5](iStar.md#is5-editar-configuracoes-de-conta) | [EF31](#ef31) |
|  RF32 | Os pins que se referem a aplicativos devem mostrar a opção de instalar. | [Direcionamentos à lojas de download de aplicativos](backward_from.md#direcionamentos-a-lojas-de-download-de-aplicativos) | [INT2.4](introspeccao.md#introspeccao-2); | [US16](backlog.md#us16); | [EF32](#ef32) |
|  RF33 | O pinterest deve manter algum canal de comunicação com usuário no caso de dúvidas ou problemas ocorridos com o usuário. | [Política de Privacidade do Pinterest](backward_from.md#politica-de-privacidade-do-pinterest) | - | [NFR6](nfr.md#nfr6-suporte); <br> [C21](cenarios.md#c21); <br> [L34](lexicos.md#l34); <br> [DCU23](diagramas_caso_uso.md#dcu-23); <br> [US21](backlog.md#us21); | [EF33](#ef33) |
|  RF34 | O Usuário deve poder remover interesses em qualquer momento após o cadastro, acessando essa opção na aba de perfil | [Interesses do Pinterest](backward_from.md#interesses-no-pinterest) | [ST1.3](storytelling.md#storytelling-1-definindo-interesses-no-pinterest); | [C5](cenarios.md#c5); <br> [L10](lexicos.md#l10); <br> [DCU7](diagramas_caso_uso.md#dcu-7); <br> [IS1](iStar.md#is1-definir-interesses); <br> [US36](backlog.md#us36); | [EF34](#ef34) |
|  RF35 | O Usuário deve possuir mais de uma opção de formas de ordenação das pastas na página de perfil, como ordem alfabética, últimos salvos, mais antigas, mais recentes ou pelo arraste dos elementos. | [Organizar Pastas no Pinterest](backward_from.md#organizar-pastas-no-pinterest) | [ST2.5](storytelling.md#storytelling-2-aprendendo-receitas-no-pinterest);  |  [L33](lexicos.md#l33); <br> [C10](cenarios.md#c10); <br> [ECU - Classificação de Pastas](especificacoes_caso_uso.md#classificacao-de-pastas); <br> [ECU - Organizar Pasta](especificacoes_caso_uso.md#organizar-pasta); <br> [IS2](iStar.md#is2-classificar-pastas); <br> [DCU21](diagramas_caso_uso.md#dcu-21); <br> [US31](backlog.md#us31); <br> [US25](backlog.md#us2); | [EF35](#ef35) |
|  RF36 | O Pinterest deve notificar usuários de outros usuários com interesses semelhantes | [Interesses do Pinterest](backward_from.md#interesses-no-pinterest) | - | [L19](lexicos.md#l19); <br> [C18](cenarios.md#c18); <br> [IS- Seguir Usuário](iStar.md#seguir-usuario) <br> [US24](backlog.md#us24); | [EF36](#ef36) |
|  RF37 | O Usuário deve poder ocultar seu perfil e seus dados de mecanismos de pesquisa | [Política de Cookies](backward_from.md#politica-de-cookies) | - | [US37](backlog.md#us37); <br> [IS5](iStar.md#is5-editar-configuracoes-de-conta) | [EF37](#ef37) |
|  RF38 | O Pinterest deve poder utilizar dados, como cookies, para identificar informações de perfil do usuário e direcionar recomendações de pins | [Política de Cookies](backward_from.md#politica-de-cookies) | [AD4](analise_discurso.md#requisitos-elicitados);  | [IS5](iStar.md#is5-editar-configuracoes-de-conta) <br> [US39](backlog.md#us39) | [EF38](#ef38) |
|  RF39 | O Usuário deve poder definir informações pessoais, como seu gênero, nome de usuário, imagem de perfil e descrição, por meio de uma opção ao editar perfil ou se cadastrar | [Perfil no Pinterest](backward_from.md#perfil-no-pinterest) e [Política de Privacidade do Pinterest](backward_from.md#politica-de-privacidade-do-pinterest) | - | [US37](backlog.md#us37); <br> [IS6](iStar.md#is6-cadastro-no-pinterest); <br> [DCU26](diagramas_caso_uso.md#dcu-26); <br> [ECU - Editar Perfil](especificacoes_caso_uso.md#editar-perfil); <br> [C24](cenarios.md#c24) <br> [US38](backlog.md#us38); | [EF39](#ef39) |
|  RF40 | O Usuário deve poder definir em qual língua irá utilizar o aplicativo, seja na edição do perfil ou no cadastro | [Perfil no Pinterest](backward_from.md#perfil-no-pinterest) e [Política de Privacidade do Pinterest](backward_from.md#politica-de-privacidade-do-pinterest) | [AD6](analise_discurso.md#requisitos-elicitados);  | [IS6](iStar.md#is6-cadastro-no-pinterest);  <br> [DCU26](diagramas_caso_uso.md#dcu-26); <br> [US38](backlog.md#us38); | [EF40](#ef40) |
|  RF41 | O Usuário deve poder postar e editar posteriormente um Pin | [Editar ou excluir um Pin](backward_from.md#editar-ou-excluir-um-pin) | - | [C6](cenarios.md#c6); <br> [DCU8](diagramas_caso_uso.md#dcu-8); <br> [ECU - Editar um Pin](especificacoes_caso_uso.md#editar-um-pin); <br> [IS8](iStar.md#is8-enviar-pin); <br> [US18](backlog.md#us18) | [EF41](#ef41) |
|  RF42 | O Usuário deve poder postar pins a partir de imagens da galeria do dispositivo | [Criar um Pin a partir da galeria de fotos](backward_from.md#criar-um-pin-a-partir-da-galeria-de-fotos) | - | [IS8](iStar.md#is8-enviar-pin) <br> [US18](backlog.md#us18) | [EF42](#ef42) |
|  RF43 | O Usuário deve definir informações do pin postado, como categorias, título e descrição | [Editar ou excluir um Pin](backward_from.md#editar-ou-excluir-um-pin) | [INT2.4](introspeccao.md#introspeccao-2); | [C6](cenarios.md#c6); <br> [DCU8](diagramas_caso_uso.md#dcu-8); <br> [ECU - Editar um Pin](especificacoes_caso_uso.md#editar-um-pin); <br> [IS8](iStar.md#is8-enviar-pin) <br> [US15](backlog.md#us15); | [EF43](#ef43) |
|  RF44 | O Usuário deve possuir formas de alterar escolhas em qualquer momento, como informações de perfil ou de postagem de pins, permitindo a correção de erros | [Perfil no Pinterest](backward_from.md#perfil-no-pinterest) | - | [NFR3](nfr.md#nfr3-usabilidade); <br> [US37](backlog.md#us37); <br> [US38](backlog.md#us38); | [EF44](#ef44) |
|  RF45 | O app deve permitir a escolha de interesses no primeiro acesso (no mínimo 5, obrigatoriamente), para que o Pinterest possa mapear os interesses do usuário. | [Interesses do Pinterest](backward_from.md#interesses-no-pinterest) | [AP2](analise_protocolo.md#resultado-dos-requisitos); <br> [ST1.1](storytelling.md#storytelling-1-definindo-interesses-no-pinterest); | [DCU10](diagramas_caso_uso.md#dcu-10); <br>  [ECU - Realizar primeiro login](especificacoes_caso_uso.md#realizar-primeiro-login); <br> [IS6](iStar.md#is6-cadastro-no-pinterest); <br> [US13](backlog.md#us13); | [EF45](#ef45) |
|  RF46 | A aplicação deve conter um sistema de scroll infinito que possibilite ao usuário uma visualização mais orgânica do feed. | - | [AP7](analise_protocolo.md#resultado-dos-requisitos) | [L15](lexicos.md#l15); <br> [DCU18](diagramas_caso_uso.md#dcu-18); <br> [C15](cenarios.md#c15); <br> [ECU - Visualizar Feed](especificacoes_caso_uso.md#visualizar-feed); <br> [US15](backlog.md#us15); | [EF46](#ef46) |
|  RF47 | O App deve sugerir Pins sobre assuntos pesquisados recentemente pelo usuário. | [Política de Cookies](backward_from.md#politica-de-cookies) | [AD5](analise_discurso.md#requisitos-elicitados)<br> [ENT12](entrevista.md#requisitos-elicitados) | [US24](backlog.md#us24); <br> [US36](backlog.md#us36); [C5](cenarios.md#c5); <br> [C11](cenarios.md#c11); <br> [C12](cenarios.md#c12); <br> [L11](lexicos.md#l11); <br>  [DCU7](diagramas_caso_uso.md#dcu-7); <br> [DCU14](diagramas_caso_uso.md#dcu-14); <br> [DCU15](diagramas_caso_uso.md#dcu-15); <br> [ECU - Pesquisar por Tema](especificacoes_caso_uso.md#pesquisar-por-tema); <br> [ECU - Pesquisar por Foto](especificacoes_caso_uso.md#pesquisar-por-foto); <br> [IS1](nfr.md#definir-interesses); <br> [IS3](nfr.md#pesquisar-pins) | [EF47](#ef47) |
|  RF48 | Ao pesquisar sobre algo, o Pinterest deve mostrar opções de filtro sobre o assunto, para que o usuário apenas clique em um e receba um resultado mais selecionado | [Produtos do Pinterest](backward_from.md#produtos-do-pinterest) | [INT2.5](introspeccao.md#introspeccao-2) | [C11](cenarios.md#c11); <br> [ECU - Pesquisar por tema](especificacoes_caso_uso.md#pesquisar-por-tema); <br> [DCU14](diagramas_caso_uso.md#dcu-14); <br> [IS3](iStar.md#is3-pesquisar-pins); <br> [C12](cenarios.md#c12); <br> [DCU15](diagramas_caso_uso.md#dcu-15); <br> [ECU - Pesquisar por Foto](especificacoes_caso_uso.md#pesquisar-por-foto) <br> [US34](backlog.md#us34); <br>  [US35](backlog.md#us35); | [EF48](#ef48) |
|  RF49 | Os pins devem oferecer informações sobre o motivo dele estar aparecendo para o usuário. | [Política de Privacidade do Pinterest](backward_from.md#politica-de-privacidade-do-pinterest) | [ST1.4](storytelling.md#storytelling-1-definindo-interesses-no-pinterest) | [US19](backlog.md#us19); | [EF49](#ef49) |
|  RF50 | O usuário deve ter o ferramental necessário para realizar as etapas de uma receita sem precisar sair do app | [Experimentar um Pin](backward_from.md#experimentar-um-pin) | [INT1.10](introspeccao.md#introspeccao-1) | [DCU3](diagramas_caso_uso.md#dcu-3); <br> [L22](lexicos.md#l22); <br> [US15](backlog.md#us15); | [EF50](#ef50) |
|  RF51 | O Aplicativo deve identificar a perda de interesse do usuário por um tema pela frequência de pesquisas. | [Interesses do Pinterest](backward_from.md#interesses-no-pinterest) | [AD7](analise_discurso.md#requisitos-elicitados); <br> | [US15](backlog.md#us15); <br> [US36](backlog.md#us36); [C5](cenarios.md#c5); <br> [C11](cenarios.md#c11); <br> [C12](cenarios.md#c12); <br> [L11](lexicos.md#l11); <br>  [DCU7](diagramas_caso_uso.md#dcu-7); <br> [DCU14](diagramas_caso_uso.md#dcu-14); <br> [DCU15](diagramas_caso_uso.md#dcu-15); <br> [ECU - Pesquisar por Tema](especificacoes_caso_uso.md#pesquisar-por-tema); <br> [ECU - Pesquisar por Foto](especificacoes_caso_uso.md#pesquisar-por-foto); <br> [IS1](nfr.md#definir-interesses); <br> [IS3](nfr.md#pesquisar-pins) | [EF51](#ef51) |
|  RF52 | O Usuário deve possuir a possibilidade de personalizar a forma em que suas pastas serão visualizadas | [Organizar Pastas no Pinterest](backward_from.md#organizar-pastas-no-pinterest) | [ST2.5](storytelling.md#storytelling-2-aprendendo-receitas-no-pinterest) | [IS2](iStar.md#is2-classificar-pastas); <br> [L30](lexicos.md#l30); <br> [US25](backlog.md#us25); | [EF52](#ef52) |

## Tabela de Requisitos Não Funcionais

|  Código | Descrição | Fonte | Elicitação | Modelagem |
|  :------: | :------: | :------: | :------: | :------: |
|  RNF1 | O sistema deve prever e tratar falhas | NIELSEN, Jakob. Usability engineering, page 145. Elsevier, 1994. | - | [NFR1](nfr.md#nfr1-confiabilidade); |
|  RNF2 | O Pinterest deve se proteger e proteger ao usuário juridicamente | [Política de Privacidade do Pinterest](backward_from.md#politica-de-privacidade-do-pinterest) | - | [NFR6](nfr.md#nfr6-suporte); |
|  RNF3 | O app deve ter semelhança de design entre suas diferentes plataformas | NIELSEN, Jakob. Usability engineering, page 88. Elsevier, 1994. | - | [NFR2](nfr.md#nfr2-conectividade) |
|  RNF4 | As mensagens do Pinterest para o usuário devem ser claras e de fácil entendimento | NIELSEN, Jakob. Usability engineering, page 115. Elsevier, 1994. | - | [NFR7](nfr.md#seguranca) |
|  RNF5 | A aplicação deve buscar utilizar o menor espaço possível de armazenamento no dispositivo  do usuário | - | - | [NFR5](nfr.md#nfr5-desempenho) |
|  RNF6 | O app deve oferecer mais conteúdo relacionado às atividades recentes | NIELSEN, Jakob. Designing web usability: The practice of simplicity, page 36. New Riders Publishing, 1999.  | [ENT12](entrevista.md#requisitos-elicitados); <br> [ST2.1](storytelling.md#storytelling-2-aprendendo-receitas-no-pinterest) | [L11](lexicos.md#l11); <br> [L27](lexicos.md#l27); <br> [NFR2](nfr.md#nfr2-conectividade): |
|  RNF7 | O sistema deve combater conteúdos indesejados | [Diretrizes da Comunidade do Pinterest](backward_from.md#diretrizes-da-comunidade-do-pinterest) | - | [NFR7](nfr.md#seguranca); |
|  RNF8 | A interface do usuário deve ser agradável para melhorar as experiências e torná-las excelentes | NIELSEN, Jakob. Usability engineering, page 102. Elsevier, 1994. | [Q4](questionario.md#requisitos-elicitados); | [NFR3](nfr.md#nfr3-usabilidade); <br> [NFR4](nfr.md#nfr4-usabilidade-design); <br> [NFR5](nfr.md#nfr5-desempenho); |
|  RNF9 | A rede social deve incluir sempre novos conteúdos sobre os temas mais pesquisados em busca de mantê-los atualizados, mas também procurar abranger temas diferentes para atrair novos públicos específicos, como os praticantes de esportes, por exemplo | NIELSEN, Jakob. Designing web usability: The practice of simplicity, page 36. New Riders Publishing, 1999.  | [Q5](questionario.md#requisitos-elicitados);  | [L11](lexicos.md#l11); <br> [L10](lexicos.md#l10); <br> [IS8](iStar.md#is8-outro-usuario); <br> [IS10](iStar.md#is10-geral); <br> [NFR2](nfr.md#nfr2-conectividade): |
|  RNF10 | O sistema deve prover uma autenticação segura | [Diretrizes da Comunidade do Pinterest](backward_from.md#diretrizes-da-comunidade-do-pinterest) | - | [NFR7](nfr.md#seguranca); |
|  RNF11 | O app deve ser de rápida aprendizagem. | NIELSEN, Jakob. Usability engineering, page 88. Elsevier, 1994. | - | [NFR3](nfr.md#nfr3-usabilidade) |
|  RNF12 | O Pinterest deve oferecer oportunidade de expensão de interesses para o usuário | [Interesses do Pinterest](backward_from.md#interesses-no-pinterest) | - | [NFR2](nfr.md#nfr2-conectividade) |
|  RNF13 | O Pinterest deve identificar gostos de usuários em diferentes ambientes ou aplicativos, permitindo um conteúdo mais personalizado e direcionado, aumentando a identificação com os interesses definidos | NIELSEN, Jakob. Usability engineering, page 73. Elsevier, 1994. | [AD7](analise_discurso.md#requisitos-elicitados); | [IS5](iStar.md#is5-editar-configuracoes-de-conta) <br> [US39](backlog.md#us39); <br> [NFR2](nfr.md#nfr2-conectividade) |
|  RNF14 | O Pinterest deve possuir feedbacks objetivos para informar o usuário da realização de tarefas pouco visuais, como copiar um link, aplicados principalmente para a versão mobile | NIELSEN, Jakob. Usability engineering, page 221. Elsevier, 1994. | - | [IS7](iStar.md#is7-enviar-pin); <br> [NFR3](nfr.md#nfr3-usabilidade); |
|  RNF15 | O pinterest deve possuir interação fluida entre as funcionalidades, de maneira que o usuário entenda todo o processo do fluxo. | NIELSEN, Jakob. Usability engineering, page 239. Elsevier, 1994. | - | [IS8](iStar.md#is8-enviar-pin); <br> [NFR3](nfr.md#nfr3-usabilidade); |
|  RNF16 | O pinterest deve possuir o menor tempo possivel para responder as ações requisitada pelo usuário.  | NIELSEN, Jakob. Usability engineering, page 109. Elsevier, 1994. | - | [NFR4](nfr.md#nfr4-usabilidade-design) <br> [IS10](iStar.md#is10-geral) |
|  RNF17 | O pinterest deve manter políticas de moderação de seu conteúdo dentro da aplicação. | [Diretrizes da Comunidade do Pinterest](backward_from.md#diretrizes-da-comunidade-do-pinterest) | - | [NFR7](nfr.md#seguranca);<br> [C20](cenarios.md#ocultar-pin); <br> [C21](cenarios.md#c21) |
|  RNF18 | O pinterest deve manter a integridade dos dados fornecidos pelo usuário em sua conta. | [Política de Privacidade do Pinterest](backward_from.md#politica-de-privacidade-do-pinterest) | - | [NFR7](nfr.md#seguranca); |

# Elos Funcionais

## EF1
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L16](lexicos.md#l16); <br> [C8](cenarios.md#c8); <br>
[DCU10](diagramas_caso_uso.md#dcu-10); <br>
[DCU11](diagramas_caso_uso.md#dcu-18); <br>
[DCU2](diagramas_caso_uso.md#dcu-2) ;<br>
[ECU - Fazer login](especificacoes_caso_uso.md#fazer-login); <br>
 [IStar- Cadastro no Pinterest](iStar.md#cadastro-no-pinterest) <br>
[US12](backlog.md#us12);
### Elo
**Representação**: [DCU- 11](diagramas_caso_uso.md#dcu-18) representa [C8](cenarios.md#c8); <br>
**Representação**: [IStar- Cadastro no Pinterest](iStar.md#cadastro-no-pinterest) representa [DCU2](diagramas_caso_uso.md#dcu-2) ; <br>
**Alocação** : [ECU - Fazer login](especificacoes_caso_uso.md#fazer-login) alocado em [US12](backlog.md#us12)

## EF2
### Categoria
Desenvolvimento

### Elementos Rastreáveis
[C- Definir interesses](cenarios.md#c5); <br>
[L10](lexicos.md#l10); <br>
[DC 7](diagramas_caso_uso.md#dcu-7); <br>
[ECU - Definir Interesses](especificacoes_caso_uso.md#definir-interesses); <br>
[IS1](iStar.md#is1-definir-interesses) <br>
[US15](backlog.md#us15); <br>
### Elo
**Representação**:  [ECU - Definir Interesses](especificacoes_caso_uso.md#definir-interesses) representa [DCU7](diagramas_caso_uso.md#dcu-7) e [C- Definir interesses](cenarios.md#c5) <br>
**Representação**: [IS1](iStar.md#is1-definir-interesses) representa [ECU - Definir Interesses](especificacoes_caso_uso.md#definir-interesses) <br>
**Alocação** :[ECU - Definir Interesses](especificacoes_caso_uso.md#definir-interesses) alocado em [US15](backlog.md#us15)  <br>

## EF3
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L10](lexicos.md#l10); <br>
[C5](cenarios.md#c5); <br>
[IS1](iStar.md#is1-definir-interesses); <br>
[ DCU7](diagramas_caso_uso.md#dcu-7); <br> [US36](backlog.md#us36); <br>
### Elo
**Representação**:   [IS1](iStar.md#is1-definir-interesses) representa [ECU - Definir Interesses](especificacoes_caso_uso.md#definir-interesses)  <br>
**Alocação** :  [ DCU7](diagramas_caso_uso.md#dcu-7) alocado em [US36](backlog.md#us36)

## EF4
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[C14](cenarios.md#c14); <br>
[L2](lexicos.md#l2)<br>
 [DCU17 ](diagramas_caso_uso.md#dcu-17); <br>
 [ECU - Salvar um Pin](especificacoes_caso_uso.md#salvar-um-pin); <br>
[US22](backlog.md#us22);
### Elo
**Representação**: [ECU - Salvar um Pin](especificacoes_caso_uso.md#salvar-um-pin) representa [DCU17](diagramas_caso_uso.md#dcu-17) e [C14](cenarios.md#c14) <br>
**Alocação** :  [ DCU7](diagramas_caso_uso.md#dcu-7) alocado em [US36](backlog.md#us22) <br>

## EF5
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[AP13](analise_protocolo.md#resultado-dos-requisitos); <br>
[C11](cenarios.md#c11); <br>
 [L31](lexicos.md#l31); <br>
 [DCU14](diagramas_caso_uso.md#dcu-14); <br>
 [ECU - Pesquisar por tema](especificacoes_caso_uso.md#pesquisar-por-tema); <br>
 [IS3](iStar.md#is3-pesquisar-pins); <br>
 [US34](backlog.md#us34);<br>
### Elo
**Representação**: [ECU - Pesquisar por tema](especificacoes_caso_uso.md#salvar-um-pin),  [DCU14](diagramas_caso_uso.md#dcu-14) representa [C11](cenarios.md#c11) <br>
**Alocação**:  [ECU - Pesquisar por tema](especificacoes_caso_uso.md#pesquisar-por-tema)  alocado em [US34](backlog.md#us34). <br>

## EF6
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[DCU13](diagramas_caso_uso.md#dcu-13); <br>
 [L33](lexicos.md#l33); <br>
[C10](cenarios.md#c10); <br>
 [US31](backlog.md#us31); <br>
### Elo
**Representação**: [DCU13](diagramas_caso_uso.md#dcu-13), [DCU13](diagramas_caso_uso.md#dcu-13) representa[C10](cenarios.md#c10). <br>
**Alocação** : [ECU - Organizar Pastas](especificacoes_caso_uso.md#organizar-pasta) alocado em [US31](backlog.md#us31). <br>

## EF7
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L10](lexicos.md#l10); <br>
[C5](cenarios.md#c5); <br>
 [L13](lexicos.md#l13); <br>
 [C20](cenarios.md#c20); <br>
 [DCU22](diagramas_caso_uso.md#dcu-22); <br>
[US20](backlog.md#us20); <br>
### Elo
--

## EF8
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L13](lexicos.md#l13); <br>
 [C20](cenarios.md#c20); <br>
 [DCU22](diagramas_caso_uso.md#dcu-22); <br>
[ECU - Ocultar um Pin](especificacoes_caso_uso.md#ocultar-um-pin); <br> [US20](backlog.md#us20); <br>
### Elo
**Representação**:  [ECU - Denunciar um Pin](especificacoes_caso_uso.md#denunciar-um-pin) representa [DCU23](diagramas_caso_uso.md#dcu-23) e [C21](cenarios.md#c21) <br>
**Alocação**: [ECU - Ocultar um Pin](especificacoes_caso_uso.md#ocultar-um-pin) esta alocado em [US20](backlog.md#us20). <br>

## EF9
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L10](lexicos.md#l10); <br>
 [US24](backlog.md#us24); <br>
### Elo
--

## EF10
### Categoria
Desenvolvimento
### Elementos Rastreáveis
 [L1](lexicos.md#l1); <br>
 [L31](lexicos.md#l31); <br>
 [US34](backlog.md#us34); <br>
### Elo
--

## EF11
### Categoria
Desenvolvimento
### Elementos Rastreáveis
 [L23](lexicos.md#l23); <br>
 [C2](cenarios.md#c2); <br>
 [DCU4](diagramas_caso_uso.md#dcu-4); <br> [US15](backlog.md#us15);<br>
### Elo
--

## EF12
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L33](lexicos.md#l33); <br>
[L4](lexicos.md#l4); <br>
 [C- Orgaizar Pasta](cenarios.md#c10); <br>
[DCU13](diagramas_caso_uso.md#dcu-13);<br>
[US30](backlog.md#us30); <br>
 [US31](backlog.md#us31); <br>
### Elo
**Representação**: [DCU13](diagramas_caso_uso.md#dcu-13) representa  [C- Orgaizar Pasta](cenarios.md#c10) <br>
**Alocação**: [DCU13](diagramas_caso_uso.md#dcu-13) está alocado em [US30](backlog.md#us30) e [US31](backlog.md#us31) <br>

## EF13
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[DCU3](diagramas_caso_uso.md#dcu-3); <br>
[ECU - Visualizar Pin](especificacoes_caso_uso.md#visualizar-pin); <br>
[US15](backlog.md#us15); <br>
### Elo
**Representação**:  [ECU - Visualizar Pin](especificacoes_caso_uso.md#visualizar-pin) representa [DCU3](diagramas_caso_uso.md#dcu-3). <br>
**Agregação**: [ECU - Visualizar Pin](especificacoes_caso_uso.md#visualizar-pin) alocado em [US15](backlog.md#us15). <br>

## EF14
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[C5](cenarios.md#c5); <br>
 [L10](lexicos.md#l10); <br>
[DCU7](diagramas_caso_uso.md#dcu-7); <br> [US36](backlog.md#us36); <br>
 [IS1](iStar.md#is1-definir-interesses); <br>
### Elo
**Alocação**: [DCU7](diagramas_caso_uso.md#dcu-7) alocado em  [US36](backlog.md#us36). <br>
**Representação**: [DCU7](diagramas_caso_uso.md#dcu-7) representa  [L10](lexicos.md#l10), [DCU7](diagramas_caso_uso.md#dcu-7). <br>

## EF15
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L2](lexicos.md#l2); <br>
 [C- Salvar um Pin](cenarios.md#c14); <br>
[DCU17](diagramas_caso_uso.md#dcu-17); <br>
[US22](backlog.md#us22);<br>
### Elo
**Representação**: [L2](lexicos.md#l2), [DCU17](diagramas_caso_uso.md#dcu-17) representa [C- Salvar um Pin](cenarios.md#c14)<br>
**Alocação**: [DCU13](diagramas_caso_uso.md#dcu-13) está alocado em [US30](backlog.md#us30);  <br>

## EF16
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[ENT11](entrevista.md#requisitos-elicitados); <br> [ST2.5](storytelling.md#storytelling-2-aprendendo-receitas-no-pinterest); <br> [ENT3](entrevista.md#requisitos-elicitados);  <br>
[US29](backlog.md#us29); <br>
 [US31](backlog.md#us31); <br>
 [L3](lexicos.md#l3); <br>
 [L33](lexicos.md#l33); <br>
 [L28](lexicos.md#l28); <br>
[C4](cenarios.md#c4); <br>
[C - Organizar Pastas](cenarios.md#c10); <br>
[DCU6](diagramas_caso_uso.md#dcu-6); <br>
 [DCU13](diagramas_caso_uso.md#dcu-13);<br>
### Elo
**Representação**: [DCU6](diagramas_caso_uso.md#dcu-6) representa [C4](cenarios.md#c4).<br>
**Representação**:  [DCU13](diagramas_caso_uso.md#dcu-13) representa[C10](cenarios.md#c10).<br>
**Alocação**: [DCU6](diagramas_caso_uso.md#dcu-6) alocado em [US29](backlog.md#us29) e  [DCU13](diagramas_caso_uso.md#dcu-13) alocado em [US31](backlog.md#us31).<br>

## EF17
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[ENT10](entrevista.md#requisitos-elicitados)<br>
 [L4](lexicos.md#l4); <br>
 [L33](lexicos.md#l33); <br>
 [L28](lexicos.md#l28); <br>
 [C4](cenarios.md#c4); <br>
[C - Organizar Pastas](cenarios.md#c10); <br>  
[DCU6](diagramas_caso_uso.md#dcu-6); <br>
 [DCU13](diagramas_caso_uso.md#dcu-13); <br>
 [US31](backlog.md#us31);<br>
[US30](backlog.md#us30); <br>
### Elo
**Representação**: [ECU - Organizar Pasta](especificacoes_caso_uso.md#organizar-pasta) representa[C10](cenarios.md#c10). <br>
**Alocação**: [ECU - Organizar Pasta](especificacoes_caso_uso.md#organizar-pasta) está alocado em [US30](backlog.md#us30). <br>

## EF18
### Categoria
Desenvolvimento
### Elementos Rastreáveis
 [L31](lexicos.md#l31); <br>
 [C12](cenarios.md#c12); <br>
[DCU15](diagramas_caso_uso.md#dcu-15); <br>
[US35](backlog.md#us35); <br>
### Elo
**Representação**:  [DCU15](diagramas_caso_uso.md#dcu-15) representa  [C12](cenarios.md#c12). <br>
**Alocação**: [DCU15](diagramas_caso_uso.md#dcu-15) está alocado em [US35](backlog.md#us35). <br>
**Agregação** :   [C12](cenarios.md#c12),
[DCU15](diagramas_caso_uso.md#dcu-15) são compostos por  [L31](lexicos.md#l31). <br>

## EF19
### Categoria
Desenvolvimento
### Elementos Rastreáveis
 [L5](lexicos.md#l5); <br>
 [C9](cenarios.md#c9); <br>
[US16](backlog.md#us16); <br>
### Elo
**Representação**:  [DCU15](diagramas_caso_uso.md#dcu-15) representa  [C12](cenarios.md#c12). <br>
**Alocação**: [DCU15](diagramas_caso_uso.md#dcu-15) está alocado em [US35](backlog.md#us35). <br>

## EF20
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L12](lexicos.md#l12); <br>
 [L14](lexicos.md#l14); <br>
 [C7](cenarios.md#c7); <br>
 [IS7](iStar.md#is7-enviar-pin); <br>
 [DCU9](diagramas_caso_uso.md#dcu-9);<br>
[US17](backlog.md#us17);
### Elo
**Representação**: [DCU9](diagramas_caso_uso.md#dcu-9) representa [C7](cenarios.md#c7).<br>  
**Alocação**: [C7](cenarios.md#c7) está alocado em [US17](backlog.md#us17). <br>

## EF21
### Categoria
Desenvolvimento
### Elementos Rastreáveis
 [L12](lexicos.md#l12); <br>
  [C7](cenarios.md#c7); <br>
 [DCU9](diagramas_caso_uso.md#dcu-9); <br>
[ECU - Enviar um Pin](especificacoes_caso_uso.md#enviar-um-pin); <br>
 [US17](backlog.md#us17); <br>
 [IS9](iStar.md#is9-enviar-pin);<br>
### Elo
**Alocação**: [ECU - Enviar um Pin](especificacoes_caso_uso.md#enviar-um-pin) está alocado em [US17](backlog.md#us17).<br>
**Representa**:  [ECU - Enviar um Pin](especificacoes_caso_uso.md#enviar-um-pin), [DCU9](diagramas_caso_uso.md#dcu-9)  representa  [C7](cenarios.md#c7).<br>

## EF22
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L23](lexicos.md#l23); <br>
[C2](cenarios.md#c2); <br>
[DCU4](diagramas_caso_uso.md#dcu-4); <br>
[ECU - Comentar em um Pin](especificacoes_caso_uso.md#comentar-em-um-pin); <br>
[US15](backlog.md#us15); <br>
### Elo
**Representação**: [ECU - Comentar em um Pin](especificacoes_caso_uso.md#comentar-em-um-pin) representa [C2](cenarios.md#c2) <br>
**Alocação**: [C2](cenarios.md#c2) está alocado em [US15](backlog.md#us15). <br>

## EF23
### Categoria
Desenvolvimento
### Elementos Rastreáveis
 [L8](lexicos.md#l8); <br>
 [C13](cenarios.md#c13); <br>
 [ECU - Seguir outro usuário](especificacoes_caso_uso.md#seguir-outro-usuario); <br>
 [DCU16](diagramas_caso_uso.md#dcu-16); <br> [US23](backlog.md#us23); <br>
 [IS4](iStar.md#is4-seguir-usuario); <br>
### Elo
**Representação**:  [ECU - Seguir outro usuário](especificacoes_caso_uso.md#seguir-outro-usuario) representa [C13](cenarios.md#c13). <br>
**Alocação**: [C13](cenarios.md#c13) está alocado em [US23](backlog.md#us23). <br>

## EF24
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L34](lexicos.md#l34); <br>
[C21](cenarios.md#c21); <br>
[C20](cenarios.md#c20); <br>
 [ECU - Ocultar um Pin](especificacoes_caso_uso.md#ocultar-um-pin); <br>
 [DCU22](diagramas_caso_uso.md#dcu-22); <br>
 [ECU - Denunciar um Pin](especificacoes_caso_uso.md#denunciar-um-pin); <br>[DCU23](diagramas_caso_uso.md#dcu-23); <br> [US20](backlog.md#us20); <br>  [US21](backlog.md#us21); <br>
### Elo
**Representação**: [ECU - Denunciar um Pin](especificacoes_caso_uso.md#denunciar-um-pin) representa [C21](cenarios.md#c21). <br>
**Representação**: [ECU - Ocultar um Pin](especificacoes_caso_uso.md#ocultar-um-pin) representa [C20](cenarios.md#c20)
**Recurso**: [C21](cenarios.md#c21) depende de um recurso provido em [L1](lexicos.md#l1). <br>
**Alocação**: [C21](cenarios.md#c21) está alocado em [US21](backlog.md#us21). <br>
**Alocação**: [C20](cenarios.md#c20) está alocado em [US20](backlog.md#us20). <br>


## EF25
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[US16](backlog.md#us16);<br>
### Elo
--

## EF26
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L26](lexicos.md#l26); <br>
[C3](cenarios.md#c3); <br>
 [DCU5](diagramas_caso_uso.md#dcu-5); <br>
 [ECU - Compartilhar Pasta](especificacoes_caso_uso.md#compartilhar-pasta); <br> [US32](backlog.md#us32); <br>
 [US33](backlog.md#us33); <br>
### Elo
**Alocação**:  [ECU - Compartilhar Pasta](especificacoes_caso_uso.md#compartilhar-pasta) alocado em [US32](backlog.md#us32) e   [US33](backlog.md#us33). <br>
**Representação**: [DCU5](diagramas_caso_uso.md#dcu-5) e
 [ECU - Compartilhar Pasta](especificacoes_caso_uso.md#compartilhar-pasta) representa [C3](cenarios.md#c3). <br>

## EF27
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[US15](backlog.md#us15); <br>
### Elo
--

## EF28
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[US39](backlog.md#us39); <br>
### Elo
--

## EF29
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L18](lexicos.md#l18); <br>
 [C17](cenarios.md#enviar-mensagem-para-outro-usuario); <br> [ECU - Enviar um Pin](especificacoes_caso_uso.md#enviar-um-pin); <br>
[ECU - Enviar Mensagem para outros usuários](especificacoes_caso_uso.md#enviar-mensagem-para-outros-usuarios); <br>
 [DCU1](diagramas_caso_uso.md#dcu-1); <br>
 [IS7](iStar.md#is7-enviar-pin); <br>
 [DCU9](diagramas_caso_uso.md#dcu-9); <br>
 [US28](backlog.md#us28);<br>
### Elo
**Representação**: [ECU - Enviar Mensagem para outros usuários](especificacoes_caso_uso.md#enviar-mensagem-para-outros-usuarios) representa [L18](lexicos.md#l18),  [C17](cenarios.md#enviar-mensagem-para-outro-usuario), [DCU1](diagramas_caso_uso.md#dcu-1) e  [IS7](iStar.md#is7-enviar-pin). <br>
**Representação**: [ECU - Enviar um Pin](especificacoes_caso_uso.md#enviar-um-pin) representa  [IS7](iStar.md#is7-enviar-pin) e [DCU9](diagramas_caso_uso.md#dcu-9). <br>
**Alocação**: [ECU - Enviar Mensagem para outros usuários](especificacoes_caso_uso.md#enviar-mensagem-para-outros-usuarios) está alocado em [US28](backlog.md#us28). <br>

## EF30
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L19](lexicos.md#l19); <br>
[C18](cenarios.md#c18); <br>
[DCU20](diagramas_caso_uso.md#dcu-20); <br>
[ECU - Receber notificações](especificacoes_caso_uso.md#receber-notificacoes); <br> [US24](backlog.md#us24);<br>
### Elo
**Representação** [ECU - Receber notificações](especificacoes_caso_uso.md#receber-notificacoes) representa [L19](lexicos.md#l19), [C18](cenarios.md#c18) e [DCU20](diagramas_caso_uso.md#dcu-20)<br>
**Alocação** [ECU - Receber notificações](especificacoes_caso_uso.md#receber-notificacoes) está alcoado em [US24](backlog.md#us24) <br>

## EF31
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[C24](cenarios.md#c24); <br>
 [ECU - Editar perfil](especificacoes_caso_uso.md#editar-perfil); <br>
[DCU26](diagramas_caso_uso.md#dcu-26); <br>
[US37](backlog.md#us37); <br>
[IS5](iStar.md#is5-editar-configuracoes-de-conta); <br>
### Elo
**Representação**:  [ECU - Editar perfil](especificacoes_caso_uso.md#editar-perfil) representa [C24](cenarios.md#c24), [DCU26](diagramas_caso_uso.md#dcu-26) e [IS5](iStar.md#is5-editar-configuracoes-de-conta) <br>
**Alocação**: [ECU - Editar perfil](especificacoes_caso_uso.md#editar-perfil)  está alocado em [US37](backlog.md#us37) <br>

## EF32
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[US16](backlog.md#us16); <br>
### Elo
--

## EF33
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[NFR6](nfr.md#usuporte); <br>
[C21](cenarios.md#c21); <br>
[L34](lexicos.md#l34); <br>
[DCU23](diagramas_caso_uso.md#dcu-23); <br> [US21](backlog.md#us21); <br>
### Elo
**Representação**: [C21](cenarios.md#c21) representa [DCU23](diagramas_caso_uso.md#dcu-23), [L34](lexicos.md#l34) e [NFR6](nfr.md#usuporte) <br>

## EF34
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[C5](cenarios.md#c5); <br>
[L10](lexicos.md#l10); <br>
[DCU7](diagramas_caso_uso.md#dcu-7); <br>
(US36)[backlog.md#us36); <br>
 [IS1](iStar.md#is1-definir-interesses);
### Elo
**Representação**: [C5](cenarios.md#c5) representa [L10](lexicos.md#l10), [DCU7](diagramas_caso_uso.md#dcu-7) e  [IS1](iStar.md#is1-definir-interesses) <br>
**Alocação**: [C5](cenarios.md#c5)  está alocado em (US36)[backlog.md#us36)

## EF35
### Categoria
Desenvolvimento
### Elementos Rastreáveis
 [L33](lexicos.md#l33); <br>
 [C10](cenarios.md#c10); <br>
 [ECU - Classificação de Pastas](especificacoes_caso_uso.md#classificacao-de-pastas); <br>
 [ECU - Organizar Pasta](especificacoes_caso_uso.md#organizar-pasta); <br>
 [IS2](iStar.md#is2-classificar-pastas); <br>
 [DCU21](diagramas_caso_uso.md#dcu-21); <br> [US31](backlog.md#us31); <br>
 [US25](backlog.md#us25);
### Elo
**Representação**: [ECU - Classificação de Pastas](especificacoes_caso_uso.md#classificacao-de-pastas) representa  [DCU21](diagramas_caso_uso.md#dcu-21) e [IS2](iStar.md#is2-classificar-pastas)<br>
**Representação**: [ECU - Organizar Pasta](especificacoes_caso_uso.md#organizar-pasta) representa  [L33](lexicos.md#l33) e [C10](cenarios.md#c10) <br>
**Alocação**: [ECU - Classificação de Pastas](especificacoes_caso_uso.md#classificacao-de-pastas) está alocado em  [US25](backlog.md#us25)<br>
**Alocação**: [ECU - Organizar Pasta](especificacoes_caso_uso.md#organizar-pasta)  está alocado em [US31](backlog.md#us31)

## EF36
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L19](lexicos.md#l19); <br>
[C18](cenarios.md#c18); <br>
 [IS- Seguir Usuário](iStar.md#seguir-usuario) <br>
[US24](backlog.md#us24);
### Elo
**Representação**: [C18](cenarios.md#c18) representa [L19](lexicos.md#l19) <br>
**Alocação**:  [C18](cenarios.md#c18) está alcoado em [US24](backlog.md#us24);

## EF37
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[US37](backlog.md#us37); <br>
 [IS5](iStar.md#is5-editar-configuracoes-de-conta)
### Elo
**Alocação**:  [IS5](iStar.md#is5-editar-configuracoes-de-conta) está alocado em [US37](backlog.md#us37)

## EF38
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[IS5](iStar.md#is5-editar-configuracoes-de-conta) <br> [US39](backlog.md#us39);
### Elo
**Alocação**: [IS5](iStar.md#is5-editar-configuracoes-de-conta)  está alocado em [US39](backlog.md#us39)

## EF39
### Categoria
Desenvolvimento
### Elementos Rastreáveis
 [IS6](iStar.md#is6-cadastro-no-pinterest); <br>
 [DCU26](diagramas_caso_uso.md#dcu-26); <br>
 [ECU - Editar Perfil](especificacoes_caso_uso.md#editar-perfil); <br>
 [C24](cenarios.md#c24) <br>
[US37](backlog.md#us37); <br>
[US38](backlog.md#us38);
### Elo
**Repreentação**:  [ECU - Editar Perfil](especificacoes_caso_uso.md#editar-perfil) representa  [DCU26](diagramas_caso_uso.md#dcu-26) e  [C24](cenarios.md#c24) <br>
**Alocação**: [ECU - Editar Perfil](especificacoes_caso_uso.md#editar-perfil) está alocado em [US37](backlog.md#us37) e [US38](backlog.md#us38)

## EF40
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[IS6](iStar.md#is6-cadastro-no-pinterest); <br>
[DCU26](diagramas_caso_uso.md#dcu-26); <br>
 [US38](backlog.md#us38);
### Elo
**Alocação**:[DCU26](diagramas_caso_uso.md#dcu-26) está alocado em [US38](backlog.md#us38)

## EF41
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[C6](cenarios.md#c6); <br>
 [DCU8](diagramas_caso_uso.md#dcu-8); <br>
 [ECU - Editar um Pin](especificacoes_caso_uso.md#editar-um-pin); <br>
 [IS8](iStar.md#is8-enviar-pin); <br>
 [US18](backlog.md#us18)
### Elo
**Representação**: [ECU - Editar um Pin](especificacoes_caso_uso.md#editar-um-pin) representa [C6](cenarios.md#c6), [DCU8](diagramas_caso_uso.md#dcu-8) e  [IS8](iStar.md#is8-enviar-pin) <br>
**Alocação**: [ECU - Editar um Pin](especificacoes_caso_uso.md#editar-um-pin) está alocado em   [US18](backlog.md#us18)

## EF42
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[IS8](iStar.md#is8-enviar-pin) <br>
[US18](backlog.md#us18)
### Elo
**Alocação**: [IS8](iStar.md#is8-enviar-pin) está alocado em [US18](backlog.md#us18)

## EF43
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[C6](cenarios.md#c6); <br>
 [DCU8](diagramas_caso_uso.md#dcu-8); <br>
 [ECU - Editar um Pin](especificacoes_caso_uso.md#editar-um-pin); <br>
[IS8](iStar.md#is8-enviar-pin) <br>
 [US15](backlog.md#us15);
### Elo
**Representação**: [ECU - Editar um Pin](especificacoes_caso_uso.md#editar-um-pin) representa [C6](cenarios.md#c6), [DCU8](diagramas_caso_uso.md#dcu-8) e [IS8](iStar.md#is8-enviar-pin) <br>
**Alocação**: [ECU - Editar um Pin](especificacoes_caso_uso.md#editar-um-pin) está alocado em [US15](backlog.md#us15)

## EF44
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[NFR3](nfr.md#nfr3-usabilidade); <br>
 [US37](backlog.md#us37); <br>
 [US38](backlog.md#us38);
### Elo
**Alocação**: [NFR3](nfr.md#nfr3-usabilidade) está alocado em [US37](backlog.md#us37) e [US38](backlog.md#us38)

## EF45
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[DCU10](diagramas_caso_uso.md#dcu-10); <br>
 [ECU - Realizar primeiro login](especificacoes_caso_uso.md#realizar-primeiro-login); <br>
 [IS6](iStar.md#is6-cadastro-no-pinterest); <br>
 [US13](backlog.md#us13);
### Elo
**Representação**:  [ECU - Realizar primeiro login](especificacoes_caso_uso.md#realizar-primeiro-login)  representa [DCU10](diagramas_caso_uso.md#dcu-10)  <br>
**Alocação**:  [ECU - Realizar primeiro login](especificacoes_caso_uso.md#realizar-primeiro-login) alocado em [US13](backlog.md#us13).

## EF46
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[L15](lexicos.md#l15); <br>
 [DCU18](diagramas_caso_uso.md#dcu-18); <br>
 [C15](cenarios.md#c15); <br>
 [ECU - Visualizar Feed](especificacoes_caso_uso.md#visualizar-feed); <br> [US15](backlog.md#us15);
### Elo
**Representação**: [ECU - Visualizar Feed](especificacoes_caso_uso.md#visualizar-feed) representa [DCU18](diagramas_caso_uso.md#dcu-18),  [C15](cenarios.md#c15), [L15](lexicos.md#l15)  <br>
**Alocação**: [ECU - Visualizar Feed](especificacoes_caso_uso.md#visualizar-feed) alocado em [US15](backlog.md#us15)

## EF47
### Categoria
Desenvolvimento
### Elementos Rastreáveis
 [C5](cenarios.md#c5); <br>
 [C11](cenarios.md#c11); <br>
 [C12](cenarios.md#c12); <br>
[L11](lexicos.md#l11); <br>
 [DCU7](diagramas_caso_uso.md#dcu-7); <br>
 [DCU14](diagramas_caso_uso.md#dcu-14); <br>
 [DCU15](diagramas_caso_uso.md#dcu-15); <br>
[ECU - Pesquisar por Tema](especificacoes_caso_uso.md#pesquisar-por-tema); <br>
 [ECU - Pesquisar por Foto](especificacoes_caso_uso.md#pesquisar-por-foto); <br>
 [IS1](nfr.md#definir-interesses); <br>
 [IS3](nfr.md#pesquisar-pins);
[US24](backlog.md#us24); <br>
 [US36](backlog.md#us36);<br>
### Elo
**Representação**: [ECU - Pesquisar por Tema](especificacoes_caso_uso.md#pesquisar-por-tema) representa [C11](cenarios.md#c11),  [DCU14](diagramas_caso_uso.md#dcu-14) . <br>
**Representação**:  [C12](cenarios.md#c12),   [DCU15](diagramas_caso_uso.md#dcu-15) representa [ECU - Pesquisar por Foto](especificacoes_caso_uso.md#pesquisar-por-foto). <br>
**Alocação**:  [ECU - Pesquisar por Foto](especificacoes_caso_uso.md#pesquisar-por-foto) alocado em [US24](backlog.md#us24). <br>
**Alocação**:    [C12](cenarios.md#c12) alocado em [US24](backlog.md#us36).

## EF48
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[C11](cenarios.md#c11); <br>
 [ECU - Pesquisar por tema](especificacoes_caso_uso.md#pesquisar-por-tema); <br>
 [DCU14](diagramas_caso_uso.md#dcu-14); <br>
 [IS3](iStar.md#is3-pesquisar-pins); <br>
[C12](cenarios.md#c12); <br>
 [DCU15](diagramas_caso_uso.md#dcu-15); <br>
 [ECU - Pesquisar por Foto](especificacoes_caso_uso.md#pesquisar-por-foto) <br> [US34](backlog.md#us34); <br>
 [US35](backlog.md#us35)
### Elo
**Representação**: [ECU - Pesquisar por tema](especificacoes_caso_uso.md#pesquisar-por-tema) representa [C11](cenarios.md#c11),  [DCU14](diagramas_caso_uso.md#dcu-14) e [IS3](iStar.md#is3-pesquisar-pins)<br>
**Representação**:  [ECU - Pesquisar por Foto](especificacoes_caso_uso.md#pesquisar-por-foto)  representa [DCU15](diagramas_caso_uso.md#dcu-15), [C12](cenarios.md#c12) e  [IS3](iStar.md#is3-pesquisar-pins)<br>
**Alocação**: [ECU - Pesquisar por tema](especificacoes_caso_uso.md#pesquisar-por-tema)  está alocado em [US34](backlog.md#us34)<br>
**Alocação**: [ECU - Pesquisar por Foto](especificacoes_caso_uso.md#pesquisar-por-foto)  está alocado em [US35](backlog.md#us35)

## EF49
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[US19](backlog.md#us19);
### Elo
--

## EF50
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[DCU3](diagramas_caso_uso.md#dcu-3); <br>
[L22](lexicos.md#l22); <br>
 [US15](backlog.md#us15);
### Elo
--

## EF51
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[US15](backlog.md#us15); <br>
 [US36](backlog.md#us36); <br>
 [C5](cenarios.md#c5); <br>
 [C11](cenarios.md#c11); <br>
[C12](cenarios.md#c12); <br>
 [L11](lexicos.md#l11); <br>
 [DCU7](diagramas_caso_uso.md#dcu-7); <br>
 [DCU14](diagramas_caso_uso.md#dcu-14); <br>
 [DCU15](diagramas_caso_uso.md#dcu-15); <br>
 [ECU - Pesquisar por Tema](especificacoes_caso_uso.md#pesquisar-por-tema); <br>
 [ECU - Pesquisar por Foto](especificacoes_caso_uso.md#pesquisar-por-foto); <br>
 [IS1](nfr.md#definir-interesses); <br>
 [IS3](nfr.md#pesquisar-pins)
### Elo
**Representação**: [ECU - Pesquisar por tema](especificacoes_caso_uso.md#pesquisar-por-tema) representa [C11](cenarios.md#c11),  [DCU14](diagramas_caso_uso.md#dcu-14) e [IS3](iStar.md#is3-pesquisar-pins)<br>
**Repreentação**:  [ECU - Pesquisar por Foto](especificacoes_caso_uso.md#pesquisar-por-foto)  representa [DCU15](diagramas_caso_uso.md#dcu-15), [C12](cenarios.md#c12) e  [IS3](iStar.md#is3-pesquisar-pins)<br>
**Alocação**: [ECU - Pesquisar por tema](especificacoes_caso_uso.md#pesquisar-por-tema)  está alocado em [US34](backlog.md#us15)<br>
**Alocação**: [ECU - Pesquisar por Foto](especificacoes_caso_uso.md#pesquisar-por-foto)  está alocado em [US35](backlog.md#us36)

## EF52
### Categoria
Desenvolvimento
### Elementos Rastreáveis
[IS2](iStar.md#is2-classificar-pastas); <br>
[L30](lexicos.md#l30); <br>
[US25](backlog.md#us25);
### Elo
**Representação**: [IS2](iStar.md#is2-classificar-pastas) representa  [L30](lexicos.md#l30)<br>
**Alocação**: [IS2](iStar.md#is2-classificar-pastas)  está alocado em [US25](backlog.md#us25)


# Links

## Vincular suas redes sociais
Disponível em: <https://help.pinterest.com/pt-br/article/link-your-social-media>

## Interesses no Pinterest
Disponível em: <https://help.pinterest.com/pt-br/article/topics>

## Salvar Pins no Pinterest
Disponível em: <https://help.pinterest.com/pt-br/article/save-pins-on-pinterest>

## Produtos do Pinterest
Disponível em: <https://newsroom.pinterest.com/pt-br/products>

## Mover Pins para outra Pasta
Disponível em: <https://help.pinterest.com/pt-br/article/move-pins-to-another-board>

## Ocultar um Pin
Disponível em: <https://help.pinterest.com/pt-br/article/hide-a-pin-on-your-home-feed#search=denunciar>

## Denunciar algo no Pinterest
Disponível em: <https://help.pinterest.com/pt-br/article/report-something-on-pinterest>

## Política de Cookies
Disponível em: <https://policy.pinterest.com/pt-br/cookies>

## Organizar pastas no Pinterest
Disponível em: <https://help.pinterest.com/pt-br/article/organize-your-boards>

## Pins patrocinados
Disponível em: <https://help.pinterest.com/pt-br/article/promoted-pins>

## Pinterest Labs
Disponível em: <https://labs.pinterest.com/publications/>

## Direcionamentos à lojas de download de aplicativos
Disponível em: <https://help.pinterest.com/pt-br/article/directed-to-app-store-or-play-store>

## Enviar Pins, Pastas e Perfis
Disponível em: <https://help.pinterest.com/pt-br/article/send-pins-boards-and-profiles>

## Compartilhar Pins e Pastas em redes sociais
Disponível em: <https://help.pinterest.com/pt-br/article/share-pins-and-boards-to-social-networks>

## Comentar em um Pin
Disponível em: <https://help.pinterest.com/pt-br/article/comment-on-a-pin>

## Encontrar e Seguir amigos
Disponível em: <https://help.pinterest.com/pt-br/article/find-and-follow-friends>

## Navegador do Pinterest
Disponível em: <https://help.pinterest.com/pt-br/article/trouble-with-pinterest-browser-button>

## Convidar amigos para uma pasta
Disponível em: <https://help.pinterest.com/pt-br/article/invite-friends-to-a-group-board>

## Experimentar um Pin
Disponível em: <https://help.pinterest.com/pt-br/search#search=experimentar>

## Enviar mensagens
Disponível em: <https://help.pinterest.com/pt-br/article/send-messages>

## Perfil no Pinterest
Disponível em: <https://help.pinterest.com/pt-br/article/edit-your-profile>

## Política de Privacidade do Pinterest
Disponível em: <https://policy.pinterest.com/pt-br/privacy-policy>

## Criar um Pin a partir da galeria de fotos
Disponível em: <https://help.pinterest.com/pt-br/article/create-a-pin-from-your-photos>

## Editar ou Excluir um Pin
Disponível em: <https://help.pinterest.com/pt-br/article/edit-or-delete-a-pin>

## Diretrizes da Comunidade do Pinterest
Disponível em: <https://policy.pinterest.com/pt-br/community-guidelines>
