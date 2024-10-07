# Desafio de modelagem dimensional

### Objetivo: 
Criar o diagrama dimensional – star schema – com base no diagrama relacional disponibilizado.

### Foco:
**Professor** – objeto de análise

**Obs.:** *Não é necessário refletir dados sobre os alunos!*

- montar o esquema em estrela;
- foco na análise dos dados dos professores;
- tabela fato deve refletir diversos dados sobre professor:
  - cursos ministrados,
  - departamento ao qual faz parte
  - ...

### A fazer:
- Deverá ser criada a tabela Fato que contêm o contexto analisado;
- criação das tabelas dimensão que serão compostas pelos detalhes relacionados ao contexto;
- adicione uma tabela dimensão de datas;
  - data de oferta das disciplinas,
  - data de oferta dos cursos,
  - ...

*Para compensar a falta de dados de datas do modelo relacional, suponha que você tem acesso aos dados e crie os campos necessários para modelagem.*

