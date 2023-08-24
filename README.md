# sql_e_nosql
SQL vs NoSQL: Entendendo as Diferenças

SQL (Structured Query Language):

1. Definição: SQL é uma linguagem padrão para gerenciar e consultar bancos de dados relacionais.
2. Características:
Estrutura Relacional: Os dados são armazenados em tabelas com linhas e colunas. As tabelas têm relações entre si através de chaves primárias e estrangeiras.
Esquema Fixo: Antes de adicionar dados, o esquema da tabela (ou seja, a estrutura da tabela) precisa ser definido.
Transações ACID: Suporta propriedades ACID (Atomicidade, Consistência, Isolamento, Durabilidade), garantindo confiabilidade.
Consultas Complexas: Devido à sua natureza relacional, é possível fazer consultas complexas usando JOINs, UNIONs, etc.
3. Exemplos de Bancos de Dados SQL: MySQL, PostgreSQL, Oracle, SQL Server.
NoSQL:
1. Definição: NoSQL refere-se a bancos de dados que não são baseados em tabelas relacionais e não usam SQL como linguagem de consulta principal.
2. Características:
Flexibilidade de Esquema: Não é necessário definir um esquema fixo antes de inserir dados. Isso permite uma maior flexibilidade e evolução dos dados ao longo do tempo.
Escalar Horizontalmente: Projetado para escalar distribuindo os dados em vários servidores, em vez de apenas aumentar a capacidade de um único servidor.
Modelos Variados: Existem diferentes tipos de bancos de dados NoSQL, incluindo bancos de dados de documentos, chave-valor, coluna-larga e grafos.
3. Tipos de Bancos de Dados NoSQL:
Documentos: Armazenam dados em documentos, geralmente em formato JSON. Exemplo: MongoDB.
Chave-Valor: Armazenam dados como um conjunto de pares de chave-valor. Exemplo: Redis, DynamoDB.
Coluna-larga: Armazenam dados em colunas em vez de linhas. Exemplo: Cassandra, HBase.
Grafos: Projetados para armazenar dados relacionados e suas conexões. Exemplo: Neo4j, OrientDB.
4. Linguagem de Consulta: A maioria dos bancos de dados NoSQL não usa SQL como linguagem de consulta. Em vez disso, eles têm suas próprias linguagens ou APIs específicas para interagir com os dados.
Quando usar SQL ou NoSQL?
SQL: É preferível quando a estrutura dos dados é bem definida, a integridade dos dados é uma prioridade, e/ou quando são necessárias consultas complexas e relações entre os dados.
NoSQL: É uma boa escolha quando a estrutura dos dados pode evoluir ao longo do tempo, ao esperar um grande volume de dados que precisa ser escalado horizontalmente, ou quando os dados não se encaixam bem em um modelo relacional.
Ambos têm seus pontos fortes e fracos, e a escolha entre SQL e NoSQL deve ser baseada nas necessidades específicas do projeto. Em muitos sistemas modernos, é comum ver uma combinação de bancos de dados SQL e NoSQL para aproveitar o melhor de ambos os mundos.
