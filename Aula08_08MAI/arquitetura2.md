# Arquitetura de Sistemas

> Disciplina: Modelagem de Software e Arquitetura de Sistemas

---

# O que é Arquitetura de Sistemas?

Arquitetura de sistemas representa a forma como um software é organizado.

Ela define:

- como as partes do sistema se conectam;
- como as responsabilidades são separadas;
- como o sistema funciona de forma estruturada.

---

# Pensando de Forma Simples

A arquitetura funciona como a planta de uma casa.

Antes de construir, precisamos planejar:

- organização;
- divisão de responsabilidades;
- comunicação entre partes;
- estrutura geral.

No software acontece algo parecido.

---

# Estrutura Básica de um Sistema

```mermaid
flowchart TD

A[Usuário]
B[Tela do Sistema]
C[Lógica da Aplicação]
D[Banco de Dados]

A --> B
B --> C
C --> D
```

---

# Interface do Usuário

A interface é a parte visual do sistema.

Exemplos:

- telas;
- botões;
- formulários;
- menus.

Tecnologias comuns:

- HTML;
- CSS;
- Java Swing;
- JavaFX;
- React;
- Vue.

---

# Exemplo de Interface

```mermaid
flowchart LR

A[Tela de Login]
B[Tela Principal]
C[Tela de Cadastro]

A --> B
B --> C
```

---

# Lógica da Aplicação

A lógica da aplicação contém as regras do sistema.

Exemplos:

- validar login;
- calcular valores;
- verificar estoque;
- salvar informações.

---

# Exemplo de Fluxo

```mermaid
flowchart TD

A[Usuário faz Login]
B[Validar Usuário]
C[Permitir Acesso]
D[Exibir Erro]

A --> B
B -->|Correto| C
B -->|Incorreto| D
```

---

# Banco de Dados

O banco de dados armazena as informações do sistema.

Exemplos:

- usuários;
- produtos;
- pedidos;
- mensagens.

Tecnologias comuns:

- SQLite;
- MySQL;
- PostgreSQL.

---

# Comunicação com Banco

```mermaid
flowchart TD

A[Tela]
B[Lógica do Sistema]
C[Banco de Dados]

A --> B
B --> C
C --> B
B --> A
```

---

# Arquitetura em Camadas

Um modelo muito comum é a arquitetura em camadas.

Cada camada possui uma responsabilidade específica.

```mermaid
flowchart TD

A[Interface]
B[Regras de Negócio]
C[Banco de Dados]

A --> B
B --> C
```

---

# Separação de Responsabilidades

Separar responsabilidades ajuda a:

- organizar o projeto;
- facilitar manutenção;
- reduzir erros;
- melhorar o trabalho em equipe.

---

# Exemplo de Organização

```mermaid
flowchart TD

A[Telas]
B[Classes de Regra]
C[Classes de Banco]

A --> B
B --> C
```

---

# Front-end e Back-end

## Front-end

Parte visual do sistema.

## Back-end

Parte responsável pelo processamento e regras.

---

# Exemplo Simplificado

```mermaid
flowchart LR

A[Usuário]
B[Front-end]
C[Back-end]
D[Banco]

A --> B
B --> C
C --> D
```

---

# APIs

Muitos sistemas modernos utilizam APIs para comunicação.

API é uma ponte entre sistemas.

---

# Exemplo de API

```mermaid
flowchart LR

A[Aplicativo]
B[API]
C[Banco de Dados]

A --> B
B --> C
```

---

# Exemplo do Cotidiano

## Aplicativo de Delivery

```mermaid
flowchart TD

A[Cliente]
B[Aplicativo]
C[Sistema de Pedidos]
D[Banco de Dados]

A --> B
B --> C
C --> D
```

---

# Importância da Arquitetura

Uma boa arquitetura ajuda a:

- melhorar organização;
- facilitar manutenção;
- permitir crescimento do sistema;
- reduzir problemas futuros.

---

# Erros Comuns

## Misturar responsabilidades

Exemplo ruim:

```mermaid
flowchart TD

A[Tela]
B[Banco de Dados]

A --> B
```

A interface acessando diretamente o banco pode dificultar manutenção.

---

# Modelo Mais Organizado

```mermaid
flowchart TD

A[Tela]
B[Lógica]
C[Banco]

A --> B
B --> C
```

---

# Resumo

- Arquitetura organiza o sistema;
- Sistemas possuem partes com responsabilidades diferentes;
- A separação melhora manutenção e organização;
- Arquitetura em camadas é muito utilizada;
- Diagramas ajudam a visualizar o funcionamento do sistema.
