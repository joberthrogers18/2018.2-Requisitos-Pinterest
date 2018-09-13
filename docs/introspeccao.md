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

| Código | Descrição |
|--|--|
|INT1.1 | O app deve oferecer a opção de selecionar a qualidade das imagens|
| INT1.2 | O app deve oferecer a opção do usuário inserir se deseja ou não o carregamento automático dos vídeos|
| INT1.3 | O app deve oferecer a opção do usuário salvar seus pins de maneira a vê-los mesmo sem o consumo de internet|
| INT1.4 | O app deve oferecer pins de receitas diversas até que o usuário tenha interesses definidos. |
| INT1.5 | O app deve absorver a informação das categorias dos pins mais visualizados para usar nas próximas recomendações  |
| INT1.6 | O app deve separar os pins por categorias |
| INT1.7 | O usuário deve conseguir compartilhar seu gosto e suas preferências entre amigos usuários|
| INT1.8 | O usuário deve ter a opção de avaliar uma receita e essa avaliação deve ser aberta a outros usuários |
| INT1.9 | O usuário deve ter a opção de acompanhar outro usuário que tenha gostos semelhantes aos dele |
| INT1.10 | O usuário deve ter a opção de salvar pins |


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

| Código | Descrição | Prioridade
|--|--|
|INT2.1 | A aplicação deve direcionar o usuário à outra aba quando clicado no link do pin| Could
| INT2.2 |O pin deve ter a opção de compartilhamento entre redes sociais ou pessoas seguidas| Should
| INT3.3 | A aplicação deve colocar nos pins a opção de "comentários"| Should
| INT4.4 | Ao clicar no pin o usuário deve conseguir ver mais informações sobre ele, como uma pequena ou grande descrição | Must
| INT5.5 | Ao pesquisar sobre algo, o Pinterest deve mostrar opções de filto sobre o assunto, para que o usuário apenas clique em um e receba um resultado mais selecionado | Should
| INT6.6 | O Pinterest deve mostrar diversos pins relacionados ao pin clicado | Must
| INT7.7 | O Pinterest deve oferecer a opção de seguir o usuário que postou o pin selecionado| Should
| INT8.8 | O Pinterest deve oferecer uma grande quantidade de pins fazendo com que o usuário tenha uma enorme quantidade de resultados | Must
