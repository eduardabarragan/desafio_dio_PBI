# Desafio de Projeto DIO - (detalhado)
## Desafio de projeto processando e transformando dados com Power BI
- [x] Integração do Power BI com MySQL no Azure
- [x] Criação de uma instância na Azure para MySQ
- [x] Criar o Banco de dados com base disponível no github: realizado na conta da julianazelatto com o script_company e a inserção dos dados.
- [x] Integração do Power BI com MySQL no Azure
- [x] Verificar problemas na base a fim de realizar a transformação dos dados

## Diretrizes para transformação dos dados

- [x] Verificação os cabeçalhos e tipos de dados
- [x] Modificção os valores monetários para o tipo double preciso
- [x] Verificação a existência dos nulos e analise a remoção
- [x] Verificação se há algum colaborador sem gerente
- [x] Verificação se há algum departamento sem gerente
- [x] Preenchimento das lacunas
- [x] Verificação do número de horas dos projetos
- [x] Separação de colunas complexas
- [x] Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá como base a tabela employee.
- [x] Eliminação das colunas desnecessárias
- [x] Junção dos colaboradores e respectivos nomes dos gerentes . 
- [x] Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores
- [x] Mescle os nomes de departamentos e localização. Utilizado o mesclar porque faz que cada combinação departamento-local seja único, auziliando na criação do modelo estrela em um módulo futuro, pois o  atribuir impede a restrição de integridade referencial feita pela mescla.
- [x] Agrupamento dos dados a fim de saber quantos colaboradores existem por gerente
- [x] Eliminação das colunas desnecessárias, que não serão usadas no relatório, de cada tabela

### Conclusão do projeto, muito obrigada pela atenção!
