# 📋 ProjetoCadastros

> Sistema web responsivo para gerenciamento e cadastro de produtos, clientes, fornecedores e colaboradores, desenvolvido em HTML, CSS e JavaScript puro (Vanilla JS).

---

## 📌 Sobre o Projeto

O **ProjetoCadastros** foi desenvolvido com o objetivo de centralizar e organizar os fluxos de cadastros essenciais para a gestão empresarial de pequenos e médios negócios. A aplicação oferece uma interface limpa, intuitiva e totalmente responsiva, garantindo usabilidade tanto em computadores quanto em dispositivos móveis.

O projeto adota uma arquitetura modular baseada em **Vanilla Web Technologies**, sem a necessidade de *frameworks* externos ou *bundlers*, facilitando a manutenção, velocidade de carregamento e aprendizado da estrutura do código.

---

## 🚀 Funcionalidades

- [x] **Menu Principal / Dashboard (`index.html`)**: Central de navegação acessível e intuitiva.
- [x] **Cadastro de Produtos (`pages/produtos.html`)**: Registro de itens, controle de preço, categoria, código de barras e estoque inicial.
- [x] **Cadastro de Clientes (`pages/clientes.html`)**: Registro completo de pessoa física/jurídica, contatos e endereço.
- [x] **Cadastro de Fornecedores (`pages/fornecedores.html`)**: Gestão de parceiros comerciais, CNPJ, Inscrição Estadual e dados bancários.
- [x] **Cadastro de Colaboradores (`pages/colaboradores.html`)**: Registro de equipe, cargos, salários e dados de admissão.
- [x] **Estilização Reutilizável**: Sistema de CSS modular com `global.css` e `form.css` padronizando formulários e temas.
- [x] **Validação no Front-end**: Validações interativas via JavaScript para preenchimento correto de dados.

---

## 📁 Arquitetura e Estrutura de Pastas

```text
ProjetoCadastros/
├── index.html              # Tela principal (Menu / Dashboard)
├── pages/                  # Módulos de cadastro
│   ├── produtos.html       # Form de Cadastro de Produtos
│   ├── clientes.html       # Form de Cadastro de Clientes
│   ├── fornecedores.html   # Form de Cadastro de Fornecedores
│   └── colaboradores.html  # Form de Cadastro de Colaboradores
├── css/                    # Estilos visuais
│   ├── global.css          # Estilos gerais, reset, menu e variáveis
│   └── form.css            # Componentização visual de formulários
├── js/                     # Lógica e comportamento
│   ├── main.js             # Scripts globais (navegação, menu)
│   ├── produtos.js         # Lógica e validação de Produtos
│   ├── clientes.js         # Lógica e validação de Clientes
│   ├── fornecedores.js     # Lógica e validação de Fornecedores
│   └── colaboradores.js   # Lógica e validação de Colaboradores
└── README.md               # Documentação do repositório
