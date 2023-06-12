
# Exercícios (Normalização) 

Considere a definição das tabelas abaixo e normalize-as até a terceira forma 
normal

#### 1)ALOCACAO_PROJETO {COD_PROJ, TIPO_PROJETO, DESCRICAO, COD_FUNC, NOME, COD_CARGO, NOME_CARGO, SALARIO, DATA_INICIO_ALOCAO, TEMPO_ALOCACAO}

Um projeto pode ter vários funcionários alocados a partir de uma data inicial 
por um determinado tempo de alocação. Os funcionários possuem um cargo 
e são remunerados em função do cargo. Um funcionário pode ser alocado 
em mais de um projeto. 

#### 2) MOVIMENTO {COD_PRODUTO, NUMERO_ALMOXARIFADO, DATA_MOVIMENTO, TIPO_MOVIMENTO, NOME-PRODUTO, VALOR_PRODUTO, LOCAL_ALMOXARIFADO, COD_EMPREGADO_RESPONSÁVEL_SAÍDA,NOME_EMPREGADO_RESP_SAIDA, COD_DEPARTAMENTO_EMPREG_RESP_SAIDA, NOME_DEPARTAMENTO, COD_FORNECEDOR_ENTRADA, RAZAO_SOCIAL_FORNECEDOR, DATA_VENDA, NOM_CLIENTE, CPF, E_MAIL_CLIENTE, ENDER_CLIENTE, TEL_CLIENTE} 

Um Almoxarifado registra entrada e saída de produtos de uma empresa. A 
saída de um produto é sempre para atender uma venda feita em uma data 
para um cliente que é identificada por uma nota fiscal de venda. A entrada de 
um produto no almoxarifado é sempre em função de um fornecimento feito 
por um fornecedor da empresa. A empresa tem interesse em manter 
informações dos clientes e dos fornecedores. 

#### 3) CORRIDA_F1 { COD_CAMPEONATO, COD_PISTA, COD_PILOTO, DENOM_CAMPEONATO, NOME_PISTA, TAMANHO_PISTA, COD_PAIS, COD_PAIS_DA_PISTA, NOME_PAIS, NOME_PILOTO, COLOCACAO_CORRIDA, DATA_CORRIDA }

O campeonato de F1 será realizado em diferentes pistas, de tamanhos 
diferentes em países diferentes. Serão realizadas corridas nas pistas onde se 
deseja registrar a data e o nome e colocação de cada piloto que participou da 
corrida. Um pais pode ter mais de uma pista.

#### 4) AVALIACAO_ESCOLAR { MATRICULA, NOME, COD_CURSO, NOTA1, NOM_PROFESSOR, NOTA2, SITUACAO_FINAL, COD_DISC, NOM_DISCIPLINA, NOM_CURSO, TURNO, COD_PROFESSOR }

Uma escola criou um cadastro de avaliações feitas com os dados dos alunos, 
cursos, professores. Porem há muitos problemas na atualização deste cadastro 
pois as informações estão duplicadas e consome muito tempo atualizar tudo. É 
necessário rever este modelo.
