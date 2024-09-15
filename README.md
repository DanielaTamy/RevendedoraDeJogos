# 🎮 **Projeto de Banco de Dados - Revendedora de Jogos** 📊
setembro/2023
Arquitetura de Banco de dados - 2° semestre Ciência da computação PUCPR

Este projeto em grupo abrange a criação de um banco de dados completo, desde o modelo conceitual até a implementação da aplicação em Python usando MySQL Workbench.

**Estudantes:**  
Bruno Nardoni
Daniel Lima
Daniela Yuki  
Isabela Conceição

## 📋 **Objetivo**

O objetivo deste projeto é criar uma solução de banco de dados desde o início, abrangendo todas as etapas do desenvolvimento, incluindo:
- **Requisitos de Dados**
- **Modelo Conceitual**
- **Modelo Lógico**
- **Modelo Físico**
- **Implementação da Aplicação**

## 🛠️ **Tecnologias Utilizadas**

- **Banco de Dados:** MySQL Workbench
- **Linguagem de Programação:** Python

## 🗂️ **Estrutura do Projeto**

### 1. **Requisitos de Dados**

- **Jogos:** Nome, categoria, preço, desenvolvedor, data de lançamento
- **Clientes:** Nome, e-mail, telefone, endereço
- **Vendas:** ID do cliente, ID do jogo, data da venda, quantidade, valor total
- **Funcionários:** Nome, e-mail, cargo, telefone

### 2. **Modelo Conceitual**

O modelo conceitual define as entidades principais e seus relacionamentos. Inclui:
- **Entidades:** Jogos, Clientes, Vendas, Funcionários
- **Relacionamentos:** 
  - Um cliente pode realizar várias vendas.
  - Uma venda pode incluir vários jogos.
  - Cada jogo pode ser vendido várias vezes.

### 3. **Modelo Lógico**

O modelo lógico detalha a estrutura das tabelas e relacionamentos, incluindo:
- **Tabelas:** Jogos, Clientes, Vendas, Funcionários
- **Chaves Primárias e Estrangeiras:** Definidas para manter a integridade referencial entre as tabelas.

### 4. **Modelo Físico**

O modelo físico especifica a implementação real do banco de dados, incluindo:
- **Definição das Tabelas:** Estrutura, tipos de dados e índices
- **Relacionamentos:** Definidos através de chaves estrangeiras

### 5. **Implementação da Aplicação**

A aplicação em Python interage com o banco de dados para realizar operações como:
- **Cadastro de Jogos e Clientes**
- **Registro de Vendas**
- **Consulta de Relatórios de Vendas**

