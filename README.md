# Hola, soy Adrián Joaquín Naum

**Desarrollador C# / .NET** — Argentina

Construyo software de escritorio y APIs. Vengo del lado **Windows** con **Windows Forms** y estoy llevando esa misma base de C#/.NET hacia **Avalonia**, para que la UI de escritorio corra en Windows, Linux y macOS sin reescribir la lógica de negocio.

[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)
[![GitHub](https://img.shields.io/badge/GitHub-adrianbeep-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/adrianbeep)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![.NET](https://img.shields.io/badge/.NET-8.0%20%7C%2010.0-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)
[![C%23](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logoColor=white)](https://learn.microsoft.com/dotnet/csharp/)

---

## Stack

### Desktop

[![Avalonia](https://img.shields.io/badge/Avalonia-7C3AED?style=for-the-badge&logo=avaloniaui&logoColor=white)](https://avaloniaui.net)
[![Windows Forms](https://img.shields.io/badge/Windows%20Forms-0078D4?style=for-the-badge&logo=windows&logoColor=white)](https://learn.microsoft.com/es-es/dotnet/desktop/winforms/)

- **Avalonia** — UI multiplataforma declarativa en XAML con MVVM: `ViewModels` separados de la vista, binding, converters, comandos y `INotifyPropertyChanged`. Es la vía para sacar la interfaz del lock-in de Windows conservando un único core en C#.
- **Windows Forms** — escritorio nativo de Windows (`net10.0-windows` + `UseWindowsForms`): shell principal que embebe los formularios activos en un panel y abre el detalle en diálogos modales propios, `DataGridView` con configuración reutilizable y formato por celda, `UserControl` reutilizable y theming con **ReaLTaiizor**.
- **Acceso a datos** — capa de repositorios con contratos propios y un DAO uniforme, para que la UI no dependa del motor de base de datos y la lógica de negocio quede testeable.

### Backend & API

[![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](https://learn.microsoft.com/es-es/aspnet/core/)
[![EF Core](https://img.shields.io/badge/EF%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](https://learn.microsoft.com/es-es/ef/core/)
[![CQRS](https://img.shields.io/badge/CQRS%20%2B%20MediatR-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](https://github.com/jbogard/MediatR)
[![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)](https://jwt.io)

- **ASP.NET Core** — Minimal APIs, middleware, CORS, health checks y endpoints públicos y de administración.
- **Clean Architecture** — `Api` / `Application` / `Domain` / `Infrastructure`, con un `Result<T>` propio para modelar errores de negocio sin excepciones.
- **CQRS + MediatR** — *commands*, *queries*, handlers, validadores y *pipeline behaviors* para cross-cutting concerns.
- **EF Core + ASP.NET Identity** — code-first con migraciones, roles y autenticación con JWT.

### Datos

[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)](https://mariadb.org/)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://www.sqlite.org/)

- **SQLite** en desarrollo, **MySQL / MariaDB** en producción.

### Tooling

[![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/features/actions)
[![NuGet](https://img.shields.io/badge/NuGet-0033CC?style=for-the-badge&logo=nuget&logoColor=white)](https://www.nuget.org/)
[![xUnit](https://img.shields.io/badge/xUnit-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](https://xunit.net/)
[![NUnit](https://img.shields.io/badge/NUnit-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](https://nunit.org/)

- **Git** · **GitHub Actions** (CI con build + tests y CD con publicación) · **Docker** (build multi-stage y `docker-compose`) · **NuGet** (global tools) · **xUnit / NUnit** con FluentAssertions.
