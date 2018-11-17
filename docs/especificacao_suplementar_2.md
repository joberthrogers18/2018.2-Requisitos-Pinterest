# Documento de Especificação Suplementar

## Histórico de Versões

|Data | Versão | Descrição | Autor |
|--|--|--|--|
|05/10/2018 | 1.0.0 | Inicialização do Documento| Guilherme Guy, Joberth Rogers e Geovana Ramos|
|06/10/2018 |1.0.1| Adição dos itens de Confiabilidade, Requisitos de sistema de ajuda, licenciamento e interfaces| Geovana Ramos|
|06/10/2018|1.0.2|Itens de desempenho, restrições de design e componentes adquiridos|Joberth Rogers|
|06/10/2018|1.0.3|Adição de requisitos de usabilidade e portabilidade|Guilherme Guy
|09/10/2018|1.0.4|Adição de Itens nos temas gerais, sumarização, modificação da formatação conforme exemplo|Alexandre Miguel e Letícia Meneses|
|10/10/2018|1.0.5| Revisão geral dos itens| Helena Goulart, Gabriela Medeiros e Daniel Maike|
|17/11/2018|2.0| Adição de referências linkadas, adição de tópicos (Conectividade, Conteúdo), dissolução de tópico(Confiabilidade: Segurança e Tratamento de Falhas), atualização de tópicos (Introdução, Funcionalidades, Suportabilidade-Portabilidade) e correção de modelo de formatação| Geovana Ramos|


## Introdução

### Finalidade
O Presente documento reúne os requisitos não identificados nos demais processos de elicitação. Permite uma visão mais ampla sobre os requisitos da aplicação que vão além de funcionalidades, que descrevem necessidades relacionadas à qualidade, estrutura e condições subjetivas.

### Escopo
O escopo se resume à uma aplicação web e mobile que oferece uma exposição  de fotos por meio de compartilhamentos em forma de rede social, dispondo de interação entre os usuários da plataforma.

### Definições, Acrônimos e Abreviações
Ver [Léxicos](https://joberthrogers18.github.io/2018.2-Requisitos/lexicos/).


### Referências
Template utilizado neste documento. Disponível em: http://www.funpar.ufpr.br:8080/rup/webtmpl/templates/req/rup_sspec.htm. Acesso em: 06 out. 2018.
Demais referências encontram-se linkadas por todo o documento.

### Visão Geral
O Documento presente apresenta uma introdução ao escopo do projeto analisado, cujos requisitos suplementares estão listados posteriormente, contendo requisitos não funcionais (obtidos pelas impressões de usuários assíduos do aplicativo), requisitos de usabilidade, desempenho, portabilidade, conectividade, conteúdo, tratamento de falhas, segurança, licenciamento e observações legais, restrições de design e interfaces.


## Funcionalidades

As funcionalidades funcionais e não funcionais já elicitadas podem ser encontradas por toda a [documentação](https://joberthrogers18.github.io/2018.2-Requisitos/) feita pelo grupo. Recomenda-se as tabelas de [backward](https://joberthrogers18.github.io/2018.2-Requisitos/backward_from/) e [foward](https://joberthrogers18.github.io/2018.2-Requisitos/forward_from/) para uma consulta mais completa e atualizada.

## Usabilidade

Este tópico descreve a qualidade da intereção do usuário com o sistema.

### Requisito de Usabilidade Um

A aplicação deve utilizar padrões visuais de informação condizentes com a plataforma em que se encontra.

### Requisito de Usabilidade Dois

A aplicação deve oferecer tutoriais para usuários de primeira viagem, no intuito de capacitá-los ao uso do aplicativo.

### Requisito de Usabilidade Três

A disposição da informação deve ser disposta de maneira coerente com a lógica de forma que o usuário possa ser treinado enquanto utiliza a aplicação.

### Requisito de Usabilidade Quatro

A aplicação deve fornecer ao usuário um fluxo intuitivo, por meio dos ícones claros, para suas diversas funcionalidades.

### Requisito de Usabilidade Cinco
O sistema deve oferecer agilidade e facilidade no momento em que o usuário executa funcionalidades básicas e principais.

### Requisito de Usabilidade Seis
O sistema deve dar feedbacks ao usuário, de forma que ele entenda o antes, durante e depois das suas ações no sistema.

## Desempenho

Este tópico descreve as restrições de comportamento geral do sistema.

### Requisito de Desempenho Um
A aplicação deve conter o balanceamento de carga ao servidor como suporte, devido ao grande número de acessos diários na aplicação, a fim de garantir o acesso de todos os usuários dentro do Pinterest.

### Requisitos de Desempenho Dois
A aplicação deve ser capaz de responder rapidamente a uma ação de cada usuário do Pinterest, de forma simultânea.   


## Portabilidade
Este tópico apresenta as restrições de plataformas do Pinterest.

### Requisito de Portabilidade Um
A aplicação deve suportar dispositivos móveis que possuam o sistema operacional Android. Limitando a versão mais recente àquela que der melhor suporte ao dispositivo ou versão do sistema operacional em execução.

### Requisito de Portabilidade Dois
A aplicação deve suportar dispositivos móveis com sistema operacional iOS 9.3 ou posterior e ser compatível com iPhone, iPad e iPod touch.

### Requisito de Portabilidade Três
A aplicação deve suportar acesso por meio de navegadores de web, com a permanência de dados e preferências de usos posteriores em diferentes plataformas mobile.

## Conectividade
Este tópico descreve a interação entre as plataformas do sistema e aplicativos de terceiros.

### Requisito de Conectividade Um
A aplicação deve possuir um design semelhante entre plataformas, para que elas possuam uma boa integração e o usuário não se sinta perdido ao trocar de dispositivo.

### Requisito de Conectividade Dois
A aplicação deve interpretar dados de buscas em sites de pesquisa para poder apresentar conteúdo mais relevante e de interesse do usuário.

### Requisito de Conectividade Três
A aplicação deve se comunicar com o usuário por meio das mais variadas plataformas de comunição, como o próprio ambiente de notificação do sistema, e por meio de e-mails cadastrados.

### Requisito de Conectividade Quatro
A aplicação deve permitir a integração com as principais redes sociais, para que o usuário encontre facilidade ao compartilhar conteúdo, achar outros usuários e também ter o cadastro facilitado.

## Conteúdo
Este tópico apresenta as restrições em relação ao conteúdo apresentado ao usuário e postado pelo mesmo.

### Requisito de Conteúdo Um
O usuário deve ter acesso a ferramentas de moderação para ter um conteúdo mais personalizado e agradável, podendo ocultar conteúdo que não lhe agrada, e denunciar conteúdo ofensivo.

### Requisito de Conteúdo Dois
A aplicação deve ter regras claras sobre o conteúdo que é permitido ser postado.

### Requisito de Conteúdo Três
A aplicação deve oferecer mais conteúdo relacionado às atividades recentes, e com base no compartamento do usuário dentro da aplicação.

### Requisito de Conteúdo Quatro
O sistema, além de oferer ferramentas de moderação para o próprio usuário, também deve combater conteúdo indesejado por meio de monitoramento automatizado.


## Tratamento de Falhas

Este tópico prevê como o sistema irá lidar com falhas, tanto na prevenção como resolução de problemas.

### Requisito de Tratamento de Falhas Um    
O Sistema deve possuir monitoramento constante, com relatórios de funcionamento, alerta de problemas e níveis de desempenho.

### Requisito de Tratamento de Falhas Dois
O sistema deve identificar os erros causadores de falhas, por meio de inspeções dinâmicas, testes de funcionamento e isolamento de processos.

### Requisito de Tratamento de Falhas Doia
O software deve procurar deixar o usuário ciente do que ocorre no sistema, assim como as falhas que possam ocorrer durante o uso. Esse feedback deve informar o motivo da falha e possíveis soluções que o próprio usuário possa executar. Caso a correção não esteja ao alcance das ações do usuário ou não possa ser informado, o suporte deve ser imediatamente informado.     

### Requisito de Tratamento de Falhas Quatro
Para evitar erros na recuperação de dados, o sistema deve implementar um banco de dados relacional.

## Segurança
Este tópico trata da proteção de dados que passam pelo sistema.

### Requisito de Segurança Um
O sistema deve promover uma autenticação segura, por meio de login por meio de *third party* e tráfego de rede  criptografado.

### Requisito de Segurança Dois
Para a autenticação por meio de login e senha, o sistema deve exigir uma senha segura ao usuário, que alterna letras maiúsculas, minúsculas, números e no mínimo 8 caracteres.

### Requisito de Segurança Três
O Sistema deve armazenar e recuperar informações com precisão, fazendo uso de criptografia de dados para impedir o vazamento de informações.

### Requisito de Segurança Quatro
No caso de uma sessão de usuário expirar, qualquer tarefa que exija futuras informações dependentes terá o acesso bloqueado, para que o os dados do usuário em sua sessão não fique exposto a um acesso de terceiros

## Restrições de Design
Esta seção reúne as decisões quanto ao design estabelecido e aplicado no Pinterest, refletindo o padrão adotado para o uso em diferentes plataformas.

### Restrição de Design Um
A aplicação  deverá ter o suporte a diversas línguas, definido através do idioma estabelecido no dispositivo do usuário.
### Restrição de Design Dois
O sistema deverá fornecer a função de scroll infinito, para dar ao usuário a impressão de uma quantidade ilimitada de conteúdo.
### Restrição de Design Três
A aplicação deverá mostrar todos os conteúdos disponibilizados na página inicial para o usuário logo ao acessar o Pinterest.
### Restrição de Design Quatro
A aplicação deverá ter a opção de denunciar, ocultar e enviar logo abaixo de cada pin, para que o usuário possa desempenhar essas ações de forma imediata e descomplicada.
### Restrição de Design Cinco
A aplicação deve fornecer páginas para que o usuário possa se cadastrar e fazer o seu login, sendo a primeira página a abrir para um usuário não cadastrado ou não logado.
### Restrição de Design Seis
A aplicação deve conter uma barra com as possíveis abas de acesso a diferentes regiões do aplicativo presente em todas as telas estáticas, permitindo um fluxo mais facilitado ao usuário.

## Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line
Esta seção reúne os requisitos que busquem tratar do suporte e dos sistemas de auxílio ao usuário para o uso correto da aplicação, como sistemas de suporte e páginas de apoio. Fonte: [Central de Ajuda do Pinterest](https://help.pinterest.com/pt-br).

### Requisito de Suporte ao Usuário Um
A  aplicação deve possuir um link de acesso a uma página da web com suporte e guia de funcionalidades da aplicação, para guiar o usuário em seu primeiro uso ou sanar dúvidas pontuais de forma direta.

### Requisito de Suporte ao Usuário Dois
A página de suporte deve conter guias de instrução para as principais funcionalidades do aplicativo, com exemplificações claras e textos diretos e informativos.

### Requisito de Suporte ao Usuário Três
A página de suporte deve possuir informações sobre o processo de alteração de dados cadastrais e proteção de dados pessoais, bem como opções de acesso à área de edição desses dados.

### Requisito de Suporte ao Usuário Quatro
A página de suporte deve possuir opções de contato com funcionários do Pinterest para o detalhamento de problemas incomuns e que fujam das especificações gerais enfrentadas pelo usuário.

### Requisito de Suporte ao Usuário Cinco
A página de suporte deverá abranger informações que auxiliem empresas e sites que utilizam o aplicativo como ferramenta de propaganda e auxílio trabalho.

### Requisito de Suporte ao Usuário Seis
A página de suporte deverá proporcionar a resposta a perguntas frequentes, com páginas de resolução de dúvidas contendo links e índices de satisfação do usuário.


## Interfaces
A Presente seção busca definir e categorizar os tipos de interface presentes na aplicação.

### Interfaces do Usuário
A plataforma deverá disponibilizar uma interface de suporte gráfico com os componentes da aplicação, de modo que o usuário possa interagir com as funcionalidades da melhor forma possível.

### Interfaces de Hardware
A plataforma deve ter suporte para dispositivos como: Smartphones, Computadores Desktops, Notebooks e Tablets.

### Interfaces de Software
A plataforma deve usufruir de linguagens e frameworks que ajude na manutenção e viabilize a eficiência no desenvolvimento, através de algum paradigma definido.

### Interfaces de Comunicação
A plataforma deve possuir uma interface de comunicação afim a suportar as diversas requisições de dados do sistema de forma a manter a integridade de todos os dados. Além de comunicação por meio de micro serviço que possibilitará o registro de contas e compartilhamento dos dados através de rede sociais.

## Requisitos de Licenciamento
Esta seção busca abranger os aspectos referentes às permissões e restrições do usuário, definidas nos documentos de licenciamento. Fonte: [Termos de Serviço](https://policy.pinterest.com/pt-br/terms-of-service) e [Diretrizes da Comunidade](https://policy.pinterest.com/pt-br/community-guidelines).

### Requisito de Licenciamento Um
Aos usuários que seguirem todas os Termos e Diretrizes da Comunidade, será oferecida uma licença limitada, não exclusiva, intransferível e revogável para usar a aplicação de forma gratuita.

### Requisito de Licenciamento Dois
Os usuários que postarem conteúdo concedem à aplicação e aos outros usuários uma licença mundial não exclusiva, livre de royalties, transferível, sublicenciável, para usar, armazenar, exibir, reproduzir, salvar, modificar, criar trabalhos derivados, executar e distribuir seu conteúdo unicamente para  fins de operação, desenvolvimento, fornecimento e uso da plataforma.

## Observações Legais, de Copyright e Outras
A plataforma irá adotar e implementar uma Política de Direitos Autorais de acordo com o Digital Millennium Copyright Act e outras leis de direitos autorais aplicáveis. Fonte: [Copyright do Pinterest](https://policy.pinterest.com/pt-br/copyright)
