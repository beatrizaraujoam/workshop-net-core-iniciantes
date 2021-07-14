# Workshop - ASP.NET CORE para Iniciantes

Realizado pelo canal da @glaucia86 



## ☕ Canal  da Glaucia disponivel no link abaixo: 

https://www.youtube.com/watch?v=njlmcXxSHE4 


## Recursos Utilizados: :computer:

Se faz necessário realizar a instalação das aplicações/frameworks abaixo:

* Visual Studio Code

    - **[Visual Studio Code](https://code.visualstudio.com/?WT.mc_id=javascript-0000-gllemos)**
    - **[.NET Core SDK](https://www.microsoft.com/net/download?WT.mc_id=javascript-0000-gllemos)**

* Visual Studio

    - **[Visual Studio](https://visualstudio.microsoft.com/downloads/?WT.mc_id=javascript-0000-gllemos)**
    - **[.NET Core 2.x](https://dotnet.microsoft.com/download?WT.mc_id=javascript-0000-gllemos)**

Caso resolva usar o Visual Studio como IDE, durante a sua instalação procure instalar os seguintes itens:
    -  ASP.NET & Web Development;
    - .NET Core Cross-Platform Development;

* Cadastrar uma Conta no Azure:

    - **[Portal Azure](https://azure.microsoft.com/?WT.mc_id=javascript-0000-gllemos)**
    
* Baixar o Git:
    
    - **[Git](https://git-scm.com/downloads)**

## O que vou aprender?! :blue_book:

Nesse workshop você será capaz de desenvolver a sua primeira aplicação Web em .NET Core 2.x Razor Pages.
A aplicação constitui num CRUD (Create, Read, Update e Delete).

## Ementa do Workshop: :pencil2:

- Parte 1: Criando Razor Pages usando o dotnet CLI & VS Code;
- Parte 2: Adicionando um modelo para a aplicaçao ASP.NET Core Razor Pages;
- Parte 3: Atualizando e gerando páginas;
- Parte 4: Adicionando busca para a aplicação Razor Pages;
- Parte 5: Build & Deploy da Aplicação no Azure App Service;



## Executando o Projeto Localmente :fire:

Caso queira executar o projeto de maneira local, basta executar os comandos abaixo:

```
> dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design
> dotnet add package Microsoft.EntityFrameworkCore.Sqlite
> dotnet restore
> dotnet ef migrations add InitialCreate
> dotnet ef database update
```

Feito isso irá criar a base de dados para que possa ser testada na hora de executar a aplicação ao dar: **dotnet run** na raiz do projeto.

