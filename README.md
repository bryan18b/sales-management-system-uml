# 📊 Sales Management System – UML

Este projeto foi desenvolvido com o objetivo de modelar e implementar a base de um sistema de gestão comercial completo. A proposta apresenta de forma clara como as classes se organizam e se relacionam dentro do contexto de vendas, envolvendo unidades da empresa, colaboradores e clientes.

## 🖼️ Diagrama de Classes
A estrutura geral do sistema destaca as conexões entre os elementos, focando na lógica de negócio e na integridade dos dados:

![Diagrama de Classes](./docs/diagrama_classes.png)

## 🛠️ Sobre a Modelagem
O diagrama foi elaborado levando em conta pontos essenciais da gestão corporativa moderna:
* **Gestão de Unidades:** Inclui o cadastro da matriz, informações de endereço e controle de faturamento centralizado através do atributo `renda`.
* **Recursos Humanos:** Contempla o gerenciamento de funcionários, incluindo níveis hierárquicos e relações de supervisão através da auto-associação `supervisiona`.
* **Processo de Vendas:** Registra as transações realizadas, relacionando automaticamente o vendedor responsável ao cliente final através da classe `venda`.
* **CRM Simplificado:** Permite o cadastro de clientes e a consulta rápida do histórico de compras através do método `consultarhistoricodevendas()`.

## 💻 Implementação Técnica
A estrutura foi definida com base nos conceitos de **Orientação a Objetos (POO)**. O projeto evoluiu de um diagrama estático para um protótipo funcional (MVP):
* **Backend:** Desenvolvido em **Python (Flask)**, simulando a lógica de negócios e a gestão de dados.
* **Frontend:** Interface responsiva e moderna em **HTML5/CSS3**.
* **Lógica de Interface:** Utilização de **JavaScript (ES6+)** para manipulação dinâmica do DOM e comunicação assíncrona com a API (Fetch API).

## 📂 Estrutura de Pastas
```text
comercio_sistema/
├── backend/          # Servidor Python e Lógica da API
├── frontend/         # Interface Web e Integração JS
├── docs/             # Diagrama UML e Documentação
└── README.md         # Documentação Principal
