# Introdução à Banco de Dados

Um banco de dados é um sistema organizado para armazenar, gerenciar e acessar informações de maneira eficiente. 
Ele é utilizado em uma variedade de aplicações, desde sites e aplicativos até sistemas empresariais complexos. 
Em termos simples, é uma coleção de dados inter-relacionados, que podem ser manipulados e acessados de maneira rápida e eficaz.

Um banco de dados deve possuir as seguintes características

- Armazenamento
- Acesso
- Segurança
- Escalabilidade
- Concorrência

## Modelo de dados

texto


## Etapas de criação de um banco de dados

**Modelagem de Dados**: <br>
Modelagem é o processo de criar uma representação abstrata ou simplificada de um sistema ou conjunto de dados, com o objetivo de entender sua estrutura, funcionamento e inter-relações.

**Escolha do SGBD (Sistema de Gerenciamento de Banco de Dados)**: <br>
Escolher qual sistema será utilizado para criar e gerenciar o banco de dados:
Isso pode ser um SGBD relacional como MySQL ou PostgreSQL, ou um banco de dados NoSQL como MongoDB, dependendo das necessidades da aplicação.

**Criação do Banco de Dados**: <br>
Após a modelagem, o banco de dados é criado, levando em consideração a estrutura do modelo de dados. Isso envolve a criação de tabelas, definição de chaves primárias e estrangeiras, índices e outras configurações.

**Desenvolvimento de Aplicações e Consultas**: <br>
Agora que o banco de dados está pronto, você pode começar a desenvolver aplicações que interajam com ele e escrever consultas SQL (ou usar APIs, dependendo do banco de dados) para manipular e acessar os dados.

##   Modelagem

A modelagem seria a parte de "arquitetura" do banco, sendo o processo de criar uma primeira perspectiva de como o banco irá
funcionar, sendo o processo de planejamento do sistema, logo, é o primeiro passo durante a criação da base de dados. <br>

### Por que a Modelagem é Crucial no Início?

- Planejamento: Antes de criar o banco de dados fisicamente, é importante planejar como os dados se conectam e como serão usados. A modelagem ajuda a evitar falhas de estrutura que poderiam surgir mais tarde, se feitas sem um planejamento adequado.
- Evitar Redundância: A modelagem ajuda a evitar a redundância de dados, garantindo que a informação seja armazenada de forma eficiente, sem duplicação desnecessária.
- Relacionamentos: A modelagem também ajuda a identificar os relacionamentos entre os dados (por exemplo, um cliente pode ter múltiplos pedidos), o que é essencial para garantir que o banco de dados seja coeso e os dados possam ser acessados de forma eficaz.

A modelagem passa por alguns processos para definir como os dados serão organizados e armazenados da melhor forma.

| **Fase da Modelagem**       | **Objetivo**                                                               | **Aspectos**                                                                                          |
|-----------------------------|-----------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|
| **1. Modelagem Conceitual**  | Capturar as necessidades de negócios e representar o domínio do problema.   | - Definição das **entidades** (ex.: "Cliente", "Produto").<br>- Identificação dos **relacionamentos** entre as entidades.<br>- Uso de diagramas de **Entidade-Relacionamento (ER)**.<br>- Não se preocupa com a implementação técnica. |
| **2. Modelagem Lógica**     | Refino do modelo conceitual com foco na estrutura de dados.                 | - Definição das **tabelas** (no caso de bancos de dados relacionais).<br>- Definição de **atributos** para as entidades.<br>- Especificação de **chaves primárias** e **estrangeiras**.<br>- Consideração do tipo de banco de dados a ser utilizado (relacional, NoSQL, etc.). |
| **3. Modelagem Física**     | Implementação real do modelo de dados no sistema de banco de dados.         | - Definição de como os dados serão **armazenados fisicamente**.<br>- Criação de **índices** e otimização de **consultas**.<br>- Consideração de aspectos como **particionamento** de dados e **desempenho**.<br>- Determinação de **restrições de integridade** e **segurança**. |

Manutenção e Evolução:

Após a criação inicial, o banco de dados e o modelo de dados podem precisar ser ajustados ou expandidos à medida que as necessidades do sistema evoluem. A modelagem ajuda a garantir que as mudanças possam ser feitas de forma controlada e eficiente.
