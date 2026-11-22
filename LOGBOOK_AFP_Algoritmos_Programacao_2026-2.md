LOGBOOK AFP — Algoritmos e Programação (2026.2)
Identificação
Campo	Informação
Nome do estudante: 	Luíz Eduardo Da Rocha Moraes
Curs: ENGENHARIA DE SOFTWARE
Unidade curricular	Algoritmos e Programação — UnDB 2026.2
Professor	Rondineli Seba Salomão
App-base do CRUD	Aplicativo de streaming inspirado no Disney+
Repositório	https://github.com/LuizEduardoMoraes/Algoritmo-e-Programa-o/blame/dc583baf4afb7256b65c9cbfe927c44b74039bb4/LOGBOOK_AFP_Algoritmos_Programacao_2026-2.md
Dupla de revisão	Aurélio
Função	Autor do próprio CRUD e revisor do CRUD de um colega


Nota de integridade: este documento organiza os registros e apresenta respostas-modelo contextualizadas ao projeto. Onde não foram fornecidas evidências concretas — código, commits, testes executados, feedback recebido, resultado da P1 ou detalhes das revisões — isso está indicado. Antes de entregar, substitua os trechos sinalizados pelas informações que realmente aconteceram. Não declare como executada uma atividade que não foi realizada.

Regras de registro
O Logbook deve mostrar o processo de aprendizagem, incluindo decisões, erros, justificativas e fontes. Cada decisão técnica precisa estar relacionada a um objeto de conhecimento e, quando possível, a uma referência. O Campo 01 e o Checkpoint são atividades sem consulta: não devem ser reconstruídos ou alterados depois da realização. O histórico de commits do GitHub é uma evidência do processo.
Projeto: aplicativo de streaming
O CRUD tem como referência um aplicativo de streaming inspirado no Disney+. O sistema pode organizar um catálogo de filmes e séries. Para cada título, podem ser considerados dados como nome, categoria, ano de lançamento e classificação indicativa. As operações do CRUD são cadastrar, consultar/listar, atualizar e excluir títulos.
GRUPO 1
Registro do Ciclo 01 — 12/08 — Preparação do laboratório e escolha do projeto
1. Desafio do ciclo: Conhecer as ferramentas utilizadas nas aulas de programação e organizar o ambiente de desenvolvimento.
2. O que implementei: Conheci a proposta do CRUD e comecei a compreender a importância de organizar os códigos e manter os arquivos salvos no repositório. A comprovação específica de arquivos e commits deve ser conferida no histórico do GitHub.
3. Objetos de conhecimento mobilizados: Ambiente de desenvolvimento, organização de arquivos, repositório, Git e GitHub.
4. Desvio ou dificuldade: Ainda tenho dificuldade em compreender a organização de um projeto e a utilização do GitHub.
5. Decisão de ajuste e fonte: Praticar a criação e a organização de arquivos Python e aprender a utilizar o GitHub para armazenar o projeto e acompanhar seu histórico. Referência: documentação oficial do GitHub, especialmente os materiais introdutórios sobre repositórios e commits.
6. Feedback recebido: [Inserir a orientação real recebida do professor ou dos colegas. Não foi informado o conteúdo desse feedback.]
7. Próximo passo: Definir os dados que serão utilizados no aplicativo de streaming e começar a desenvolver um programa com variáveis e entrada de dados.
Registro do Ciclo 02 — 19/08 — Variáveis, tipos de dados e entrada/saída
1. Desafio do ciclo: Aprender a armazenar informações em variáveis e receber dados do usuário utilizando Python.
2. O que implementei: Trabalhei com os conceitos de variáveis, input() e print(), além dos tipos int, float e str. No contexto do aplicativo, esses tipos podem representar ano de lançamento, avaliação numérica e título/categoria.
3. Objetos de conhecimento mobilizados: Variáveis, atribuição de valores, tipos primitivos, entrada e saída de dados.
4. Desvio ou dificuldade: Uma dificuldade foi compreender que input() retorna uma string. Quando é necessário realizar cálculos ou comparações numéricas, é preciso converter o valor para int ou float.
5. Decisão de ajuste e fonte: Praticar a conversão dos dados antes de realizar operações matemáticas e verificar se o tipo da variável corresponde à operação. Fonte: documentação oficial do Python — Tutorial, introdução informal.
6. Feedback recebido: [Inserir a devolutiva real recebida durante a aula ou nos exercícios.]
7. Próximo passo: Estudar os operadores matemáticos e relacionais para construir condições no programa.
Campo 01 — Instrumento de entrada
Atenção: o enunciado determina que este campo seja realizado sem consulta e não seja editado posteriormente. O texto abaixo reproduz a resposta que já constava no material fornecido; mantenha-o apenas se corresponder ao que foi efetivamente escrito no momento da atividade.

1a. Objetos de conhecimento identificados
1. Tipos de dados int, float e str, utilizados para armazenar informações.
2. Entrada e saída de dados com input() e print().
3. Estruturas condicionais (if, elif e else), utilizadas para tomar decisões.
1b. Lacunas — o que preciso descobrir
1. Tenho dificuldade em entender como organizar os dados recebidos pelo usuário e armazená-los corretamente.
2. Ainda preciso aprender a validar entradas para evitar que o usuário informe dados de tipos incorretos.
3. Tenho dificuldade em organizar as condições e os laços de repetição para controlar o funcionamento de um programa.
1c. Hipótese inicial
Acredito que os problemas de um sistema CRUD podem acontecer quando os dados são cadastrados sem validação ou quando as condições do programa não verificam corretamente as informações. Também considero que erros nos tipos de dados podem prejudicar as operações de cadastro, consulta, atualização e exclusão.
Campo 02 — Aprofundamento pós-aula
2a. Referências e contribuições
- Referência 1: Documentação oficial do Python — Tutorial, seção de introdução à programação: https://docs.python.org/3/tutorial/introduction.html
  Contribuição: Ajudou a compreender variáveis, tipos de dados, operadores, entrada e saída de informações e estruturas básicas da linguagem.
- Referência 2: Allen B. Downey — Think Python, 3ª edição: https://allendowney.github.io/ThinkPython/
  Contribuição: Apresenta fundamentos da programação e ajuda a compreender como organizar instruções, trabalhar com variáveis e desenvolver o raciocínio lógico.
2b. Hipótese revisada
Depois de aprofundar meus conhecimentos, percebi que os problemas de um CRUD não acontecem somente no cadastro. Também podem ocorrer durante a consulta, a atualização e a exclusão dos dados. Entendi que é importante utilizar variáveis com tipos adequados, validar as informações recebidas pelo input() e utilizar estruturas condicionais para evitar operações incorretas.
2c. Dimensionamento inicial de recursos
Recurso	Quantidade estimada	Justificativa técnica
Horas de estudo de Python	6 horas	Revisar variáveis, tipos de dados, operadores e condicionais.
Casos de teste	10 testes	Verificar entradas válidas, vazias e incorretas.
Arquivos Python	2 arquivos	Considerar a separação entre programa principal e testes, se necessário.
Dados de teste	10 registros	Simular títulos de filmes e séries para verificar o funcionamento do sistema.


Registro do Ciclo 03 — 26/08 — Operadores, fluxogramas e paradigmas
1. Desafio do ciclo: Compreender como os operadores e a lógica de programação permitem construir decisões e resolver problemas.
2. O que implementei: Estudei os operadores utilizados em Python e a organização da sequência de instruções de um programa. [Acrescentar os exercícios ou arquivos efetivamente produzidos.]
3. Objetos de conhecimento mobilizados: Operadores aritméticos (+, -, *, /), operadores relacionais (==, !=, >, <, >=, <=) e operadores lógicos (and, or, not).
4. Desvio ou dificuldade: Uma dificuldade foi diferenciar o operador de atribuição = do operador de comparação ==.
5. Decisão de ajuste e fonte: Praticar expressões simples e observar que = atribui um valor a uma variável, enquanto == compara dois valores. Fonte: documentação oficial do Python — expressões e operadores.
6. Feedback recebido: [Inserir feedback real, se houve.]
7. Próximo passo: Aplicar operadores relacionais e lógicos em estruturas condicionais para validar as opções do menu do aplicativo.
Registro do Ciclo 04 — 02/09 — Estruturas condicionais
1. Desafio do ciclo: Utilizar if, elif e else para controlar diferentes caminhos de execução.
2. O que implementei: Estudei estruturas condicionais e expressões booleanas. No CRUD, essas estruturas podem verificar a opção escolhida no menu e validar se um título existe antes de permitir uma alteração ou exclusão.
3. Objetos de conhecimento mobilizados: Estruturas condicionais, operadores relacionais, expressões booleanas e indentação.
4. Desvio ou dificuldade: A principal dificuldade foi compreender a ordem das condições e manter a indentação correta. Uma condição muito abrangente pode impedir que outra condição seja executada.
5. Decisão de ajuste e fonte: Organizar as condições da mais específica para a mais geral e testar diferentes entradas. Fonte: tutorial oficial do Python sobre estruturas de controle.
6. Feedback recebido: [Inserir orientação real recebida.]
7. Próximo passo: Estudar condicionais aninhadas e operadores lógicos para criar validações mais completas.
GRUPO 2
Registro do Ciclo 05 — 09/09 — Condicionais aninhadas e operadores lógicos
1. Desafio do ciclo: Combinar condições para validar mais de uma informação antes de executar uma operação.
2. O que implementei: Estudei o uso de condicionais aninhadas e dos operadores and, or e not. No aplicativo de streaming, uma validação pode verificar se o título foi informado e se o ano de lançamento está dentro de um formato numérico.
3. Objetos de conhecimento mobilizados: Condicionais aninhadas, operadores lógicos e expressões booleanas.
4. Desvio ou dificuldade: Uma dificuldade possível é construir expressões com várias condições sem compreender corretamente a relação entre elas. A combinação inadequada de and e or pode permitir entradas inválidas.
5. Decisão de ajuste e fonte: Separar as validações em etapas e testar combinações verdadeiras e falsas. Fonte: documentação oficial do Python sobre expressões booleanas.
6. Feedback recebido: [Inserir feedback real.]
7. Próximo passo: Utilizar condições dentro de laços de repetição para manter o menu funcionando até que o usuário escolha sair.
Registro do Ciclo 06 — 30/09 — Devolutiva da P1 e estruturas de repetição
1. Desafio do ciclo: Compreender como repetir instruções utilizando for e while e controlar a continuidade de um programa.
2. O que implementei: Estudei os laços for e while, além de break e continue. No aplicativo, um laço pode manter o menu principal em execução até a escolha da opção de saída.
3. Objetos de conhecimento mobilizados: Laços de repetição, condição de parada, iteração, break e continue.
4. Desvio ou dificuldade: Uma dificuldade é definir corretamente a condição de parada do while. Se ela não for atualizada, o programa pode entrar em repetição indefinida.
5. Decisão de ajuste e fonte: Verificar a condição de continuidade e testar a opção de saída. Fonte: documentação oficial do Python — estruturas de controle.
6. Feedback da P1: O resultado ou a nota da P1 não foi informado. [Inserir a devolutiva e os pontos que precisam ser melhorados, conforme a avaliação real.]
7. Próximo passo: Aplicar laços de repetição para percorrer e exibir os títulos armazenados.
Registro do Ciclo 07 — 07/10 — Listas: armazenamento e iteração
1. Desafio do ciclo: Compreender como armazenar vários registros em uma estrutura de dados e percorrer seus elementos.
2. O que implementei: Estudei listas e operações de armazenamento e iteração. No aplicativo, uma lista pode reunir os títulos cadastrados no catálogo.
3. Objetos de conhecimento mobilizados: Listas, índices, elementos, append(), remoção e laços de iteração.
4. Desvio ou dificuldade: É necessário prestar atenção aos índices, pois a primeira posição de uma lista é 0. Também é importante verificar se a lista possui elementos antes de acessar uma posição.
5. Decisão de ajuste e fonte: Testar listas vazias, listas com um elemento e listas com vários elementos. Fonte: documentação oficial do Python — estruturas de dados.
6. Feedback recebido: [Inserir feedback real.]
7. Próximo passo: Estudar busca de registros e dicionários para organizar os dados de cada título.
Registro do Ciclo 08 — 14/10 — Busca, dicionários e matrizes
1. Desafio do ciclo: Localizar informações armazenadas e compreender estruturas que organizam dados relacionados.
2. O que implementei: Estudei busca e introdução a dicionários e matrizes. Um dicionário pode representar um título com campos como nome, gênero, ano e classificação indicativa.
3. Objetos de conhecimento mobilizados: Busca sequencial, listas, dicionários, chaves e valores; matrizes como estruturas organizadas em linhas e colunas.
4. Desvio ou dificuldade: Uma dificuldade é acessar corretamente os valores de um dicionário por meio de suas chaves e tratar o caso em que uma chave não existe.
5. Decisão de ajuste e fonte: Padronizar os nomes das chaves e verificar sua existência antes de acessar os valores. Fonte: documentação oficial do Python — tipos de dados e estruturas de dados.
6. Feedback recebido: [Inserir feedback real.]
7. Próximo passo: Integrar cadastro, consulta, atualização e exclusão em um CRUD completo.
Checkpoint Conceitual Individual
Não preencher por reconstrução. O documento de orientação informa que o Checkpoint é individual, sem consulta e com duração de 20 minutos, mas não contém as três perguntas do Apêndice A nem as respostas efetivamente dadas pelo estudante.
- Questão 1: [Transcrever a questão aplicada e registrar a resposta original.]
- Questão 2: [Transcrever a questão aplicada e registrar a resposta original.]
- Questão 3: [Transcrever a questão aplicada e registrar a resposta original.]
Campo 03 — Execução e desvios
Os itens abaixo são um roteiro de reflexão relacionado ao CRUD. Ajuste-os para corresponder ao código e aos testes que realmente foram executados.

3a. O que foi executado
O projeto de referência é um catálogo de filmes e séries. A estrutura lógica do CRUD precisa permitir cadastrar um título, listar ou consultar os títulos, atualizar informações e excluir um registro. [Informar quais dessas operações estão efetivamente implementadas e em quais arquivos.]
3b. Casos de teste e resultados
Caso	Entrada ou situação	Resultado esperado	Resultado real
1	Cadastrar título com dados válidos	Registro incluído	[Preencher após executar]
2	Cadastrar título sem nome	Entrada recusada ou solicitada novamente	[Preencher após executar]
3	Consultar título existente	Dados exibidos	[Preencher após executar]
4	Consultar título inexistente	Mensagem informativa	[Preencher após executar]
5	Atualizar título existente	Dados alterados	[Preencher após executar]
6	Excluir título existente	Registro removido	[Preencher após executar]


3c. Análise técnica
Os principais pontos que precisam ser verificados são a validação dos dados de entrada, a conversão dos tipos, a busca de registros existentes e o tratamento de opções inválidas no menu. Não é possível afirmar que os testes passaram sem executar o programa e registrar os resultados.
3d. Desvios e correções
[Registrar cada erro realmente encontrado, a mensagem apresentada, a causa identificada e a correção aplicada. Exemplo de análise, caso tenha ocorrido: se o ano foi recebido como texto, a comparação numérica pode falhar; a conversão para int deve ocorrer depois de validar a entrada.]
3e. Fontes consultadas
- Documentação oficial do Python: https://docs.python.org/3/
- Allen B. Downey, Think Python, 3ª edição: https://allendowney.github.io/ThinkPython/
Campo 04 — Interação com Inteligência Artificial
Ferramenta utilizada: ChatGPT
Data da interação registrada: 22/11/2026
Finalidade: Apoio à organização e compreensão do Logbook de Algoritmos e Programação e à contextualização dos conceitos de Python no projeto de CRUD inspirado em um aplicativo de streaming.

Prompt utilizado (síntese fiel do pedido):

“Com base no Logbook de Algoritmos e Programação, ajude a responder e organizar os registros e campos do trabalho. O aplicativo escolhido como base do CRUD é o Disney; o repositório está no GitHub e Aurélio participou das duas revisões. A apresentação da Defesa Técnica foi ruim.”

Síntese da resposta da IA:

A IA organizou sugestões para relacionar os conteúdos de programação ao catálogo de filmes e séries: variáveis e tipos de dados para armazenar informações; condicionais para validar entradas e opções; laços para manter o menu em execução; listas e dicionários para organizar títulos; e funções para separar as operações do CRUD. Também destacou que a revisão por pares deve registrar critérios, testes, riscos e decisões técnicas.

O que considerei útil:
- Relacionar os conteúdos de Python a um contexto concreto, o catálogo de filmes e séries.
- Diferenciar as responsabilidades de cadastro, consulta, atualização e exclusão.
- Utilizar testes para verificar entradas válidas, vazias e registros inexistentes.
- Registrar as dificuldades e justificar tecnicamente as decisões.
O que questionei ou não posso aceitar sem verificar:
- Uma sugestão de código não comprova que o código foi implementado ou executado.
- A IA não pode afirmar que testes passaram sem resultados observados.
- Não foram informados o resultado da P1, as perguntas do Checkpoint, os detalhes do feedback do professor nem os resultados concretos das revisões de Aurélio.
- Não devo registrar como realizada uma atividade que foi apenas sugerida.
Decisão final: Utilizar a IA como apoio para organizar conceitos e levantar possibilidades de teste, mas conferir cada sugestão com o código real, com a documentação oficial do Python e com as orientações do professor.
GRUPO 3
Registro do Ciclo 09 — 21/10 — Atualização e exclusão: CRUD completo
1. Desafio do ciclo: Compreender e integrar as quatro operações do CRUD: Create, Read, Update e Delete.
2. O que implementei: O projeto foi pensado como um catálogo de filmes e séries. [Descrever quais operações foram realmente programadas e indicar os arquivos ou commits.]
3. Objetos de conhecimento mobilizados: Listas, dicionários, busca, condicionais, atualização de valores e remoção de elementos.
4. Desvio ou dificuldade: Uma situação que precisa ser testada é tentar atualizar ou excluir um título que não existe. O programa deve localizar o registro antes de executar a operação.
5. Decisão de ajuste e fonte: Realizar a busca pelo título ou identificador antes de atualizar ou excluir. Fonte: documentação oficial do Python sobre listas e dicionários.
6. Feedback recebido: [Inserir o feedback real do colega ou professor.]
7. Próximo passo: Revisar o CRUD de um colega e registrar os achados da revisão por pares.
Campo 05 — Revisão por pares nº 1
Campo	Informação
Autor do CRUD revisado	Aurélio [confirmar se Aurélio é o autor do projeto revisado]
Repositório revisado	[Inserir o link do repositório de Aurélio]
Revisor	Luíz Eduardo Da Rocha Moraes
Unidade curricular	Algoritmos e Programação — 2026.2
Ciclo / data	Ciclo 09 — 21/10 [confirmar data da revisão]


5a. Etapas do processo de revisão
Etapa	Responsável	Status	Desvio / justificativa
1. Identificar os requisitos e as operações do CRUD	Revisor	[Confirmar]	[Descrever o que foi feito]
2. Verificar se o projeto pode ser executado	Revisor	[Confirmar]	[Registrar eventual dificuldade]
3. Testar cadastro e consulta	Revisor	[Confirmar]	[Registrar entradas e resultados reais]
4. Testar atualização e exclusão	Revisor	[Confirmar]	[Registrar entradas e resultados reais]
5. Registrar e devolver feedback ao autor	Revisor	[Confirmar]	[Registrar o feedback efetivamente enviado]


5b. Insumos e critérios de qualidade
Recurso	Quantidade planejada	Quantidade utilizada	Variação	Justificativa
Casos de teste	6	[Preencher]	[Preencher]	Verificar as operações principais.
Registros de teste	5	[Preencher]	[Preencher]	Avaliar a manipulação de mais de um registro.
Requisitos do CRUD	4 operações	[Preencher]	[Preencher]	Conferir cadastro, consulta, atualização e exclusão.


5c. Controle de qualidade
- Critério: as operações do CRUD devem executar a ação correspondente e tratar registros inexistentes ou entradas inválidas.
- A solução atende? [Marcar Sim, Parcialmente ou Não somente depois da revisão real.]
- Justificativa: [Registrar o que foi observado no repositório e nos testes.]
5d. Gestão de riscos
- Risco: não conseguir executar o projeto revisado por ausência de instruções, dependências ou arquivos necessários.
- Mitigação: conferir o README, identificar os arquivos de entrada e solicitar ao autor as informações necessárias, sem alterar o projeto sem autorização.
5e. Rastreabilidade das decisões técnicas
Data	Decisão técnica	Responsável	Objeto de conhecimento	Fundamentação / referência
[Data real]	Verificar os dados antes de cadastrar	Revisor	Validação de entrada	Documentação oficial do Python sobre tipos e entrada de dados.
[Data real]	Verificar a existência do registro antes de alterar	Revisor	Busca e condicionais	Documentação oficial do Python sobre estruturas de controle.
[Data real]	Testar o tratamento de registro inexistente	Revisor	Condicionais e tratamento de casos-limite	Casos de teste definidos para o CRUD.


Feedback ao colega: [Registrar o feedback real, indicando um ponto positivo, um problema reproduzível e uma sugestão objetiva.]
Registro do Ciclo 10 — 28/10 — Modularização: funções
1. Desafio do ciclo: Compreender como dividir um programa em funções menores, cada uma com uma responsabilidade.
2. O que implementei: Estudei a modularização do CRUD. Uma organização possível é separar as operações em funções como cadastrar(), listar(), buscar(), alterar(), excluir() e menu(). [Indicar quais funções existem efetivamente no código.]
3. Objetos de conhecimento mobilizados: Definição e chamada de funções, parâmetros, argumentos, retorno e escopo de variáveis.
4. Desvio ou dificuldade: É necessário compreender quando uma função deve receber parâmetros e quando deve retornar um valor. Também é preciso evitar depender de variáveis locais fora do escopo em que foram definidas.
5. Decisão de ajuste e fonte: Separar as responsabilidades e testar cada função individualmente. Fonte: documentação oficial do Python — definição de funções.
6. Feedback recebido: [Inserir feedback real da revisão por pares.]
7. Próximo passo: Compreender recursividade e comparar sua aplicação com estruturas de repetição.
Registro do Ciclo 11 — 04/11 — Recursividade
1. Desafio do ciclo: Compreender o funcionamento de uma função recursiva e a importância de uma condição de parada.
2. O que implementei: Estudei o conceito de recursividade. Uma função recursiva chama a si mesma para resolver uma parte menor de um problema. [Descrever eventual exercício realmente implementado.]
3. Objetos de conhecimento mobilizados: Funções, chamadas recursivas, caso base, caso recursivo e pilha de execução.
4. Desvio ou dificuldade: Sem um caso base adequado, uma função recursiva pode continuar realizando chamadas até atingir o limite de recursão.
5. Decisão de ajuste e fonte: Identificar primeiro o caso base e depois verificar como cada chamada aproxima o problema desse caso. Fonte: documentação oficial do Python sobre definição de funções e limite de recursão.
6. Feedback recebido: [Inserir feedback real.]
7. Próximo passo: Revisar a organização do código e identificar oportunidades de refatoração.
Campo 06 — Próximos passos
6a. Decisão técnica que consigo explicar
Uma decisão técnica importante é verificar se um título existe antes de permitir sua atualização ou exclusão. Essa verificação evita que o programa tente modificar ou remover um registro inexistente. A decisão utiliza busca e estrutura condicional: primeiro localizo o registro; depois, se ele for encontrado, executo a operação. Se não for encontrado, apresento uma mensagem ao usuário. Essa lógica deve ser demonstrada no código real para ser considerada evidência de domínio.
6b. Lacuna técnica e plano de ação
- Lacuna: ainda preciso desenvolver maior segurança na organização do código em funções e na validação de entradas.
- Plano de ação:
  1. Revisar funções, parâmetros e retorno na documentação oficial do Python.
  2. Separar as operações do CRUD em funções com responsabilidades claras.
  3. Testar cada função com dados válidos, vazios e inexistentes.
  4. Registrar os resultados e corrigir os erros encontrados.
  5. Conferir se consigo explicar cada parte do programa sem depender de respostas prontas.
6c. Pergunta que a banca pode fazer
Pergunta: Por que é importante verificar se um título existe antes de atualizar ou excluir um registro do catálogo?

Resposta: É importante porque a atualização e a exclusão precisam atuar sobre um registro que esteja armazenado. Primeiro, o programa deve realizar uma busca para localizar o título. Essa busca pode percorrer uma lista ou consultar uma estrutura de dados. Depois, uma estrutura condicional verifica se o registro foi encontrado. Se existir, o programa permite a alteração ou exclusão. Caso contrário, apresenta uma mensagem informando que o título não foi localizado. Essa validação evita operações incorretas e melhora a confiabilidade do CRUD.

Objeto de conhecimento mobilizado: Busca em estruturas de dados, listas, dicionários e estruturas condicionais.

Fonte: Documentação oficial do Python — https://docs.python.org/3/tutorial/
Registro do Ciclo 12 — 11/11 — Refatoração e qualidade de código
1. Desafio do ciclo: Compreender como melhorar a organização e a legibilidade do código sem alterar o comportamento esperado do programa.
2. O que implementei: Estudei refatoração e qualidade de código. No CRUD, a revisão pode identificar repetição de instruções, nomes pouco claros e funções com muitas responsabilidades. [Registrar as alterações realmente feitas.]
3. Objetos de conhecimento mobilizados: Modularização, funções, legibilidade, reutilização de código, organização e testes.
4. Desvio ou dificuldade: Uma dificuldade é modificar a estrutura do código sem introduzir novos erros ou alterar as operações que já funcionavam.
5. Decisão de ajuste e fonte: Fazer alterações pequenas e executar novamente os casos de teste após cada mudança. Fonte: documentação oficial do Python e materiais de qualidade de código utilizados na disciplina.
6. Feedback recebido: [Inserir o feedback real da segunda revisão.]
7. Próximo passo: Avaliar minha evolução conceitual e identificar os conteúdos que ainda preciso aprofundar.
Campo 05 — Revisão por pares nº 2
Campo	Informação
Autor do CRUD revisado	Aurélio [confirmar se foi o mesmo projeto/colega]
Repositório revisado	[Inserir o link do repositório de Aurélio]
Revisor	Luíz Eduardo Da Rocha Moraes
Ciclo / data	Ciclo 12 — 11/11 [confirmar data da revisão]


5a. Etapas do processo de revisão
Etapa	Responsável	Status	Desvio / justificativa
1. Conferir a organização geral do código	Revisor	[Confirmar]	[Descrever o que foi observado]
2. Verificar nomes de variáveis e funções	Revisor	[Confirmar]	[Registrar achados]
3. Procurar trechos repetidos ou funções extensas	Revisor	[Confirmar]	[Registrar achados]
4. Executar casos de teste, inclusive entradas inválidas	Revisor	[Confirmar]	[Registrar resultados]
5. Enviar feedback ao autor	Revisor	[Confirmar]	[Registrar feedback real]


5b. Insumos e critérios de qualidade
Recurso	Quantidade planejada	Quantidade utilizada	Variação	Justificativa
Casos de teste	8	[Preencher]	[Preencher]	Verificar o comportamento em diferentes entradas.
Funções analisadas	[Definir]	[Preencher]	[Preencher]	Avaliar a divisão de responsabilidades.
Registros de teste	5	[Preencher]	[Preencher]	Verificar a consistência das operações.


5c. Controle de qualidade
- Critério: legibilidade, organização das funções, ausência de duplicação desnecessária e funcionamento correto dos casos de teste.
- A solução atende? [Marcar somente após a revisão.]
- Justificativa: [Descrever os resultados efetivamente observados.]
5d. Gestão de riscos
- Risco: uma alteração de organização pode modificar acidentalmente o comportamento do programa.
- Mitigação: comparar o comportamento antes e depois da alteração e executar novamente os casos de teste.
5e. Rastreabilidade das decisões técnicas
Data	Decisão técnica	Responsável	Objeto de conhecimento	Fundamentação / referência
[Data real]	Verificar se as funções possuem responsabilidades claras	Revisor	Modularização e funções	Documentação oficial do Python sobre funções.
[Data real]	Conferir se os nomes identificam a finalidade das variáveis	Revisor	Legibilidade e organização	Critérios de qualidade trabalhados na disciplina.
[Data real]	Reexecutar testes depois de uma refatoração	Revisor	Testes e validação	Comparação dos resultados antes e depois da mudança.


Feedback ao colega: [Inserir o feedback real da segunda revisão.]
Campo 07 — Evolução conceitual
7a. O que eu pensava no início
No início, eu reconhecia alguns fundamentos de Python, como variáveis, tipos de dados, entrada e saída e estruturas condicionais. Minha hipótese inicial era que falhas em um CRUD poderiam ocorrer por falta de validação dos dados, condições incorretas ou incompatibilidade entre tipos. Também reconhecia que precisava melhorar a organização dos dados e compreender melhor os laços de repetição.
7b. O que aprendi
Objeto de conhecimento	O que eu não dominava	O que aprendi e consigo explicar	Evidência
Tipos de dados e conversão	Não compreendia completamente que input() retorna texto.	É necessário converter a entrada quando a operação exige um valor numérico e validar o dado recebido.	Campo 01, Campo 02 e Ciclo 02.
Condicionais e operadores lógicos	Tinha dificuldade em organizar condições e diferenciar = de ==.	= atribui valor; == compara valores. and, or e not combinam expressões booleanas.	Ciclos 03, 04 e 05.
Listas, dicionários e busca	Tinha dificuldade em organizar vários registros e localizar informações.	Listas armazenam conjuntos de elementos; dicionários organizam informações por chaves e valores; a busca permite localizar registros.	Ciclos 07 e 08.


Importante: a tabela descreve a evolução conceitual pretendida a partir dos registros existentes. Para afirmar que consegue demonstrar cada conteúdo, confirme que consegue explicar e apresentar um exemplo no seu próprio código.

7c. Equívocos que precisei corrigir
1. Equívoco: considerar que o valor recebido por input() já possui o tipo numérico desejado.
   Correção: input() retorna uma string; para realizar operações numéricas, é necessário converter o valor e validar a entrada.
   O que corrigiu: estudo dos tipos de dados e prática com int() e float().
2. Equívoco: confundir atribuição (=) com comparação (==).
   Correção: a atribuição armazena um valor em uma variável, enquanto a comparação verifica se dois valores são iguais.
   O que corrigiu: estudo dos operadores e prática de expressões condicionais.
7d. Transferência para outro contexto
Os conhecimentos do CRUD podem ser utilizados em um sistema de biblioteca. As variáveis armazenariam título, autor e ano de publicação; as listas ou os dicionários organizariam os livros; as condicionais verificariam se um livro existe antes de atualizar ou excluir; e os laços permitiriam percorrer o catálogo. Assim, os mesmos fundamentos podem ser aplicados em outro sistema de gerenciamento de informações.
7e. Avaliação honesta do percurso
Ainda preciso aprofundar a organização de programas em funções, a validação de entradas e a realização de testes. Também preciso ganhar mais segurança para explicar o funcionamento do código e justificar minhas decisões técnicas sem depender de ajuda externa. Meu próximo passo é revisar o CRUD, executar diferentes casos de teste, registrar os resultados reais e estudar os pontos em que ainda apresento dificuldade.
DEFESA TÉCNICA — 18/11
Registro informado pelo estudante: a apresentação da Defesa Técnica foi ruim/insatisfatória.

Não foi informada uma pontuação por critério. Portanto, não é possível atribuir uma nota numérica com segurança.
Critério	Registro
1. Domínio dos objetos de conhecimento	[Preencher com a avaliação ou devolutiva recebida.]
2. Aplicação do conteúdo à solução	[Preencher com a avaliação ou devolutiva recebida.]
3. Evolução conceitual	[Preencher com a avaliação ou devolutiva recebida.]
4. Capacidade de transferência	[Preencher com a avaliação ou devolutiva recebida.]
5. Argumentação sob pressão	[Preencher com a avaliação ou devolutiva recebida.]
6. Autonomia intelectual e coerência com o Logbook	[Preencher com a avaliação ou devolutiva recebida.]
Pontuação	[Não informada]
Conceito	[Não informado]


Reflexão sobre a apresentação: Considero que meu desempenho na apresentação não foi satisfatório. Preciso melhorar a preparação para explicar o funcionamento do programa, relacionar os conceitos estudados às decisões tomadas no código e responder aos questionamentos com mais clareza. Para evoluir, devo praticar a explicação de cada operação do CRUD, revisar os conceitos fundamentais e testar o programa antes de uma nova apresentação.
Registro do Encerramento — 18/11
1. O que apresentei/defendi: Apresentei o projeto de CRUD inspirado em um aplicativo de streaming. [Descrever o que foi efetivamente demonstrado.]
2. Objetos de conhecimento explorados pela banca: [Inserir os conteúdos que foram perguntados.]
3. Pergunta que mais me desafiou e como respondi: [Registrar a pergunta real e a resposta dada.]
4. O que levo deste semestre para o próximo módulo: A importância de compreender os fundamentos da lógica de programação, organizar o código, testar as operações e justificar tecnicamente as decisões tomadas.
Referências
- PYTHON SOFTWARE FOUNDATION. Python 3 Documentation. https://docs.python.org/3/
- DOWNEY, Allen B. Think Python, 3rd edition. https://allendowney.github.io/ThinkPython/
- GITHUB. Documentação do GitHub. https://docs.github.com/
Informações que ainda precisam ser completadas com dados reais
1. Curso e módulo.
2. Feedback do professor/colegas nos ciclos.
3. Resultado e devolutiva da P1.
4. Perguntas e respostas originais do Checkpoint (Apêndice A).
5. Arquivos, funções, commits e operações realmente implementadas no CRUD.
6. Resultados reais dos casos de teste.
7. Link do repositório de Aurélio e achados das duas revisões.
8. Pontuação ou devolutiva detalhada da Defesa Técnica.
