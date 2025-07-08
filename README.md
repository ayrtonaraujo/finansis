<div align="center">
  <img src="#" alt="Logo do Finansis" width="200"/>
</div>

# Finansis: Gerenciador Financeiro Pessoal

**Finansis** é um sistema de gerenciamento financeiro pessoal, desenvolvido como Projeto de Conclusão de Curso da **Capacitação Profissional em Desenvolvimento de Sistemas** pela **FPF Escola Tecnológica** (Manaus, AM). A aplicação oferece uma maneira simples e intuitiva para controlar receitas e despesas.

---

## 📜 Sumário

* [Visão Geral](#-visão-geral)
* [Principais Funcionalidades](#-principais-funcionalidades)
* [Tecnologias Utilizadas](#-tecnologias-utilizadas)
* [Prévia do Sistema](#-prévia-do-sistema)
* [Funcionalidades Detalhadas (CRUDs)](#-funcionalidades-detalhadas-cruds)
* [Como Executar o Projeto](#-como-executar-o-projeto)
* [Autores](#-autores)

---

## 🎯 Visão Geral

O projeto **Finansis** foi desenvolvido como Projeto de Conclusão de Curso da **Capacitação Profissional em Desenvolvimento de Sistemas** pela **FPF Escola Tecnológica**, localizada em Manaus, Amazonas.

O objetivo principal da aplicação é fornecer uma ferramenta prática e de fácil utilização para o controle financeiro diário, permitindo que os usuários cadastrem e categorizem suas receitas e despesas para obter uma visão clara de seus hábitos financeiros.

* **Nome do Projeto:** Finansis
* **Instituição:** FPF Escola Tecnológica - Manaus, AM
* **Curso:** Capacitação Profissional em Desenvolvimento de Sistemas
* **Ano de Conclusão:** 2025

---

## ✨ Principais Funcionalidades

* **Gestão de Receitas:** Adicionar, visualizar, editar e excluir ganhos.
* **Gestão de Despesas:** Adicionar, visualizar, editar e excluir gastos.
* **Categorização:** Crie e gerencie categorias personalizadas para organizar as transações.
* **Design Responsivo:** Interface otimizada para diferentes tamanhos de tela, como desktops e celulares.
* **Interface Intuitiva:** Uma interface limpa e focada na experiência do usuário.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando uma arquitetura moderna com backend e frontend desacoplados:

**Backend:**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)

**Frontend:**
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)


**Banco de Dados:**
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

---

## 🖥️ Prévia do Sistema

A seguir, algumas das principais telas da aplicação:

### Página Inicial
*A tela principal que o usuário vê ao acessar o sistema.*
![Tela Inicial](\references\prints\Screenshot 2025-07-08 191332.png)

### Tela de Lançamentos
*Onde o usuário visualiza, cadastra e gerencia suas receitas e despesas.*
![Tela de Lançamentos](\references\prints\Screenshot 2025-07-08 191344.png)

### Tela de Categorias
*Gerenciamento das categorias utilizadas para classificar os lançamentos.*
![Tela de Categorias](\references\prints\Screenshot 2025-07-08 191353.png)

### Design Responsivo (Mobile)
*Visualização do sistema em um dispositivo móvel, demonstrando a adaptabilidade da interface.*
![Design Responsivo (Mobile)](\references\prints\Screenshot 2025-07-08 191808.png)

### Página de Erro 404
*Página amigável para rotas não encontradas.*
![Design Responsivo (Mobile)](\references\prints\Screenshot 2025-07-08 191406.png)

---

## ⚙️ Funcionalidades Detalhadas (CRUDs)

O sistema implementa operações de **CRUD (Create, Read, Update, Delete)** completas para as seguintes entidades:

| Entidade | Create (Criar) | Read (Ler) | Update (Atualizar) | Delete (Excluir) |
| :--- | :---: | :---: | :---: | :---: |
| **Receitas** | ✅ | ✅ | ✅ | ✅ |
| **Despesas** | ✅ | ✅ | ✅ | ✅ |
| **Categorias** | ✅ | ✅ | ✅ | ✅ |

---

## 🚀 Como Executar o Projeto

Para executar este projeto localmente, siga os passos abaixo em dois terminais diferentes: um para o backend e outro para o frontend.

### Pré-requisitos

* [Python 3.8+](https://www.python.org/)
* [Node.js e npm](https://nodejs.org/)
* [Angular CLI](https://angular.io/cli)
* [Git](https://git-scm.com/)

### Backend (Django)

```bash
# Navegue até a pasta do backend
cd DjangoProject

# Crie e ative um ambiente virtual
python -m venv venv
# No Windows: venv\Scripts\activate
# No Linux/Mac: source venv/bin/activate

# Instale as dependências
pip install -r requirements.txt

# Aplique as migrações do banco de dados
python manage.py migrate

# Inicie o servidor de desenvolvimento do backend
python manage.py runserver
# O servidor da API estará rodando em: [http://127.0.0.1:8000](http://127.0.0.1:8000)
```
### Frontend (Angular)

```bash
# Em um novo terminal, navegue até a pasta do frontend
cd finansisAngular

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento do frontend
ng serve
# A aplicação estará acessível no navegador em: http://localhost:4200
```

## 👨‍💻 Autoresome do Autor
	
- Ayton Araújo
- Mathias Teixeira
- Judson Silva