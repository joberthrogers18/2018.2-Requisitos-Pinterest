# Introdução

O presente documento visa apresentar a inspeção dos casos de uso, trabalho desenvolvido no módulo de Modelagem de Requisitos.

# Objetivo

A inspeção dos casos de uso permite conhecer vários aspectos sobre as informações, a abrangência, a completude, a qualidade do objeto analisado. Um dos focos principais desta inspeção é realizar a verificação da consistência técnica dos casos de uso levantados e também validar os casos de uso através de métricas. Esse conjunto de dados permite descobrir as fraquezas existentes no trabalho e facilita a melhoria da qualidade dos casos de uso nas métricas levantadas como passíveis de melhorias.

# Metodologia

Para a inspeção dos casos de uso será utilizada uma metodologia de avaliação padronizada, em que cada caso de uso, será julgado de acordo com sua não-conformidade com a métrica em análise, ou seja, se a opção “não” for marcada, quer dizer que a descrição de caso de uso não está em conformidade com a métrica. Cada métrica está disposta em uma escala de impacto, sendo este alto, médio ou baixo. Além disso, também há espaço para a adição de observações pelo avaliador, quando necessário. A inspeção será montada em forma de tabela, sendo cada tabela uma tabela de inspeção baseada no checklist geral criado para este documento, em que contém as métricas necessárias para avaliação de um caso de uso.

Após a aplicação da checklist na descrição de uma inspeção de um caso de uso selecionado será compilada a tabela de medição de inspeção. Em que é compilado um valor que representa de forma quantitativa a qualidade da descrição de caso de uso. A tabela de medição necessita de pesos para os impactos e neste trabalho será usado como convenção o peso 3 para métricas com alto impacto, 2 para impacto médio e 1 para impacto baixo. Nesta tabela é calculado a proporção de não conformidades encontradas, tendo como parâmetro de aceitação uma taxa máxima de 35% das questões aplicadas. Sendo que o resultado classificatório final é “Aprovado” quando a taxa de não conformidade é menor que a taxa máxima e “Reprovado” caso contrário.

As métricas utilizadas e a metodologia são elaboradas a partir do estudo “Uma proposta de inspeção em modelos de caso de uso” de Rosângela Gregolin [[1]](#referencias). Neste estudo a autora levanta critérios, regras e modelos para a melhor inspeção de casos de uso, tanto em formato de diagrama, quanto sua descrição.

A metodologia possui certas adaptações para melhor adequá-la ao contexto da disciplina, pois não é feito desenvolvimento de protótipos e documentos específicos requisitados pelo modelo.
Para uma melhor avaliação e observações das métricas foram utilizadas referenciais teóricos da IBM que auxiliam na produção de um bom caso de uso e com isso consegue-se visualizar melhor os erros cometidos no caso de uso desenvolvidos no projeto da matéria e elaborar melhores observações a respeito da métrica analisada.

A seguir pode-se conferir os modelos utilizados para a realização da inspeção:

### Checklist

![](img/inspecao_caso_de_uso/checklist_inspecao_caso_de_uso.png)

### Registro de Inspeção

![](img/inspecao_caso_de_uso/modelo_inspecao_caso_de_uso.png)

### Tabela de medição

![](img/inspecao_caso_de_uso/modelo_resultado_caso_de_uso.png)


## Inspeções

### Relação de inspeções

![](img/inspecao_caso_de_uso/resumo_inspecao_caso_de_uso.png)

### IDUC-1 Receber Notificações

Rastreabilidade: [UC - Receber Notificações](especificacoes_caso_uso.md#receber-notificacoes)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc1.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc1.png)

### IDUC-2 Editar um Pin

Rastreabilidade: [UC - Editar um Pin](especificacoes_caso_uso.md#editar-um-pin)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc2.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc2.png)

### IDUC-3 Realizar primeiro login

Rastreabilidade: [UC - Realizar primeiro login](especificacoes_caso_uso.md#realizar-primeiro-login)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc3.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc3.png)

### IDUC-4 Classificar um Pin como Experimentado

Rastreabilidade: [UC - Classificar um Pin como Experimentado](especificacoes_caso_uso.md#classificar-um-pin-como-experimentado)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc4.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc4.png)

### IDUC-5 Denunciar um Pin

Rastreabilidade: [UC - Denunciar um Pin](especificacoes_caso_uso.md#denunciar-um-pin)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc5.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc5.png)

### IDUC-6 Seguir outro usuário

Rastreabilidade: [UC - Seguir outro usuário](especificacoes_caso_uso.md#seguir-outro-usuario)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc6.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc6.png)

### IDUC-7 Pesquisar por foto

Rastreabilidade: [UC - Pesquisar por foto](especificacoes_caso_uso.md#pesquisar-por-foto)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc7.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc7.png)

### IDUC-8 Organizar Pasta

Rastreabilidade: [UC - Organizar Pasta](especificacoes_caso_uso.md#organizar-pasta)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc8.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc8.png)

### IDUC-9 Visualizar Feed

Rastreabilidade: [UC - Visualizar Feed](especificacoes_caso_uso.md#visualizar-feed)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc9.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc9.png)

### IDUC-10 Fazer login

Rastreabilidade: [UC - Fazer login](especificacoes_caso_uso.md#fazer-login)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc10.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc10.png)

### IDUC-11 Visualizar Pin

Rastreabilidade: [UC - Visualizar Pin](especificacoes_caso_uso.md#visualizar-pin)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc11.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc11.png)

### IDUC-12 Cadastro de usuário

Rastreabilidade: [UC - Cadastro de usuário](especificacoes_caso_uso.md#cadastro-de-usuario)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc12.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc12.png)

### IDUC-13 Enviar mensagem para outros usuários

Rastreabilidade: [UC - Enviar mensagem para outros usuários](especificacoes_caso_uso.md#enviar-mensagem-para-outros-usuarios)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc13.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc13.png)

### IDUC-14 Ocultar um Pin

Rastreabilidade: [UC - Ocultar um Pin](especificacoes_caso_uso.md#ocultar-um-pin)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc14.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc14.png)

### IDUC-15 Salvar um Pin

Rastreabilidade: [UC - Salvar um Pin](especificacoes_caso_uso.md#salvar-um-pin)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc15.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc15.png)

### IDUC-16 Enviar um Pin

Rastreabilidade: [UC - Enviar um Pin](especificacoes_caso_uso.md#enviar-um-pin)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc16.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc16.png)

### IDUC-17 Editar Perfil

Rastreabilidade: [UC - Editar Perfil](especificacoes_caso_uso.md#editar-perfil)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc17.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc17.png)

### IDUC-18 Compartilhar Pasta

Rastreabilidade: [UC - Compartilhar Pasta](especificacoes_caso_uso.md#compartilhar-pasta)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc18.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc18.png)

### IDUC-19 Criar Pasta

Rastreabilidade: [UC - Criar Pasta](especificacoes_caso_uso.md#criar-pasta)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc19.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc19.png)

### IDUC-20 Comentar em um Pin

Rastreabilidade: [UC - Comentar em um Pin](especificacoes_caso_uso.md#comentar-em-um-pin)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc20.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc20.png)

### IDUC-21 Definir interesses

Rastreabilidade: [UC - Definir interesses](especificacoes_caso_uso.md#definir-interesses)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc21.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc21.png)

### IDUC-22 Pesquisar por tema

Rastreabilidade: [UC - Pesquisar por tema](especificacoes_caso_uso.md#pesquisar-por-tema)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc22.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc22.png)

### IDUC-23 Classificação de Pastas

Rastreabilidade: [UC - Classificação de Pastas](especificacoes_caso_uso.md#classificacao-de-pastas)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc23.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc23.png)

### IDUC-24 Ir para a fonte de um Pin

Rastreabilidade: [UC - Ir para a fonte de um Pin](especificacoes_caso_uso.md#ir-para-a-fonte-de-um-pin)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc24.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc24.png)

### IDUC-25 Visualizar aba seguindo

Rastreabilidade: [UC - Visualizar aba seguindo](especificacoes_caso_uso.md#visualizar-aba-seguindo)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc25.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc25.png)

### IDUC-26 Sair do aplicativo Pinterest

Rastreabilidade: [UC - Sair do aplicativo Pinterest](especificacoes_caso_uso.md#sair-do-aplicativo-pinterest)

![](img/inspecao_caso_de_uso/inspecao_caso_de_uso_iduc26.png)

![](img/inspecao_caso_de_uso/resultado_caso_de_uso_iduc26.png)

## Resultados

Com a realização da inspeção dos casos de uso foi verificado que todos eles possuem algum ponto em que precisam de melhoria, porém tivemos um resultado de 22 aprovados e 4 reprovados dentre os 26 casos de uso feitos pelo grupo no módulo de Modelagem de Requisitos.

## Conclusão

A inspeção dos casos de uso com base nos referenciais teóricos possibilitou a avaliação de métricas essenciais e a identificação de erros. Com as tabelas de inspeção, a correção de cada caso de uso será facilitada com os pontos fracos já listados.

## Referências

[1] - Gregolin, Rosângela. Uma proposta de inspeção em modelos de caso de uso. 2007. Disponível em: <http://cassiopea.ipt.br/teses/2007_EC_Rosangela_Gregolin.pdf>. Acesso em: 01 nov. 2018.

[2] - IBM. Creating use case. Disponível em: <https://www.ibm.com/support/knowledgecenter/SSB2MU_8.1.3/com.ibm.rhp.uml.diagrams.doc/topics/rhp_c_dm_use_case_diagrams.html>. Acesso em: 02 nov. 2018.

[3] - IBM. Use-cases. Disponível em: <https://www.ibm.com/developerworks/rational/library/content/RationalEdge/may02/m_chapter4_jr.pdf>. Acesso em: 02 nov. 2018.

[4] - IBM. Creating use case models. Disponível em: <https://www.ibm.com/support/knowledgecenter/SSB2MU_8.1.4/com.ibm.rhp.harmonyse.doc/topics/t_createusecases.htmll>. Acesso em: 02 nov. 2018.
