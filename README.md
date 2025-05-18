# 🧪 Laboratório: Identificação e Refatoração de *Code Smells* em Java

## 🎯 Objetivo

Este laboratório tem como objetivo ajudar você a:

- Reconhecer *code smells* em código Java orientado a objetos.
- Aplicar técnicas de refatoração para melhorar a legibilidade, manutenibilidade e extensibilidade do código.
- Desenvolver boas práticas de design de software.

---

## 📋 Instruções

### 1. **Análise de Código**

Abra o arquivo `OrderProcessor.java` e **analise o código cuidadosamente**.

Identifique pelo menos **5 *code smells*** presentes no código, tais como:

- Métodos longos (*Long Method*)
- Agrupamento de dados primitivos (*Data Clumps*)
- Obsessão por tipos primitivos (*Primitive Obsession*)
- Conhecimento excessivo de detalhes de outros objetos (*Feature Envy*)
- Código duplicado (*Duplicated Code*)

---

### 2. **Refatoração**

Crie uma nova versão do código utilizando técnicas de refatoração apropriadas. Algumas refatorações que podem ser aplicadas:

- `Extract Method`
- `Extract Class`
- `Replace Primitive with Object`
- `Introduce Parameter Object`
- `Move Method`

Busque seguir boas práticas como:

- Clareza e coesão nos métodos
- Reaproveitamento de código
- Encapsulamento de responsabilidades

---

### 3. **Justificativa das Refatorações**

Crie um arquivo `justificativas.md` ou comente no próprio código refatorado, explicando:

- Quais *code smells* você identificou
- Quais refatorações aplicou e por quê
- Quais melhorias obteve com as mudanças

---

## 📚 Recursos

- [Refactoring Guru – Code Smells](https://refactoring.guru/refactoring/smells)
- [Martin Fowler – Refactoring (Livro)]
  - Sabi: https://research.ebsco.com/c/5ovcoe/search/details/3pxaqt6e4j?limiters=None&q=refactoring%20Improving%20the%20Design%20of%20Existing%20Code
  - Minha Biblioteca: https://app.minhabiblioteca.com.br/reader/books/9788577804153

