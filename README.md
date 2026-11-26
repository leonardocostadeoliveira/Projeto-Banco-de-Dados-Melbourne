# Projeto-Banco-de-Dados-Melbourne
Projeto acadêmico de banco de dados utilizando MySQL e SQL

🗄️ Projeto de Banco de Dados — Amerikanos

Projeto acadêmico desenvolvido durante o 3º semestre do curso de Análise e Desenvolvimento de Sistemas, na disciplina de Programação e Desenvolvimento de Banco de Dados, no Centro Universitário Anhanguera.

O projeto teve como objetivo desenvolver uma estrutura de banco de dados relacional para a empresa fictícia Amerikanos, um e-commerce que precisava substituir seus controles descentralizados por uma solução estruturada e centralizada.

🎯 Objetivo do projeto

Desenvolver um banco de dados relacional capaz de organizar e centralizar as informações de clientes, endereços, produtos e pedidos, proporcionando maior controle operacional e suporte à geração de informações gerenciais.

O trabalho partiu da análise do cenário atual (AS IS) e da definição de uma solução futura (TO BE).

🛠️ Tecnologias e ferramentas

- MySQL: criação, estruturação e manipulação do banco de dados.
- MySQL Workbench: desenvolvimento e sincronização da estrutura do banco.
- SQL: criação de tabelas, inserção de dados e consultas.
- DER: modelagem e representação dos relacionamentos entre entidades.

🏗️ Estrutura do banco de dados

O banco foi estruturado com entidades relacionadas por chaves primárias e estrangeiras.

Entre as principais tabelas desenvolvidas estão:

Tabela| Finalidade
clientes| Armazenamento dos dados dos clientes
endereco| Informações de endereço dos clientes
tipo_genero| Classificação de gênero
tipo_endereco| Classificação dos endereços
produto| Cadastro e informações dos produtos
categorias_produtos| Organização das categorias
cores_produtos| Cadastro das cores dos produtos
sons_produto| Informações de sons dos produtos
imagens_produto| Armazenamento das imagens dos produtos
itens_pedido| Estrutura dos itens dos pedidos
itens_pedidos_detalhes| Detalhamento dos itens
status_pedido| Controle dos status dos pedidos

📊 Modelagem de dados

O projeto contou com a elaboração de um Diagrama Entidade-Relacionamento (DER), representando as entidades, seus atributos e os relacionamentos entre as tabelas.

A estrutura foi desenvolvida utilizando chaves primárias (PRIMARY KEY) e chaves estrangeiras (FOREIGN KEY), buscando manter a integridade e a organização dos dados.

💻 Conceitos e recursos SQL aplicados

Durante o desenvolvimento, foram trabalhados:

- CREATE TABLE — criação de tabelas.
- ALTER TABLE — alteração de estruturas.
- INSERT INTO — inserção de registros.
- PRIMARY KEY — definição de chaves primárias.
- FOREIGN KEY — criação de relacionamentos.
- UNIQUE — restrições de unicidade.
- CREATE OR REPLACE VIEW — criação e atualização de views.
- INNER JOIN — relacionamento e consulta entre tabelas.
- GROUP BY e ORDER BY — agrupamento e ordenação de resultados.
- CTE (Common Table Expression) — organização de consultas complexas.
- ROW_NUMBER() — numeração de registros utilizando funções de janela.
- TIMESTAMPDIFF() — cálculo de idade a partir da data de nascimento.
- COUNT(), AVG() e ROUND() — funções de agregação e cálculos.

📈 Consultas e análises desenvolvidas

Foram elaboradas consultas para extrair informações gerenciais da base de dados, incluindo:

1. Volume de clientes por gênero, idade e região geográfica.
2. Quantidade e percentual de clientes por gênero.
3. Média de idade dos clientes por gênero e região do país.
4. Município com maior quantidade de clientes acima de 50 anos.
5. Quantidade de clientes com menos de 21 anos.
6. Quantidade de clientes que utilizam contas de e-mail Gmail.

As consultas utilizaram recursos de agrupamento, junções, funções de agregação, CTEs e funções de janela.

🔍 Resultados e aprendizado

O desenvolvimento permitiu aplicar conceitos de modelagem e programação de banco de dados em um cenário próximo de uma necessidade empresarial.

Entre os principais aprendizados estão:

- Estruturação de bancos de dados relacionais.
- Criação e relacionamento de tabelas.
- Integridade referencial.
- Manipulação e consulta de dados utilizando SQL.
- Desenvolvimento de consultas analíticas.
- Utilização de Views e CTEs.
- Sincronização de estruturas utilizando MySQL Workbench.

🚀 Próximas etapas previstas

Conforme o escopo original, o projeto prevê a evolução das análises relacionadas às vendas e ao faturamento, incluindo:

- Identificação dos produtos mais vendidos.
- Análise do faturamento mensal.
- Desenvolvimento de um dashboard utilizando Microsoft Power BI.

Essas etapas representam possibilidades de continuidade do projeto.

👥 Desenvolvimento

Projeto acadêmico desenvolvido em equipe, com orientação do professor da disciplina de Programação e Desenvolvimento de Banco de Dados.

Instituição: Centro Universitário Anhanguera de São Paulo — Santo André.

Curso: Análise e Desenvolvimento de Sistemas.

Ano: 2026.

Autor: Leonardo Costa de Oliveira.

---

Projeto desenvolvido com foco na aplicação prática de conceitos de banco de dados relacionais e linguagem SQL.
