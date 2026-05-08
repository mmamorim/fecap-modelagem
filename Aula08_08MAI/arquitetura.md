<img src="../banner.svg" width="100%">

# Aula 8 - 08/05/2026

# Arquitetura de Sistemas

# O que é Arquitetura de Sistemas?

Arquitetura de sistemas representa a forma como um software é organizado.

Ela define:

- como as partes do sistema se comunicam;
- como os componentes são separados;
- como o sistema é estruturado.

---


# Pensando de Forma Simples

A arquitetura funciona como a planta de uma casa.

Antes de construir, precisamos planejar:

- divisão dos espaços;
- responsabilidades;
- conexões;
- organização geral.

No software acontece algo parecido.

---

# Componentes de um Sistema

Um sistema normalmente possui diferentes partes trabalhando juntas.

Exemplo:

- interface do usuário;
- regras de negócio;
- banco de dados;
- serviços externos.

---

# Exemplo Simples

## Sistema de Loja Virtual

~~~text
Usuário
   ↓
Interface do Sistema
   ↓
Regras de Negócio
   ↓
Banco de Dados
~~~

---

# Interface do Usuário

É a parte visual do sistema.

Exemplos:

- páginas web;
- aplicativos mobile;
- telas do sistema.

Responsável pela interação com o usuário.

---

# Regras de Negócio

Contêm a lógica principal do sistema.

Exemplos:

- calcular desconto;
- validar login;
- processar pagamento;
- verificar estoque.

---

# Banco de Dados

Responsável pelo armazenamento das informações.

Exemplos:

- usuários;
- produtos;
- pedidos;
- mensagens.

---

# Separação de Responsabilidades

Uma boa arquitetura tenta separar responsabilidades.

Isso facilita:

- manutenção;
- organização;
- evolução do sistema;
- trabalho em equipe.

---

# Arquitetura em Camadas

Um modelo muito comum é a arquitetura em camadas.

---

# Exemplo

~~~text
+-------------------+
| Interface         |
+-------------------+
| Regras de Negócio |
+-------------------+
| Banco de Dados    |
+-------------------+
~~~

Cada camada possui uma responsabilidade específica.

<img src="./arquitetura.png" width="10%">

---

<img src="./teste.svg" width="100%">

# Front-end e Back-end

## Front-end

Parte visual do sistema.

Tecnologias comuns:

- HTML;
- CSS;
- JavaScript;
- Vue;
- React.

---

## Back-end

Parte responsável pelas regras e processamento.

Tecnologias comuns:

- Node.js;
- Java;
- Python;
- PHP.

---

# APIs

Muitos sistemas modernos utilizam APIs.

API é uma forma de comunicação entre sistemas.

Exemplo:

~~~text
Aplicativo → API → Banco de Dados
~~~

---

# Exemplo do Cotidiano

## Aplicativo de Delivery

### Front-end

- tela do aplicativo;
- lista de restaurantes;
- carrinho.

### Back-end

- processa pedidos;
- calcula entrega;
- autentica usuários.

### Banco de Dados

- salva pedidos;
- salva usuários;
- salva produtos.

---

# Importância da Arquitetura

Uma boa arquitetura ajuda a:

- reduzir problemas;
- melhorar organização;
- facilitar manutenção;
- permitir crescimento do sistema;
- melhorar reutilização de código.

---

# Erros Comuns

## Misturar responsabilidades

Exemplo:

- interface acessando diretamente banco de dados;
- regras espalhadas pelo sistema.

---

## Falta de organização

Pode gerar:

- código difícil de manter;
- dificuldade para evoluir;
- aumento de erros.

---

# Resumo

- Arquitetura define a organização do sistema;
- Sistemas possuem diferentes componentes;
- Cada parte possui responsabilidades específicas;
- Arquiteturas ajudam na manutenção e evolução do software;
- Arquitetura em camadas é uma abordagem muito utilizada.

---

# Exercício

Escolha um sistema do cotidiano e tente identificar:

- interface;
- regras de negócio;
- armazenamento de dados;
- possíveis APIs utilizadas.

Exemplos:

- Netflix;
- WhatsApp;
- Spotify;
- iFood;
- Aplicativo Bancário.
