1. using a mvc template: 
    dotnet new mvc
2. add .gitignore file:
    search gitignore.io
    search keywords:
        language: csharp
        engine：dotnetcore
        framework：aspnetcore

==============================Good to know==============================
ASP.NET Core 是一种服务器端框架，用于构建 Web 应用程序，而 React 和 Vite 是客户端框架和构建工具，用于构建前端部分的 Web 应用程序。它们属于不同的层次和职责。

-- ASP.NET Core: 用于构建服务器端应用程序，负责处理请求、执行业务逻辑、与数据库交互等。它提供了一种框架，可以用 C# 编写服务器端代码，并生成用于构建 Web API 或 MVC 应用程序的后端逻辑。

-- React: 是一个 JavaScript 库，用于构建用户界面。它通常用于创建单页应用程序（SPA），其中大部分的用户界面逻辑都在客户端执行。React 可以与后端框架（如 ASP.NET Core）结合使用，通过 API 进行数据交互。

-- Vite: 是一个现代化的前端构建工具，用于快速构建现代 Web 应用程序。Vite 支持 Vue、React、和其他前端框架，它使用现代的构建技术，如 ES Module（ESM）和原生 ES Build，以提供快速的开发和构建体验。

-- 综上所述，ASP.NET Core 主要用于构建服务器端应用程序，而 React 和 Vite 主要用于构建客户端的用户界面。在实际应用中，你可能会将它们结合使用，使用 ASP.NET Core 提供后端服务，同时使用 React 或其他前端框架来构建富客户端应用程序。