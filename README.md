# 🎵 Discos de Vinil

Sistema web para gerenciamento de acervo, estoque e vendas de uma loja de discos de vinil.

Projeto desenvolvido para o **Simulado SAEP – Técnico em Desenvolvimento de Sistemas**.

## ✨ Funcionalidades

- 🔐 Login com e-mail e senha.
- 💿 Cadastro, listagem, busca, edição e exclusão de discos.
- 📦 Controle de entrada e saída de estoque.
- ⚠️ Alertas de estoque abaixo do mínimo.
- 👤 Registro do usuário responsável pelas movimentações.

## 🛠️ Tecnologias

- **Front-end:** HTML, CSS e JavaScript.
- **Back-end:** Node.js e Express.
- **Banco de dados:** MySQL.

## 📁 Estrutura do projeto

```text
prepara_saep/
├── docs/
├── api/
├── web/
└── README.md
```

## ⚙️ Como executar

1. Clone o repositório:

```bash
git clone https://github.com/<seu-usuario>/preparar_saep.git
```

2. Entre na pasta do projeto:

```bash
cd prepara_saep
```

3. Execute o arquivo `database/script.sql` no MySQL.

4. Instale as dependências do back-end:

```bash
cd backend
npm install
```

5. Inicie o sistema:

```bash
npm start
```

6. Acesse `http://localhost:3000` no navegador.

## 🧪 Testes

Foram considerados os seguintes testes:

- Login com dados válidos e inválidos.
- Cadastro, edição e exclusão de discos.
- Busca de discos.
- Entrada e saída de estoque.
- Bloqueio de vendas acima da quantidade disponível.
- Alertas de estoque mínimo.



## 📋 Documentação

A pasta `docs/` contém os requisitos do sistema, o diagrama de entidade-relacionamento (DER), os casos de teste e os requisitos de infraestrutura.

## 👥 Autoras 

Heloá e Lívia Guarizo

---

Desenvolvido para o Simulado SAEP – Técnico em Desenvolvimento de Sistemas.
