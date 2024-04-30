# **Desafio Dio Cria Catálogo de Jogos Usando Boas Praticas de Arquitetura com .NET**


**Objetivo:** Desenvolver uma API REST para um catálogo de jogos digitais, utilizando boas práticas de arquitetura com .NET.

**Requisitos:**

1. A API deve permitir o cadastro, atualização, visualização e remoção de jogos.
2. Os jogos devem ser armazenados em um banco de dados.
3. Cada jogo deve ter um nome, produtora, preço e ano de lançamento.
4. Não deve ser permitido o cadastro de dois jogos com o mesmo nome e produtora.

**Consultas e Resultados:**

1. **Consulta:** GET /api/jogos **Resultado:** Retorna uma lista de todos os jogos cadastrados.
2. **Consulta:** POST /api/jogos **Resultado:** Cadastra um novo jogo e retorna os detalhes do jogo cadastrado.
3. **Consulta:** PUT /api/jogos/{id} **Resultado:** Atualiza os detalhes de um jogo existente e retorna os detalhes atualizados.
4. **Consulta:** DELETE /api/jogos/{id} **Resultado:** Remove um jogo do catálogo.

**Resumo :**

Neste desafio, você irá desenvolver uma API REST para um catálogo de jogos digitais. Você irá utilizar o .NET, uma plataforma de desenvolvimento popular que suporta várias linguagens de programação, como C# e F#. O .NET é conhecido por sua eficiência, segurança e por ser ótimo para criar aplicativos de alto desempenho.

 Implementar várias operações CRUD (Create, Read, Update, Delete) para gerenciar os jogos no catálogo. Isso inclui adicionar novos jogos, visualizar jogos existentes, atualizar detalhes de jogos e remover jogos. Cada jogo terá um nome, produtora, preço e ano de lançamento, e você não poderá adicionar dois jogos com o mesmo nome e produtora.



## **Criacão do Projeto**

### **1. Desafio: Criando um Catálogo de Jogos Usando Boas Práticas de Arquitetura com .NET**

**Objetivo:** Projetar e implementar um catálogo de jogos usando boas práticas de arquitetura com .NET.

**Diretrizes:**

- Crie um aplicativo de API RESTful usando o ASP.NET Core.
- Use o Entity Framework Core para acesso a dados.
- Implemente princípios de arquitetura limpa, como separação de interesses e injeção de dependência.
- Teste seu aplicativo usando testes unitários e de integração.

#### **Consultas e Resultados:**

**Consulta 1: Obter todos os jogos**

```plaintext
GET /api/games
```

**Resultado:** Retorna uma lista de todos os jogos no catálogo.

**Consulta 2: Obter um jogo por ID**

```plaintext
GET /api/games/{id}
```

**Resultado:** Retorna o jogo com o ID especificado.

**Consulta 3: Criar um novo jogo**

```plaintext
POST /api/games
```

**Resultado:** Cria um novo jogo e retorna o jogo recém-criado.

**Consulta 4: Atualizar um jogo**

```plaintext
PUT /api/games/{id}
```

**Resultado:** Atualiza o jogo com o ID especificado e retorna o jogo atualizado.

**Consulta 5: Excluir um jogo**

```plaintext
DELETE /api/games/{id}
```

**Resultado:** Exclui o jogo com o ID especificado.

#### **2. Explorar Mais com Explicações e Montagem do Desafio**

- **Arquitetura Limpa:** Aprenda sobre os princípios e benefícios da arquitetura limpa, incluindo separação de interesses e injeção de dependência.
- **ASP.NET Core:** Explore os recursos e funcionalidades do ASP.NET Core para criar aplicativos API RESTful.
- **Entity Framework Core:** Investigue como usar o Entity Framework Core para acesso a dados e mapeamento objeto-relacional.
- **Testes Unitários e de Integração:** Compreenda a importância dos testes unitários e de integração para garantir a qualidade do código.

#### **3.  Apresentável**

#### **** Catálogo de Jogos: Boas Práticas de Arquitetura com .NET

**Introdução:**

- Defina boas práticas de arquitetura e explique sua importância no desenvolvimento de software.
- Apresente o desafio de criar um catálogo de jogos usando .NET.

#### **Metodologia:**

- Descreva as etapas para projetar e implementar o catálogo de jogos, enfatizando as boas práticas de arquitetura usadas.
- Explique como o ASP.NET Core, Entity Framework Core e testes unitários/de integração contribuem para a qualidade e manutenção do aplicativo.

#### **Resultados:**

- Demonstre os resultados das consultas SQL fornecidas, incluindo a obtenção de jogos, criação e atualização de jogos.
- Destaque os benefícios das boas práticas de arquitetura, como separação de interesses, testabilidade e manutenção.

#### Arquitetura aplicada

------

<img src="C:\CRIA-CATALOGO-JOGOS-COM-ARQT-DOT-NET-SQL-SERVER-MARIO2\API_Catalogo_Jogos-F-MARIO\img\Arquitetura.png" style="zoom:60%;" />



#### Telas

------

<img src="C:\CRIA-CATALOGO-JOGOS-COM-ARQT-DOT-NET-SQL-SERVER-MARIO2\API_Catalogo_Jogos-F-MARIO\img\Index.png" style="zoom:50%;" />



<img src="C:\CRIA-CATALOGO-JOGOS-COM-ARQT-DOT-NET-SQL-SERVER-MARIO2\API_Catalogo_Jogos-F-MARIO\img\GET.png" style="zoom:50%;" />

<img src="img\GET2.png" style="zoom:50%;" />

#### **Conclusão:**

- Resuma as principais lições aprendidas e os benefícios de usar boas práticas de arquitetura no desenvolvimento de software.
- Incentive os participantes a explorar mais sobre boas práticas de arquitetura e tecnologias usadas no desafio.
