<img src="../banner.svg" width="100%">

# Aula 3 - 27/03/2026

## O que são requisitos de software?

Requisitos de software são descrições das necessidades, expectativas e restrições relacionadas a um sistema que será desenvolvido. Em outras palavras, eles ajudam a definir **o que o sistema deve fazer** e **como ele deve se comportar** para atender aos objetivos do projeto e às necessidades dos usuários.

Os requisitos servem como base para o desenvolvimento do software, pois orientam a equipe sobre as funcionalidades esperadas, as regras de negócio, os limites do sistema e os critérios de qualidade.

De forma geral, um bom levantamento de requisitos contribui para reduzir erros de interpretação, evitar retrabalho e aumentar as chances de que o sistema final atenda ao que realmente foi solicitado.


## Técnicas de Levantamento de Requisitos

As técnicas de levantamento de requisitos são métodos utilizados para coletar informações junto aos stakeholders (usuários, clientes e envolvidos no projeto). A escolha da técnica adequada ajuda a compreender melhor o problema e definir corretamente o que o sistema deve fazer.

---

### 🔹 Entrevistas
Consistem em conversas diretas com stakeholders para entender necessidades, expectativas e regras do negócio.

---

### 🔹 Workshops
Reuniões colaborativas com vários participantes para discutir, alinhar e definir requisitos em conjunto.

---

### 🔹 Observação
O analista acompanha o usuário em seu ambiente de trabalho para entender como as atividades são realizadas na prática.

---

### 🔹 Questionários
Formulários com perguntas objetivas utilizados para coletar informações de um grande número de pessoas de forma rápida.


## Tipos de Requisitos

Os requisitos de software podem ser classificados em dois principais tipos: **funcionais** e **não funcionais**. Essa classificação ajuda a organizar e entender melhor o comportamento e as restrições do sistema.

---

### 🔹 Requisitos Funcionais
Descrevem **o que o sistema deve fazer**, ou seja, suas funcionalidades e comportamentos.

📌 Exemplos:
- O sistema deve permitir o cadastro de usuários  
- O sistema deve realizar autenticação (login)  
- O sistema deve gerar relatórios de vendas  

---

### 🔹 Requisitos Não Funcionais
Descrevem **como o sistema deve se comportar**, incluindo restrições, desempenho e qualidade.

📌 Exemplos:
- O sistema deve responder às requisições em até 2 segundos  
- O sistema deve estar disponível 99,9% do tempo  
- O sistema deve garantir a segurança dos dados dos usuários  


## Modelagem de Requisitos

A modelagem de requisitos organiza e representa as funcionalidades do sistema de forma compreensível para a equipe e stakeholders. Duas abordagens comuns são **casos de uso** e **histórias de usuário**.

---

### 🔹 Casos de Uso
Descrevem as interações entre usuários (atores) e o sistema.

- Focam no fluxo de ações
- Representam cenários de uso do sistema

📌 Exemplo:  
*Usuário realiza login informando e-mail e senha e acessa o sistema*

---

### 🔹 Histórias de Usuário
São descrições curtas e simples das funcionalidades, escritas sob a perspectiva do usuário.

- Muito utilizadas em métodos ágeis  
- Foco em valor para o usuário  
- Estrutura comum:  
  **"Como [tipo de usuário], quero [ação] para [benefício]"**

📌 Exemplos:
- *Como usuário, quero realizar login para acessar minha conta*  
- *Como cliente, quero visualizar meus pedidos para acompanhar minhas compras*  
- *Como administrador, quero gerar relatórios para analisar o desempenho do sistema*  

💡 **Dica:**  
Histórias de usuário devem ser claras, curtas e focadas no valor entregue ao usuário.


## Validação e Priorização de Requisitos

Após o levantamento, os requisitos precisam ser **validados** e **priorizados** para garantir que o sistema atenda corretamente às necessidades do projeto.

---

### 🔹 Validação
Consiste em verificar se os requisitos estão corretos, completos e compreensíveis.

- Evita ambiguidades e erros de interpretação  
- Garante alinhamento com os stakeholders  
- Pode envolver revisões, reuniões e protótipos  

---

### 🔹 Priorização
Define a ordem de importância dos requisitos para o desenvolvimento.

- Ajuda a focar no que gera mais valor  
- Considera critérios como urgência, impacto e custo  
- Muito usada em métodos ágeis  

📌 Exemplos de priorização:
- Alta prioridade: funcionalidades essenciais (ex: login)  
- Média prioridade: funcionalidades importantes, mas não críticas  
- Baixa prioridade: melhorias ou funcionalidades adicionais  

---

💡 **Dica:**  
Nem todos os requisitos serão implementados ao mesmo tempo — priorizar bem é essencial para entregar valor rapidamente.


--- 

# 📌 Projeto Integrador — Template de Requisito Funcional

Para organizar e documentar corretamente os requisitos de um sistema, utilizamos um template padrão que ajuda a descrever de forma clara e objetiva cada funcionalidade.

A estrutura abaixo representa um **Requisito Funcional do Sistema (RFS)**.

---

### 🧩 Estrutura do Template

#### 🔹 Identificador (Ex: RFS01)
Cada requisito deve possuir um código único para facilitar sua identificação e rastreabilidade.

- Exemplo: `RFS01`, `RFS02`, `RFS03`

---

#### 🔹 Função
Representa o nome da funcionalidade.

- Deve ser **curto e direto**
- Descreve *o que o sistema faz*

📌 Exemplo: *Realizar login do usuário*

---

#### 🔹 Descrição
Apresenta uma explicação mais detalhada da funcionalidade.

- Deve deixar claro o objetivo do requisito
- Pode incluir regras básicas de funcionamento

📌 Exemplo:  
*Permitir que o usuário acesse o sistema informando e-mail e senha válidos*

---

#### 🔹 Entradas
Define quais dados são necessários para executar a função.

- Informações fornecidas pelo usuário ou por outros sistemas

📌 Exemplos:
- e-mail  
- senha  
- código do produto  

---

#### 🔹 Fonte
Indica de onde vêm as entradas.

- Quem ou o que fornece os dados

📌 Exemplos:
- Usuário  
- Sistema externo  
- API  

---

#### 🔹 Saídas
Descreve os resultados gerados pelo sistema após o processamento.

- Respostas, mensagens ou dados retornados

📌 Exemplos:
- Acesso concedido  
- Mensagem de erro  
- Confirmação de cadastro  

---

#### 🔹 Ação
Explica o que o sistema faz internamente para transformar as entradas em saídas.

- Processamento realizado pelo sistema

📌 Exemplos:
- Validar dados no banco de dados  
- Calcular total da compra  
- Armazenar informações  

---

### ✅ Resumo

| Campo       | Objetivo                         |
|------------|---------------------------------|
| Função     | O que o sistema faz             |
| Descrição  | Explicação da funcionalidade    |
| Entradas   | Dados necessários               |
| Fonte      | Origem dos dados                |
| Saídas     | Resultado gerado                |
| Ação       | Processamento realizado         |

---

💡 **Dica:**  
Um bom requisito deve ser **claro, objetivo e sem ambiguidades**, permitindo que qualquer pessoa da equipe compreenda facilmente o comportamento esperado do sistema.


--- 

## Evolução do Template de Requisitos

O template de requisito funcional pode ser expandido para incorporar práticas modernas de desenvolvimento, como **Histórias de Usuário** e **Priorização**.

Essa adaptação torna o documento mais completo, facilitando o entendimento do valor do requisito e sua importância no projeto.

---

### 🔹 Inclusão de História de Usuário

Adicionar uma história de usuário ao requisito ajuda a contextualizar a funcionalidade sob a perspectiva do usuário.

📌 Estrutura:
**Como [tipo de usuário], quero [ação] para [benefício]**

📌 Exemplo:
*Como cliente, quero realizar login para acessar minha conta*

---

### 🔹 Inclusão de Prioridade

A prioridade indica o nível de importância do requisito no desenvolvimento.

- Ajuda na organização do backlog  
- Define o que deve ser implementado primeiro  

📌 Exemplos:
- Alta  
- Média  
- Baixa  

---

### 🧩 Template Atualizado (Sugestão)

- Identificador (RFS01)  
- Função  
- História de Usuário  
- Descrição  
- Entradas  
- Fonte  
- Saídas  
- Ação  
- Prioridade  

---

💡 **Benefício:**  
Essa estrutura combina organização tradicional com práticas ágeis, tornando os requisitos mais claros, orientados ao usuário e fáceis de priorizar.