## 📝 Natureza da Atividade

Este projeto é a **Atividade Avaliativa do 3º Bimestre** da disciplina de **Sistemas Web II (SW-II)**. Ele serve como instrumento final de composição de nota e deve ser desenvolvido obrigatoriamente de forma gradual durante as aulas, com a evolução registrada no GitHub em datas específicas.

---

## 🎯 O que o projeto faz?

O projeto consiste na criação de uma **aplicação web full stack para gerenciamento de livros**. Ele conecta a camada de persistência de dados (Banco de Dados) até a camada de apresentação (Interface no Navegador).

### 🛠️ Funcionalidades Principais

* **Cadastrar livros (`POST`):** Insere novos títulos na biblioteca informando título, autor, ano de publicação e disponibilidade.
* **Listar e consultar livros (`GET`):** Exibe a lista completa de livros cadastrados ou consulta um registro específico.
* **Atualizar livros (`PUT`):** Permite alterar dados de livros já existentes (como mudar o status de disponibilidade).
* **Excluir livros (`DELETE`):** Remove um livro do banco de dados.

### 🏗️ Arquitetura do Sistema

1. **Back-End (API RESTful):** Criado com **Python** e **FastAPI**, responsável por receber as requisições HTTP, validar os dados e tratar erros.
2. **Banco de Dados:** **MySQL** (gerenciado via **XAMPP** e **phpMyAdmin**), utilizando o **SQLAlchemy** para mapear e salvar as informações do acervo.
3. **Front-End:** Interface interativa feita com **HTML, CSS e JavaScript**, que utiliza a **Fetch API** para se comunicar com a API e atualizar as informações na tela em tempo real.