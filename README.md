# Sistema CRUD de Empréstimos de Livros

Um simples sistema CRUD para gerenciar empréstimos de livros, desenvolvido com ASP.NET Core.

## Tecnologias
* **Frontend:** HTML, CSS, Bootstrap
* **Backend:** C#, ASP.NET Core
* **Banco de Dados:** SQL Server
* **IDE:** JetBrains Rider

## Como Executar
1. **Pré-requisitos:**
    * Instalar o .NET SDK 6.0 ou superior
    * Instalar o SQL Server e criar um banco de dados chamado "Emprestimos"
2. **Clonando o Repositório:**
    ```bash
    git clone [URL inválido removido]
    ```
3. **Restaurando as Dependências:**
    ```bash
    cd emprestimos-livros
    dotnet restore
    ```
4. **Executando o Projeto:**
    ```bash
    dotnet run
    ```
5. **Criando o Banco de Dados:**
    * Abra o arquivo `Migrations/EmprestimosContextModelSnapshot.cs` para verificar o schema do banco de dados.
    * Execute as migrations usando o Entity Framework Core.

## Estrutura do Projeto
* **Controllers:** Contém a lógica dos controladores MVC.
* **Models:** Define os modelos de dados.
* **Views:** Contém as views Razor.
* **Data:** Contem o contexto do Entity Framework.

## Contribuições
Contribuições são bem-vindas! Para contribuir, por favor, fork este repositório, faça suas alterações e abra um pull request.

<br>
<br>

### Feito com muito carinho
Atenciosamente, Gabriel Mitsuru 💗
