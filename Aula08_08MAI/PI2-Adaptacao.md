<img src="../banner.svg" width="100%">

# Adaptação da Seção de Arquitetura do Sistema

Durante o acompanhamento dos projetos, observei que muitos dos sistemas desenvolvidos pela turma ainda estão em estágio inicial, utilizando aplicações desktop simples e banco de dados local.

Por esse motivo, decidi adaptar a seção de arquitetura do sistema para um formato mais compatível com o nível atual dos projetos e com os conteúdos trabalhados na disciplina.

O objetivo desta atividade não é produzir uma arquitetura corporativa complexa, mas sim demonstrar que a equipe consegue:

- compreender a organização básica do sistema;
- identificar responsabilidades das partes do software;
- representar a estrutura geral da aplicação;
- documentar tecnologias e componentes utilizados.

Assim, itens avançados como:

- microsserviços;
- Docker;
- CI/CD;
- cloud computing;
- autenticação avançada;
- filas de mensagens;
- APIs externas complexas;
- ambientes de produção;

não serão obrigatórios nesta etapa do curso.

---

# Nova Proposta Simplificada

A seção de arquitetura deverá conter apenas os tópicos abaixo.

---

# 6. Arquitetura do Sistema

## 6.1. Visão Geral do Sistema

Descrevam brevemente:

- nome do sistema;
- objetivo do sistema;
- público-alvo;
- principais funcionalidades.

---

## 6.2. Estrutura Geral do Sistema

Expliquem de forma simples como o sistema está organizado.

Exemplo:

> O sistema possui telas desktop para interação com o usuário, regras de negócio implementadas em Java e armazenamento de dados em banco SQLite.

---

## 6.3. Tecnologias Utilizadas

Listem as principais tecnologias utilizadas no projeto.

Exemplo:

- Java;
- Java Swing;
- SQLite;
- JDBC.

---

## 6.4. Componentes do Sistema

Descrevam as principais partes do sistema.

Exemplo:

| Componente | Responsabilidade |
|---|---|
| Tela de Login | Permitir autenticação |
| Tela Principal | Navegação do sistema |
| Banco de Dados | Armazenar informações |
| Classe de Conexão | Realizar acesso ao banco |

---

## 6.5. Diagrama Simplificado

Criem um diagrama simples mostrando:

- usuário;
- telas do sistema;
- lógica da aplicação;
- banco de dados.

Exemplo textual:

~~~text
Usuário
   ↓
Telas do Sistema
   ↓
Lógica da Aplicação
   ↓
Banco de Dados
~~~

---

## 6.6. Organização de Arquivos e Pastas

Mostrem como o projeto está organizado.

Exemplo:

~~~text
/src
   /telas
   /model
   /database
   /util
~~~

---

# Observação Importante

A simplicidade da arquitetura não é um problema.

Nesta etapa do curso, o mais importante é:

- organização;
- clareza;
- compreensão da estrutura do sistema;
- documentação coerente com o projeto desenvolvido.

O documento deve representar o sistema real construído pela equipe, evitando adicionar tecnologias ou conceitos que não foram utilizados no projeto.
