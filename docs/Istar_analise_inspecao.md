# Inspeção IStar

## Planejamento

Após discutir como seria a inspeção dos IStars, chegou-se a um consenso entre a dupla que seria utilizado partes do método citado pelos casos de uso contendo pequenas modificações, onde irá conter os campos que serão preenchidos com “sim” ou “não” de acordo com a avaliação que obteve ao julgar se uma condição foi ou não satisfeita para um determinado caso, uma coluna será dedicada às observações destacadas sobre IStar modelado no momento da análise. Ao contrário dos casos de uso, o IStar não conta com o campo “impacto” por possuir um tipo de modelo de maior completude, que envolve tanto requisitos funcionais quanto não funcionais.

## Visão Geral

Esse documento tem por objetivo analisar todos os modelos de dependência e rationales feitos na modelagem dos requisitos. A partir do diagnóstico será adquirido o embasamento necessário para modificar e otimizar todos os diagramas IStars desenhados no projeto, apontando as principais falhas técnicas e conceituais, além de oferecer meios para o aperfeiçoamento.

## Inspeção

### Strategic Dependency Models

#### SD1

| Questões Avaliativas / Diagrama avaliado | SD1 | Observações | Melhorias |
|--|--|--|--|
| Os atores mais importantes estão sendo representados ? | Sim | Possui o usuário e o Pinterest como atores | - |
| Possui todos os elementos necessários? | Sim | Mesmo que o diagrama não explore todos os elementos do _framework_, a análise mostrou que foram usados aqueles que são necessários para representar a sua finalidade | - |
| Os _softgoals_ têm relação com os requisitos não funcionais levantados anteriormente? | - |  Este modelo não possui _softgoals_ | - |
| Todas as tarefas estão corretamente representadas ? | Sim | Todas representam funcionalidades que possuem um fluxo pré determinado para ser executada.  | - |
| As metas estão descritas na linguagem passiva? | - | Este modelo não possui metas | - |
| Os _softgoals_ representam critérios de qualidade? | -| Este modelo não possui softgoals | - |
| As dependências estão no sentido correto? | Não | Modelo com dependêcia em sentidos opostos para um mesmo elemento | Colocar depedências no sentido correto e em uma só direção. |
| O diagrama está de acordo com a última versão do _framework_? | Sim | Está atualizado em sua última versão | - |
| Os elementos utilizados (meta, tarefa, recurso, agentes) foram escolhidos de forma correta (condizem com o seu objetivo no _framework_)? | Sim | Modelo usa muitas notações de acordo com o framework, mas há falta de softgoals. | - |
| Os elementos metas estão descritos na voz passiva? | - | O modelo não possui metas | - |

#### SD2

| Questões Avaliativas / Diagrama avaliado | SD2 | Observações | Melhoria |
|--|--|--|--|
| Os atores mais importantes estão sendo representados ? | Sim | Possui o usuário e o Pinterest como atores | - |
| Possui todos os elementos necessários? | Sim | Possui todos os elementos | - |
| Os _softgoals_ têm relação com os requisitos não funcionais levantados anteriormente? | Não | O diagrama possui apenas um _softgoal_ e este não está presente nas etapas anteriores do projeto | Verificar se o softgoal é um requisito do projeto que não foi levantado ou se ele foi representado como softgoal erroneamente. |
| Todas as tarefas estão corretamente representadas ? | Não | Há funcionalidades que deveriam ser representadas como tarefa, mas estão em forma de meta. | Converter as metas incorretas em tarefas |
| As metas estão descritas na linguagem passiva? | Sim | - | - |
| Os _softgoals_ representam critérios de qualidade? | Sim | - | - |
| O diagrama está de acordo com a última versão do _framework_? | Sim | Está atualizado com sua última versão | - |
| Os elementos utilizados (meta, tarefa, recurso, agentes) foram escolhidos de forma correta (condizem com o seu objetivo no _framework_)? | Sim | - | - |
| Os elementos metas estão descritos na voz passiva? | Sim | - | - |

### Strategic Rationale Models

#### SR1 - Definir Interesses

| Questões Avaliativas / Diagrama avaliado | SR1 | Observações | Melhoria |
|--|--|--|--|
| Está baseado em alguma documentação? | Sim | - | Usar documentação complementar |
| Possui todos os elementos necessários (softgoal, meta, recurso, tarefas)? | Sim | - | - |
| Os atores foram representados de forma correta? | Sim | - | - |
| A ligações com 'and' e 'or' foram feitas corretamente? | Sim | - | - |
| As ligações de 'and' e 'or' estão na ultima versão do framework? | Sim | - | - |
| Está esteticamente padronizado com os demais diagramas? | Sim | - | - |
| As ligações representadas de acordo com a sua função? | Sim | - | - |
| Os hardgoals estão bem definidos(voz passiva)? | Sim | Estão todos descritos na voz passiva. | - |
| Os hardgoals estão presentes no SD? | Não | - | Atualizar SR com SD. |

#### SR2 - Classificar Pastas
| Questões Avaliativas / Diagrama avaliado | SR2 | Observações | Melhoria |
|--|--|--|--|
| Está baseado em alguma documentação? | Sim | - | Usar documentação complementar |
| Possui todos os elementos necessários (softgoal, meta, recurso, tarefas)? | Sim | - | - |
| Os atores foram representados de forma correta? | Sim | - | - |
| A ligações com 'and' e 'or' foram feitas corretamente? | Sim | - | - |
| As ligações de 'and' e 'or' estão na ultima versão do framework? | Sim | - | - |
| Está esteticamente padronizado com os demais diagramas? | Não | Linhas não estão retas e a meta possui formato diferente do outros modelos (menos arredondados). | Redesenhar diagrama com linhas retas e aumentar a circunferência das bordas das metas |
| As ligações representadas de acordo com a sua função? | Não | Recurso está representado errado. | Atualizar a ligação de uma tarefa com recurso colocando "need" entre eles. |
| Os hardgoals estão bem definidos(voz passiva)? | Sim | Estão todos descritos na voz passiva. | - |
| Os hardgoals estão presentes no SD? | Não | - | Atualizar SR com SD. |

#### SR3 - Enviar Pin
| Questões Avaliativas / Diagrama avaliado | SR3 | Observações | Melhoria |
|--|--|--|--|
| Está baseado em alguma documentação? | Sim | - | Usar documentação complementar |
| Possui todos os elementos necessários (softgoal, meta, recurso, tarefas)? | Não | Não possui _softgoals_ | Atualizar com mais _softgoals_ |
| Os atores foram representados de forma correta? | Sim  | Necessitou a ocorrência de mais um ator que não foi diretamente citado no SD. | - |
| A ligações com 'and' e 'or' foram feitas corretamente? | Sim | - | - |
| As ligações de 'and' e 'or' estão na ultima versão do framework? | Não | Há notação de ambas as versões | Atualizar os elementos obsoletos de acordo com a nova versão |
| Está esteticamente padronizado com os demais diagramas? | Sim | - | - |
| As ligações representadas de acordo com a sua função? |Não | Recurso está representado errado. | Atualizar a ligação de uma tarefa com recurso colocando "need" entre eles. |
| Os hardgoals estão bem definidos(voz passiva)? | Sim | Estão todos descritos na voz passiva. | - |
| Os hardgoals estão presentes no SD? | Não | - | Atualizar SR com SD. |


### SR4 - Pesquisar PIN

| Questões Avaliativas / Diagrama avaliado | SR4 | Observações | Melhoria |
|--|--|--|--|
| Está baseado em alguma documentação? | Sim | - | Usar documentação complementar |
| Possui todos os elementos necessários (softgoal, meta, recurso, tarefas)? | Não | Não possui _softgoals_ | Adicionar mais softgoals |
| Os atores foram representados de forma correta? | Sim  | Necessitou a ocorrência de mais um ator que não foi diretamente citado no SD. | - |
| A ligações com 'and' e 'or' foram feitas corretamente? | Sim | - | - |
| As ligações de 'and' e 'or' estão na ultima versão do framework? | Não | Há notação de ambas as versões | Atualizar os elementos obsoletos de acordo com a nova versão |
| Está esteticamente padronizado com os demais diagramas? | Não | A modelagem está diferente dos outros Srs (cor) | - |
| As ligações representadas de acordo com a sua função? | Não | Recursos são representados com a notação need | - |
| Os hardgoals estão bem definidos(voz passiva)? | Sim | Estão todos descritos na voz passiva. | - |
| Os hardgoals estão presentes no SD? | Não | - | Atualizar SR com SD. |

### SR5 - Pinterest

| Questões Avaliativas / Diagrama avaliado | SR4 | Observações | Melhoria |
|--|--|--|--|
| Está baseado em alguma documentação? | Sim | - | Usar documentação complementar |
| Possui todos os elementos necessários (softgoal, meta, recurso, tarefas)? | Sim | - | - |
| Os atores foram representados de forma correta? | Sim  | - | - |
| A ligações com 'and' e 'or' foram feitas corretamente? | Sim | - | - |
| As ligações de 'and' e 'or' estão na ultima versão do framework? | Sim | - | - |
| Está esteticamente padronizado com os demais diagramas? | Sim | - | - |
| As ligações representadas de acordo com a sua função? | Sim | - | - |
| Os hardgoals estão bem definidos(voz passiva)? | Sim | - | - |
| Os hardgoals estão presentes no SD? | Não | - | Atualizar SR com SD. |
