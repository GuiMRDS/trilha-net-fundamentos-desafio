# DIO - Trilha .NET - Fundamentos
www.dio.me

# 🚗 Sistema de Estacionamento - C# (.NET)

## 📄 Descrição

Este projeto foi desenvolvido como parte do **Desafio de Projeto da Trilha .NET - Fundamentos** da [Digital Innovation One (DIO)](https://www.dio.me/).

O desafio consiste na construção de um **Sistema de Estacionamento**, que será utilizado para **gerenciar os veículos estacionados e realizar operações essenciais**, como:

- ✅ Cadastrar um veículo;
- ✅ Remover um veículo (calculando o valor total pelo tempo de permanência);
- ✅ Listar os veículos estacionados.

O objetivo é aplicar na prática os conceitos de **Programação Orientada a Objetos (POO)** e os fundamentos da linguagem **C# com .NET**, além de consolidar o uso de versionamento de código com **Git e GitHub**.

---

## 💡 Contexto do Desafio

Você foi contratado para construir um sistema de estacionamento, onde será possível:

- Registrar veículos que entram no estacionamento;
- Remover veículos quando saem, calculando o valor a ser pago com base no tempo;
- Listar todos os veículos presentes no estacionamento.

---

## 🔧 Proposta e Estrutura do Projeto

A classe principal é a **`Estacionamento`**, que possui os seguintes atributos e métodos:

### 🔸 **Atributos:**
- **`precoInicial`** (`decimal`): Valor fixo cobrado no momento da entrada.
- **`precoPorHora`** (`decimal`): Valor cobrado por cada hora de permanência.
- **`veiculos`** (`List<string>`): Lista contendo as placas dos veículos estacionados.

### 🔸 **Métodos:**
- **`AdicionarVeiculo()`**  
  Recebe uma placa informada pelo usuário e adiciona à lista de veículos.

- **`RemoverVeiculo()`**  
  Verifica se o veículo está na lista. Se estiver, solicita a quantidade de horas, calcula o valor total (`precoInicial + precoPorHora * horas`) e remove o veículo da lista.

- **`ListarVeiculos()`**  
  Exibe todos os veículos atualmente estacionados. Caso não haja nenhum, informa que não há veículos estacionados.

---

## 🗺️ Funcionalidades do Menu Interativo

- 🚗 **Cadastrar veículo**
- 🗑️ **Remover veículo**
- 📜 **Listar veículos**
- ❌ **Encerrar programa**

---

## 💻 Tecnologias Utilizadas
- Linguagem: **C#**
- Framework: **.NET 6 ou superior**
- Paradigma: **Programação Orientada a Objetos (POO)**
- Controle de versão: **Git e GitHub**
- IDE recomendada: **Visual Studio / Visual Studio Code**

---
