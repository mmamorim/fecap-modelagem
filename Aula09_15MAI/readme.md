<img src="../banner.svg" width="100%">

# Aula 8 - 15/05/2026

# Atividade Investigativa — Diagnóstico de Problemas em Engenharia de Software

---

# Contexto

Uma startup chamada **FastMarket** decidiu desenvolver um sistema para realizar pedidos online em pequenos mercados de bairro.

A ideia do projeto é permitir que clientes:

- façam pedidos;
- acompanhem entregas;
- realizem pagamentos;
- consultem produtos disponíveis.

O desenvolvimento começou rapidamente devido à pressão para lançar o sistema antes dos concorrentes.

Após alguns meses, a equipe percebeu que o projeto começou a apresentar diversos problemas técnicos e organizacionais.

Vocês foram contratados como uma equipe de consultoria para analisar o projeto e identificar possíveis problemas relacionados à modelagem, requisitos, arquitetura e processo de desenvolvimento.

---

# Requisitos Levantados pela Equipe

Abaixo estão alguns requisitos definidos pela equipe original do projeto.

## Requisitos Funcionais

- O sistema deve permitir login.
- O sistema deve gerar pedidos.
- O sistema deve ser moderno.
- O sistema deve mostrar produtos.
- O sistema deve processar pagamentos.

---

## Requisitos Não Funcionais

- O sistema deve ser rápido.
- O sistema deve ser bonito.
- O sistema deve funcionar bem.
- O sistema deve ser seguro.

---

# Histórias de Usuário Definidas

A equipe organizou algumas funcionalidades utilizando histórias de usuário.

## História 1

> Como sistema, quero salvar produtos para funcionar corretamente.

---

## História 2

> Como desenvolvedor, quero usar banco de dados para armazenar informações.

---

## História 3

> Como usuário, quero comprar produtos.

---

## História 4

> Como administrador, quero uma tela bonita.

---

# Casos de Uso Modelados

A equipe também produziu alguns casos de uso para o sistema.

### Atores Identificados

- Cliente
- Banco de Dados
- Tela Inicial
- Entregador

---

### Casos de Uso Relacionados

| Ator | Caso de Uso |
|---|---|
| Cliente | Página Home |
| Cliente | Comprar Produto |
| Cliente | Tela de Carrinho |
| Banco de Dados | Banco SQL |
| Entregador | Fazer PIX |

---

# Arquitetura do Sistema

A equipe implementou o sistema da seguinte maneira:

~~~text
Usuário
   ↓
Tela Principal
   ↓
Banco de Dados
~~~

Além disso:

- as telas realizam consultas SQL diretamente;
- regras de negócio estão espalhadas em diferentes arquivos;
- parte da lógica de pagamento está implementada na interface;
- não existe separação clara entre front-end e back-end.

---

# Processo de Desenvolvimento

O projeto utiliza Scrum.

Porém, durante o desenvolvimento:

- novas funcionalidades são adicionadas diariamente na Sprint;
- o Sprint Backlog muda constantemente;
- não existem prioridades claras no Product Backlog;
- as Daily Scrums duram cerca de 1 hora;
- os usuários só visualizam o sistema próximo da entrega final.

---

# Objetivo da Atividade

Em grupo, analisem o sistema apresentado e identifiquem problemas relacionados aos conteúdos estudados na disciplina.

---

# Questões para Discussão

## Engenharia de Software

- Quais fases do ciclo da engenharia de software parecem estar sendo negligenciadas?
- Como isso pode impactar o projeto?

---

## Requisitos

- Existem problemas nos requisitos apresentados?
- Quais requisitos são funcionais?
- Quais requisitos não funcionais estão mal definidos?

---

## Histórias de Usuário

- As histórias seguem corretamente o padrão de user stories?
- O que poderia ser melhorado?

---

## Casos de Uso

- Existem elementos que não deveriam ser atores?
- Existem itens que não representam casos de uso?
- O foco está realmente no usuário?

---

## Arquitetura

- Quais problemas arquiteturais podem ser identificados?
- Existe separação de responsabilidades?
- Como o sistema poderia ser reorganizado?

---

## Scrum

- O Scrum está sendo utilizado corretamente?
- Quais problemas podem surgir pela forma como as Sprints estão sendo conduzidas?

---

# Desafio Final

Após identificar os problemas:

- proponham melhorias;
- reorganizem os requisitos;
- corrijam histórias de usuário;
- sugiram uma arquitetura melhor;
- indiquem boas práticas que poderiam melhorar o projeto.

---

# Dica

Nem todos os problemas estão explícitos.

O objetivo da atividade não é apenas encontrar erros óbvios, mas relacionar conceitos da disciplina com situações próximas da realidade do desenvolvimento de software.

```