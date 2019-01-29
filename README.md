# Set up .NET Core on Windows

> Get ready for .NET Core and Blazor development on Windows

- [Webpage](https://denisecase.github.io/setup-dotnet/)
- [Source](https://github.com/denisecase/setup-dotnet)

## Recommended Prerequisites

- [Windows Setup for Developers](https://github.com/denisecase/windows-setup)
- [Windows File Management](https://github.com/denisecase/windows-file-management)
- [Set up Windows with Chocolatey (for Web Development)](https://github.com/denisecase/get-setup-with-chocolatey)

## Recommended Tools

- [Visual Studio Dev Essentials](https://visualstudio.microsoft.com/dev-essentials/)

## .NET Installs

To install the following:

- .NET Core 2.2 SDK (dotnetcore-sdk)
- Visual Studio 2017 Community with the following:
- Visual Studio 2017 Azure workload
- Visual Studio 2017 Data storage and processessing workload
- Visual Studio 2017 ASP.NET and web development workload

Open PowerShell as administrator in your documents folder and run the following commands:

```Powershell
choco install dotnetcore-sdk -y
choco install visualstudio2017community -y
choco install visualstudio2017-workload-azure -y
choco install visualstudio2017-workload-data -y
choco install visualstudio2017-workload-netweb -y

```

## Install Visual Studio Extensions

Install from the VS Marketplace:

- [Microsoft Visual Studio Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsls-vs) extension
- [Visual Studio Blazor Language Services](https://marketplace.visualstudio.com/items?itemName=aspnet.blazor) extension

## Install Blazor Templates

Run the following in Powershell:

```Powershell
dotnet new -i Microsoft.AspNetCore.Blazor.Templates
```

## Terms

- .NET Core
- Blazor
- dotnet
- operating system
- Software Development Kit (SDK)

## Next Steps

Configure Git distributed version control system

- See [Git Started With Windows](https://github.com/denisecase/git-started-windows)

## References

- [Blazor Docs](https://blazor.net/docs/get-started.html)
- [Chocolatey Gallery](https://chocolatey.org/packages)
- [Live Share](https://visualstudio.microsoft.com/services/live-share/)
- [Microsoft .NET](https://dotnet.microsoft.com/)

## Videos to Get Started with Visual Studio

- [Getting Started with Visual Studio 2017 – Install and setup your new IDE](https://www.youtube.com/watch?v=R6dZJ-FEypk)
- [Web Development in Visual Studio 2017](https://www.youtube.com/watch?v=gfjFJ-v_h2s)


