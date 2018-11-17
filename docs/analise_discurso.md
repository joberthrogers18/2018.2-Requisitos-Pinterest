# Análise de Discurso

Essa técnica consiste na conversa, dentro de um grupo, de forma organizada e hierárquica, permitindo que cada membro possa exprimir uma ideia ou argumento de forma direta e sem interrupções, possibilitando uma análise mais aprofundada dos possíveis requisitos citados sob o ponto de vista bem definido de um membro da discussão. Pode ser feita de 3 formas:

* A Forma **Análise de Conversação** é menos estruturado, permitindo um contato mais informal do grupo e propiciando uma socialização, sem turnos definidos a priori;

* A Forma **Turntaking** consiste na definição de turnos de oradores em uma ordem específica, para que cada membro possa ter seu momento de fala completo, até algum fator definido pelo grupo, como tempo, pausa vocal longa e etc. demarque a mudança de turno;

* A Forma **Pares Adjacentes** consiste em uma conversa entre duas pessoas de forma ordenada e binária, permitindo que a função de orador seja transferida de forma alternada entre os membros, semelhante a um modelo de _Pergunta e Resposta_.


## Grupo de Discussão

| Nome | Papel | Observação |
|--|--|--|
| Guilherme Guy | Moderador / Sintetizador| Membro da equipe |
| Alexandre Miguel | Orador| Membro da equipe |
| Daniel Maike | Orador | Membro da equipe |
| Gabriela Medeiros | Oradora| Membro da equipe |
| Geovana Ramos | Oradora | Membro da equipe |
| Helena Goulart| Oradora| Membro da equipe |
| Joberth Rogers | Orador| Membro da equipe |
| Letícia Meneses| Oradora| Membro da equipe |

### Metodologia

Para essa técnica, o grupo se reuniu no intuito de realizar, a priori, um _Brainstorming_. Entretanto, a forma mais direta do discurso e do sistema de oradores contando ainda com um moderador (Guilherme Guy) responsável por resumir a ideia proposta no discurso de um membro e agir na elicitação foi essencial para a obtenção dos requisitos elicitados. Assim, fez-se uso de uma **análise de conversação** como forma principal da técnica de elicitação utilizada.

### Resumo da Discussão

_Os resumos aqui apresentados buscam resumir os pontos abordados pelos oradores em seus turnos na discussão, bem como a análise realizada pelo moderador e pelos demais membros que atuaram na elicitação dos requisitos. O Áudio contendo a discussão completa está disponível nesse [link](https://drive.google.com/open?id=1VcwwykePY8xA2j7U9DbHl8KZQ-SyajmN)._

**Guilherme Guy (Moderação):** Ao exemplificar para a Gabriela como a discussão poderia ocorrer, como os tópicos abordados, citou o desejo do usuário de não ver conteúdo repetido e ver coisas novas ao acessar o aplicativo, permitindo atualizar o conteúdo e possibilitando elicitar o Requisito _AD1_.

**Letícia Meneses :** Comentou que, ao salvar um Pin, aparece uma grande quantidade de Pins relacionados e que, caso o usuário possua uma pasta com conteúdo em comum, esse é notificado de Pins relacionados à pasta. Adicionou que o usuário recebe notificação quando um amigo adiciona um novo Pin, mas que o conteúdo do Pin adicionado nem sempre é relevante ao usuário notificado, e que é possível desativar essas notifcações.
_Requisitos : AD2, AD3_

**Alexandre Miguel :** Citou uma ocasião recente em que, deixando o perfil logado na aplicação web do Pinterest ainda que sem a página do app aberta, o orador pesquisou em imagens do google as obras de um artista e, ao acessar a aplicação web do Pinterest posteriormente, recebeu sugestões de Pins com as obras do artista, ainda que o login no Pinterest tenha sido feito pelo Facebook. Sugeriu que o Pinterest utiliza dados de pesquisa do google.
_Requisitos : AD4_

**Helena Goulart :** Citou que, na aba _explorar_ do aplicativo, existem sugestões de temas para usuários já classificados. Helena comentou que encontrou essas sugestões somente no site. Guilherme complementou dizendo que acredita ter encontrado na versão mobile e Letícia afirmou verificar essa funcionalidade na versão para Tablet.
_Requisitos : AD5_

**Joberth Rogers :** Citou que alguns avisos e notificações aparecem com uma construção verbal não usual, com expressões e preposições que não fazem sentido na gramática convencional ou coloquial. Guilherme e Daniel complementaram sugerindo que havia uma relação que o aplicativo queria explicitar, mas que algum algorítmo de tradução fez com que a mensagem perdesse o sentido.
 _Requisitos : AD6_

 **Gabriela Medeiros :** Citou que, de acordo com que os interesses do usuário vão se modificando, as sugestões de busca do Pinterest mudam, se adequando aos novos gostos do usuário e deixando de explicitar conteúdos de antiga preferência do usuário.
  _Requisitos : AD7_

 **Daniel, Alexandre, Letícia e Geovana :** Os usuários comentaram e complementaram argumentos acerca da grande frequência de emails que o aplicativo envia para o usuário conforme algum evento ocorre, como notificação de mensagens, sugestões de temas e etc. Letícia comentou que é possível cancelar a lista de emails.
  _Requisitos : AD8, AD9_


### Requisitos Elicitados

| Código | Descrição | Prioridade |
|--|--|--|
| AD1 | O App precisa possuir sempre conteúdos novos no feed do usuário. | Should |
| AD2 | O Usuário deve poder bloquear Pins que não são de seu interesse.| Must |
| AD3 | O Aplicativo deve ser capaz de reconhecer relações de conteúdo entre Pins.| Should|
| AD4 | O Aplicativo deve ser capaz de extrapolar dados de pesquisa de outras fontes para trazer itens mais relevantes para o usuário.| Should |
| AD5 | O Aplicativo deve sugerir temas de Pins conforme os interesses estabelecidos pelos usuário. | Must |
| AD6 | O Aplicativo deve possuir algorítmos para adaptação de mensagens para a linguagem de sistema do usuário. | Should |
| AD7 | O Aplicativo deve identificar a perda de interesse do usuário por um tema pela frequência de pesquisas.| Could|
| AD8 | O Aplicativo deve notificar o usuário por email acerca de novidades de temas ou comunicações. | Could |
| AD9 | O Usuário deve poder escolher parar de receber emails do aplicativo. | Must |
| AD10 | O Aplicativo deve conter uma aba de mensagens que possibilite a comnunicação entre os usuários ativos. | Could |
| AD11 | O Aplcativo deve tornar visível e atrativo o acesso às mensagens. | Could |
| AD12 | O Aplicativo deve possbilitar que os usuários compartilhem pastas, subpastas e pins através de mensagens. | Could |
| AD13 | O Aplicativo deve conter as pesquisas através de imagem tirada instantaneamente pela câmera do celular, que aproximem o usuário dos resultados desejados. | Should |
| AD14 | O Aplicativo deve tornar intuitiva a funcão do ícone de pesquisa através da câmera. | Should |
