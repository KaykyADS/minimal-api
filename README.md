# Minimal API

> Uma API simples construída com .NET 9 para fins de aprendizado e demonstração.

## 📋 Sobre o Projeto

Esta API trata do cadastro de **Administradores** e **Editores**, com controle de acesso baseado em permissões.  
- **Administradores** têm acesso a áreas restritas que **Editores** não possuem.  
- O acesso é gerenciado via autenticação por **tokens JWT**.  

## 🚀 Tecnologias

- **.NET 9**: Framework utilizado para construir a API.
- **C#**: Linguagem de programação principal.
- **xUnit**: Framework de testes utilizado para garantir a qualidade do código.

## 📦 Estrutura do Repositório

```
├── Api/                # Código da API
├── Test/               # Testes automatizados
├── .gitignore          # Arquivos a serem ignorados pelo Git
└── minimal-api.sln     # Solution do Visual Studio
```

## 🛠️ Como Rodar

1. Clone este repositório:

   ```bash
   git clone https://github.com/KaykyADS/minimal-api.git
   cd minimal-api
   ```

2. Restaure as dependências:

   ```bash
   dotnet restore
   ```

3. Execute a API:

   ```bash
   dotnet run --project Api
   ```

   A API estará disponível em `http://localhost:5260/swagger/index.html`.

4. Para rodar os testes:

   ```bash
   dotnet test Test
   ```

## 🧪 Testes

Os testes automatizados estão localizados na pasta `Test/`. Eles utilizam o framework **xUnit** para garantir que a API funcione conforme o esperado.
