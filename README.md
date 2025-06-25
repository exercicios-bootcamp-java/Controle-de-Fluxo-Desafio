# 📊 Contador Java com Exceção Personalizada

Este é um projeto simples em Java que simula uma **contagem entre dois números**, com **validação de parâmetros** usando uma **exceção personalizada** (`ParametrosInvalidosException`).  
Ideal para quem está aprendendo sobre estruturas de controle, métodos e tratamento de erros em Java! 💻☕

---

## 🚀 Como funciona?

O programa pede para o usuário digitar dois números:

- **Parâmetro 1**: número inicial
- **Parâmetro 2**: número final

Ele então **imprime uma contagem do número 1 até a diferença entre os dois números** (ex: `parametroDois - parametroUm`).  
Mas se o primeiro número for **maior que o segundo**, o programa **lança uma exceção personalizada** com uma mensagem de erro amigável. 🤝

---

## 📂 Estrutura do Projeto

```bash
📁 contador-java
├── Contador.java
└── ParametrosInvalidosException.java
