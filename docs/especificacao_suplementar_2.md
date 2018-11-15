# Documento de Especificação Suplementar

## Histórico de Versões

|Data | Versão | Descrição | Autor |
|--|--|--|--|
|05/10/2018 | 1.0.0 | Inicialização do Documento| Guilherme Guy, Joberth Rogers e Geovana Ramos|
|06/10/2018 |1.0.1| Adição dos itens de Confiabilidade, Requisitos de sistema de ajuda, licenciamento e interfaces| Geovana Ramos|
|06/10/2018|1.0.2|Itens de desempenho, restrições de design e componentes adquiridos|Joberth Rogers|
|06/10/2018|1.0.3|Adição de requisitos de usabilidade e suportabilidade|Guilherme Guy
|09/10/2018|1.0.4|Adição de Itens nos temas gerais, sumarização, modificação da formatação conforme exemplo|Alexandre Miguel e Letícia Meneses|
|10/10/2018|1.0.5| Revisão geral dos itens| Helena Goulart, Gabriela Medeiros e Daniel Maike|



## Introdução
O Presente documento reúne os requisitos não identificados nos demais processos de elicitação, e que não foram atendidos pelo contato direto com o aplicativo, mas com a percepção de usuários, membros da equipe e ainda análise de documentação exposta no site do pinterest.

### Finalidade
Esse documento visa  descrever requisitos não funcionais do Pinterest, ou seja, restrições qualitativas que impactam na usabilidade, no visual, no desempenho, na segurança, dentre outros aspectos. Permite uma visão mais ampla sobre os requisitos da aplicação que vão além de funcionalidades, que descrevem necessidades relacionadas à qualidade, estrutura e condições subjetivas.

### Escopo
O escopo se resume à uma aplicação web e mobile que oferece uma exposição  de fotos por meio de compartilhamentos em forma de rede social, dispondo de interação entre os usuários da plataforma.

### Definições, Acrônimos e Abreviações
Pinterest - Aplicativo analisado pela equipe, cujo foco é a descoberta e compartilhamento de imagens de diferentes temas;
Elicitação - Processo de obtenção de requisitos através das técnicas de entrevistas, brainstorming, introspecções, dentre outras;
Pin - Imagens expostas no Pinterest;

Ver também Léxicos do projeto.


### Referências
Pinterest terms of service. Disponível em: https://policy.pinterest.com/en/terms-of-service. Acesso em: 06 out. 2018.
Template Especificação Suplementar. Disponível em: http://www.funpar.ufpr.br:8080/rup/webtmpl/templates/req/rup_sspec.htm. Acesso em: 06 out. 2018.

### Visão Geral
O Documento presente apresenta uma introdução ao escopo do projeto analisado, cujos requisitos suplementares estão listados posteriormente, contendo requisitos não funcionais (obtidos pelas impressões de usuários assíduos do aplicativo), requisitos de usabilidade, confiabilidade, desempenho, suportabilidade, sistema, licenciamento, restrições de design e interfaces.


## Funcionalidade
Esse tópico reúne os requisitos não funcionais, dado que os requisitos funcionais estão dispostos e definidos na documentação de elicitação, sendo representados pelos casos de uso.


### Requisitos não Funcionais

| Identificador |Origem|Funcionalidade|
|--|--|--|
|RNF-01|ENT-05|O app deve possuir um design de interface semelhante entre o aplicativo mobile e o aplicativo web.|
|RNF-02|ENT-01|A rede social deve abranger conteúdos que mantenham ativos os usuários que compõe o principal público, jovens de faixa etária entre 16 e 25 anos.|
|RNF-03|ENT-02|A rede social deve conter uma melhor experiência de usuário para que o usuário possa acessá-la tanto pela web quanto pelo aplicativo.|
|RNF-04|ENT-03|A interface do usuário deve ser agradável para melhorar as experiências e torná-las excelentes.|
|RNF-05|ENT-04|A rede social deve procurar diferenciais perante seus maiores concorrentes, weheartit.com e tumblr.com|
|RNF-06|ES|A linguagem da aplicação deve focar no seu público alvo para facilitar a comunicação entre eles.|


## Usabilidade
Os usuários devem poder aprender a mexer no sistema de forma intuitiva através do uso. Dessa forma o treinamento necessário para fazer uma utilização correta do sistema deverá ser rápido, considerando que um usuário não gasta muito tempo de uma vez só no sistema, o período de aprendizado mínimo para poder utilizar o básico do sistema deverá ser menor que uma hora. Já para um usuário que deseja ter conhecimento profundo do sistema (usuário avançado) pode levar um período de tempo maior, indo de algumas horas até vários dias, de acordo com sua habilidade de aprendizagem e através de aprendizagem orgânica, utilizando a aplicação.
    Uma observação pertinente é que para fazer bom uso do sistema o usuário deve ser capaz de utilizar seu dispositivo físico de acesso (celular smartphone) e também o sistema operacional instalado no dispositivo (Android ou iOS) pois vários dos conhecimentos dos padrões do sistema operacional do dispositivo serão necessários para a utilização da aplicação.
### Requisito de Usabilidade Um

A aplicação deve utilizar padrões visuais de informação condizentes com a plataforma em que se encontra.

### Requisito de Usabilidade Dois

A aplicação deve oferecer tutoriais para usuários de primeira viagem, no intuito de capacitá-los ao uso do aplicativo.

### Requisito de Usabilidade Três

A disposição da informação deve ser disposta de maneira coerente com a lógica de forma que o usuário possa ser treinado enquanto utiliza a aplicação.

### Requisito de Usabilidade Quatro

A aplicação deve fornecer ao usuário um fluxo intuitivo, por meio dos ícones, para suas diversas funcionalidades.

### Requisito de Usabilidade Cinco

O sistema deve oferecer agilidade e facilidade no momento em que o usuário executa funcionalidades básicas e principais.

## Confiabilidade
O Sistema possui servidores estáveis, com uma baixa taxa de reclamação dos usuários quanto a falhas de funcionamento. Os dados de usuário, como Pins salvos, informações pessoais, preferências e bloqueios devem estar sincronizados com o banco de dados que gerencia o fluxo de informações, propiciando um funcionamento ininterrupto e com fluxo constante de informações.

### Requisito de Confiabilidade Um    
O Sistema deve possuir monitoramento constante, com relatórios de funcionamento, alerta de problemas e níveis de desempenho.

### Requisito de Confiabilidade Dois

O Sistema deve armazenar e recuperar informações com precisão, fazendo uso de criptografia de dados para impedir o vazamento de informações.

### Requisito de Confiabilidade Três
No caso de uma sessão de usuário expirar, qualquer tarefa que exija futuras informações dependentes terá o acesso bloqueado, para que o os dados do usuário em sua sessão não fique exposto a um acesso de terceiros

### Requisito de Confiabilidade Quatro
O software deve procurar deixar o usuário ciente do que ocorre no sistema, assim como as falhas que possam ocorrer durante o uso. Esse feedback deve informar o motivo da falha e possíveis soluções que o próprio usuário possa executar. Caso a correção não esteja ao alcance das ações do usuário ou não possa ser informado, o suporte deve ser imediatamente informado.     

## Desempenho

Como requisito de desempenho, Além disso o tempo de resposta das requisições feitas pelo usuário deve ser o menor possível, não podendo passar de 2 segundos para uma melhor experiência do usuário dentro da aplicação.

### Requisito de Desempenho Um
A aplicação deve conter o balanceamento de carga ao servidor como suporte, devido ao grande número de acessos diários na aplicação, a fim de garantir o acesso de todos os usuários dentro do Pinterest.

### Requisitos de Desempenho Dois
A aplicação deve ser capaz de responder rapidamente a uma ação de cada usuário do Pinterest, de forma simultânea.


## Suportabilidade
O Sistema do Pinterest possibilitará o uso em dispositivos mobiles - tanto os que utilizam o sistema Android quanto os que utilizam o sistema iOS - através de aplicativos instalados. O Uso também poderá ocorrer pelo site, sendo acessado de qualquer browser para a web. Essas formas de utilização não são dependentes, atuando mais como complementares uma à outra.

### Requisito de Suportabilidade Um
A aplicação deve suportar dispositivos móveis que possuam o sistema operacional Android. Limitando a versão mais recente àquela que der melhor suporte ao dispositivo ou versão do sistema operacional em execução.

### Requisito de Suportabilidade Dois
A aplicação deve suportar dispositivos móveis com sistema operacional iOS 9.3 ou posterior e ser compatível com iPhone, iPad e iPod touch.
Requisito de Suportabilidade Três
A aplicação deve suportar acesso por meio de navegadores de web, com a permanência de dados e preferências de usos posteriores em diferentes plataformas mobile.

## Restrições de Design
Esta seção reúne as decisões quanto ao design estabelecido e aplicado no Pinterest, refletindo o padrão adotado para o uso em diferentes plataformas e a adaptação às alterações conforme o formato de exibição de informações, caracterizando a forma de utilização e o grau de contato entre o usuário e o aplicativo.
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
Esta seção reúne os requisitos que busquem tratar do suporte e dos sistemas de auxílio ao usuário para o uso correto da aplicação, como sistemas de suporte e páginas de apoio

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


## Componentes Adquiridos
O sistema deve levar em consideração as licenças do software e reservas legais ao ser desenvolvido.

## Interfaces
A Presente seção busca definir e categorizar os tipos de interface presentes na aplicação, contando com a necessidade do software conter um desenvolvimento correto e a presença de endereços, lógicas, protocolos e planejamento de execução bem integrados para um funcionamento correto.

### Interfaces do Usuário
A plataforma deverá disponibilizar uma interface de suporte gráfico com os componentes da aplicação, de modo que o usuário possa interagir com as funcionalidades da melhor forma possível.

### Interfaces de Hardware
A plataforma deve ter suporte para dispositivos como: Smartphones, Computadores Desktops, Notebooks e Tablets.

### Interfaces de Software
A plataforma deve usufruir de linguagens e frameworks que ajude na manutenção e viabilize a eficiência no desenvolvimento, através de algum paradigma definido.

### Interfaces de Comunicação
A plataforma deve possuir uma interface de comunicação afim a suportar as diversas requisições de dados do sistema de forma a manter a integridade de todos os dados. Além de comunicação por meio de micro serviço que possibilitará o registro de contas e compartilhamento dos dados através de rede sociais.

## Requisitos de Licenciamento
Esta seção reúne os requisitos que definem as especificações do licenciamento da aplicação, buscando abranger os aspectos referentes às permissões e restrições do usuário, definidas nos documentos de licenciamento.

### Requisito de Licenciamento Um
Aos usuários que seguirem todas os Termos e Diretrizes da Comunidade, será oferecida uma licença limitada, não exclusiva, intransferível e revogável para usar a aplicação de forma gratuita.

### Requisito de Licenciamento Dois
Os usuários que postarem conteúdo concedem à aplicação e aos outros usuários uma licença mundial não exclusiva, livre de royalties, transferível, sublicenciável, para usar, armazenar, exibir, reproduzir, salvar, modificar, criar trabalhos derivados, executar e distribuir seu conteúdo unicamente para  fins de operação, desenvolvimento, fornecimento e uso da plataforma.

## Observações Legais, de Copyright e Outras

A plataforma irá adotar e implementar uma Política de Direitos Autorais de acordo com o Digital Millennium Copyright Act e outras leis de direitos autorais aplicáveis.
