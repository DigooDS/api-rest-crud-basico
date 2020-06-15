<h1 align="center">
  API REST - CRUD básico
</h1>

<h3 align="center">
CRUD básico para cadastro de Fornecedores
</h3>

<h1>
  <img src="public/paraReadme_01.gif">
</h1>

---

## 🔖   Sobre

API REST desenvolvida para estudo de uma CRUD básica utilizando o **Entity Framework Core**, onde é possível realizar cadastros de fornecedores com as seguintes informações:

- **ID** (Gerado através do GUID);
- **Nome**;
- **Documento** (podendo ser CPF ou CNPF);
- **Tipo de Fornecedor** (Ex: 1 para pessoa física e 2 para pessoa jurídica);
- **Ativo?** (Se o fornecedor está ativo ou não);

---

## 🚀   Tecnologia utilizada

- [ASP.NET Core](https://dotnet.microsoft.com/)

---

## ⚙   Para clonar o projeto

```bash
  # clonar o projeto
  $ git clone https://github.com/DigooDS/api-rest-crud-basico.git

  # acessar a pasta do projeto
  $ cd api-rest-crud-basico
```
---

## 💿   Para executar o backend

- Caso utilize o Visual Studio é só clicar no botão **"Play" (irá executar no IIS Express)**;

- Caso utilize outras IDEs, como o VS Code, é só executar o comando abaixo:

```bash
  $ dotnet run   # Quando abrir o browser no localhost e sua respectiva porta, acrescete: "/api/fornecedores"
```

---

## 📌 Importante

<h1>
  <img src="public/paraReadme_02.jpg" width= 300px>
</h1>

Para cadastrar os IDs dos fornecedores, utilize o **Create GUID** do Microsoft Visual Studio (Tools -> Create GUID).

Para realizar todos os CRUDs, utilizar uma plataforma de desenvolvimento de API como o Postman, Insomnia etc. Segue links dos respectivos abaixo:

Postman: (https://www.postman.com/)

Insomnia: (https://insomnia.rest/)

---
<i>Desenvolvido por RodrigoDS</i> 🤓
