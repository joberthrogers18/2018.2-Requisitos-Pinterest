# Introdução

A técnica de
introspecção consiste em imaginar que tipo de sistema seria desejável por uma pessoa
que estivesse executando uma tarefa específica, utilizando um equipamento específico, em um lugar específico, dentre outros. Se dá ao imaginar que características um sistema deveria ter para obter
a satisfação do usuário definido.

## Introspecção 1

#### Rastreabilidade

| Nome | Papel | Observação |
|--|--|--|
| Gabriela Medeiros | Autora | Membro da equipe/Usuário |

#### Contexto

O contexto dessa introspecção se dá com um usuário homem do aplicativo que deseja começar a praticar atividades de gastronomia e busca suas ideias/receitas enquanto está no ônibus em seu aparelho celular.

### Necessidades do Contexto

Este tópico indicará as necessidades absorvidas da introspecção citada no contexto indicado no tópico anterior.

##### Necessidades técnicas
* Navegação com limite de dados móveis (personalizável)
* Que o app tenha um cronômetro próprio para que não seja necessário sair da página da receita para usá-lo
##### Necessidades sociais
* Compartilhamento de receitas com amigos
* Que as receitas tenham avaliações de outros usuários, para que haja confiança em fazê-las
* Que tenha a  opção de acompanhar as receitas de um “cozinheiro” específico
##### Necessidades individuais
* A opção de salvar receitas para fazê-las quando desejado
* A recomendação de receitas, caso se perceba uma preferência em cozinhar um tipo de comida específico (doces, massas, salgados, etc)
* A possibilidade de avaliar as receitas
* A busca de receitas por tipos de comida

#### Requisitos Elicitados

| Código | Descrição | Prioridade|
|--|--|--|
|INT1.1 | O app deve oferecer a opção de selecionar a qualidade das imagens| Could |
| INT1.2 | O app deve oferecer a opção do usuário inserir se deseja ou não o carregamento automático dos vídeos| Could |
| INT1.3 | O app deve oferecer a opção do usuário salvar seus pins de maneira a vê-los mesmo sem o consumo de internet| Could |
| INT1.4 | O app deve oferecer pins de receitas diversas até que o usuário tenha interesses definidos. | Must |
| INT1.5 | O app deve absorver a informação das categorias dos pins mais visualizados para usar nas próximas recomendações  | Must |
| INT1.6 | O app deve separar os pins por categorias | Must |
| INT1.7 | O usuário deve conseguir compartilhar seu gosto e suas preferências entre amigos usuários| Should |
| INT1.8 | O usuário deve ter a opção de avaliar uma receita e essa avaliação deve ser aberta a outros usuários | Must |
| INT1.9 | O usuário deve ter a opção de salvar pins | Must |
| INT1.10 | O usuário deve ter o ferramental necessário para realizar as etapas de uma receita sem precisar sair do app | Would |


## Introspecção 2

#### Rastreabilidade

| Nome | Papel | Observação |
|--|--|--|
| Letícia Meneses | Usuário do Pinterest | Membro da equipe |

#### Contexto

A introspecção conta a história de uma usuária que pesquisa no Pinterest pelo seu notebook, por penteados para o casamento de sua prima.

### Necessidades do Contexto

Este tópico aborda as necessidades obtidas nessa introspecção.

##### Necessidades técnicas
* O link clicado de um pin direcione a página em outra aba.
##### Necessidades sociais
* Compartilhar imagens com outras pessoas
* Poder ver os comentários da foto
* A opção de seguir o usuário do pin selecionado
##### Necessidades individuais
* A opção de clicar no pin e ter mais informações sobre eles
* Conter uma diversidades de pins para ver
* Ao fazer uma pesquisa geral como "penteados", conter opções de filtros (cabelo solto, cabelo preso, tranças, etc.)
* Poder ver outras ideias parecidas com uma foto clicada

#### Requisitos Elicitados

| Código | Descrição | Prioridade|
|--|--|--|
| INT2.1 | A aplicação deve direcionar o usuário à outra aba quando clicado no link do pin| Could |
| INT2.2 |O pin deve ter a opção de compartilhamento entre redes sociais ou pessoas seguidas| Should |
| INT2.3 | A aplicação deve colocar nos pins a opção de "comentários"| Should |
| INT2.4 | Ao clicar no pin o usuário deve conseguir ver mais informações sobre ele, como uma pequena ou grande descrição | Must |
| INT2.5 | Ao pesquisar sobre algo, o Pinterest deve mostrar opções de filto sobre o assunto, para que o usuário apenas clique em um e receba um resultado mais selecionado | Should |
| INT2.6 | O Pinterest deve mostrar diversos pins relacionados ao pin clicado | Must |
| INT2.7 | O Pinterest deve oferecer a opção de seguir o usuário que postou o pin selecionado| Should |
| INT2.8 | O Pinterest deve oferecer uma grande quantidade de pins fazendo com que o usuário tenha uma enorme quantidade de resultados | Must |

# Introspecção 3

#### Rastreabilidade

| Nome | Papel | Observação |
|--|--|--|
| Daniel Maike | Autor | Membro da equipe e Usuário do Pinterest |

#### Contexto

Esta Instrospecção consiste em uma pessoa que está iniciando na musculação e que procura por dicas e inspirações para atingir seu objetivo, que possa guardá-los em sua conta para que possa acessar também posteriormente e compartilhar com seus amigos da musculação. Desejável também pelo usuário que seja um app mobile para que seja possível acessar de forma eficiente em qualquer lugar utilizando apenas o acesso a internet em seu dispositivo smartphone, pois o usuário não tem acesso a um computador.

### Necessidades do Contexto

Este tópico aborda as necessidades oriundas do contexto específico da pessoa citada no contexto da Instrospecção.

##### Necessidades Técnicas
* Haver versão mobile do sistema
* Não ser um app que ocupe muito espaço para que seja acessível de celular com menos memória
* App possuir design intuitivo para usuários leigos conseguirem utilizar sem muita dificuldade

##### Necessidades Sociais
* Haver forma de enviar as dicas e inspirações para outras pessoas pelo app
* Haver forma de compartilhamento para pessoas que não tenham o app
* Conecte com outras redes sociais para que ache mais amigos que utilizem o app

##### Necessidades Individuais
* O feed do app possuir muito conteúdo do interesse do usuário
* Salvar dicas e inspirações em sua conta
* Haver uma forma de organizar suas dicas e inspirações salvas para que não fique tudo junto, para uma forma mais eficiente de achá-las depois
* Haver uma forma de escolha de interesses para mostrar apenas coisas que o usuário desejar

#### Requisitos Elicitados

| Código | Descrição | Prioridade | Classificação |
|--|--|--|--|
| INT3.1 | A aplicação deve disponibilizar versão mobile multiplataforma para iOS, Windows Phone e Android | Must | Não Funcional |
| INT3.2 | O aplicativo não deve ocupar muita memória do celular | Should | Não Funcional |
| INT3.3 | O aplicativo deve possuir um design intuitivo para usuários leigos conseguirem utilizá-lo | Should | Não Funcional |
| INT3.4 | O aplicativo deve possuir um chat para que possa haver interação com outros usuários, por meio de envio texto ou envio de fotos | Must | Funcional |
| INT3.5 | A aplicação deve possuir a função de compartilhar fotos para outras redes sociais como Facebook e WhatsApp | Should | Funcional |
| INT3.6 | O aplicativo deve oferecer um feed com scroll infinito para visualizar muitas fotos dos interesses do usuário | Should | Funcional |
| INT3.7 | A aplicação deve oferecer a funcionalidade de escolha de interesses pré-determinados para que o usuário tenha no seu feed apenas o que deseja | Must | Funcional |
| INT3.8 | A aplicação deve oferecer a função de salvamento de fotos em sua conta | Must | Funcional |
| INT3.9 | O app deve oferecer criação de pastas para salvamento de fotos, com o objetivo de organizar melhor as fotos salvas | Should | Funcional |
| INT3.10 | A aplicação possuir meio de login por micro serviço como Facebook e Google | Must | Funcional |
