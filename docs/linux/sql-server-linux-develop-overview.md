---
title: Develop applications for SQL Server on Linux
description: You can create applications that connect to and use SQL Server on Linux from various programming languages and popular web frameworks.
author: rwestMSFT
ms.author: randolphwest
ms.date: 09/11/2023
ms.service: sql
ms.subservice: linux
ms.topic: conceptual
ms.custom:
  - linux-related-content
---
# How to get started developing applications for SQL Server on Linux

[!INCLUDE [SQL Server - Linux](../includes/applies-to-version/sql-linux.md)]

You can create applications that connect to and use [!INCLUDE [ssnoversion-md](../includes/ssnoversion-md.md)] on Linux from various programming languages, such as C#, Java, Node.js, PHP, Python, Ruby, and C++. You can also use popular web frameworks and Object Relational Mapping (ORM) frameworks.

> [!TIP]  
> These same development options also enable you to target [!INCLUDE [ssnoversion-md](../includes/ssnoversion-md.md)] on other platforms. Applications can target [!INCLUDE [ssnoversion-md](../includes/ssnoversion-md.md)] running on-premises or in the cloud, on Linux, Windows, or Docker on macOS. Or you can target Azure SQL Database and Azure Synapse Analytics.

## Try the tutorials

The best way to get started and build applications with [!INCLUDE [ssnoversion-md](../includes/ssnoversion-md.md)] is to try it out for yourself.

- Browse to [Getting Started guides](../connect/sql-data-developer.md).
- Select your language and development platform.
- Try the code samples.

> [!TIP]  
> If you want to develop for [!INCLUDE [ssnoversion-md](../includes/ssnoversion-md.md)] on Docker, take a look at the **macOS** tutorials.

## Create new applications

If you're creating a new application, refer to the [Connectivity libraries](sql-server-linux-develop-connectivity-libraries.md), for a summary of the connectors and popular frameworks available for various programming languages.

## Use existing applications

If you have an existing database application, you can change its connection string to target [!INCLUDE [ssnoversion-md](../includes/ssnoversion-md.md)] on Linux. Make sure to read about the [Known Issues](sql-server-linux-release-notes-2017.md#known-issues) in [!INCLUDE [ssnoversion-md](../includes/ssnoversion-md.md)] on Linux.

## Use existing SQL tools on Windows with SQL Server on Linux

Tools that currently run on Windows such as SSMS, SSDT, and PowerShell, also work with [!INCLUDE [ssnoversion-md](../includes/ssnoversion-md.md)] on Linux. Although they don't run natively on Linux, you can still manage remote [!INCLUDE [ssnoversion-md](../includes/ssnoversion-md.md)] instances on Linux.

See the following articles for more information:

- [SQL Server Management Studio (SSMS)](sql-server-linux-manage-ssms.md)
- [SQL Server Data Tools (SSDT)](sql-server-linux-develop-use-ssdt.md)
- [SQL PowerShell](sql-server-linux-manage-powershell.md)

> [!NOTE]  
> Make sure that you're using the latest versions of these tools for the best experience.

## Use new SQL tools for Linux

You can use the [mssql extension](https://aka.ms/mssql-marketplace) for [Visual Studio Code](https://code.visualstudio.com) on Linux, macOS, and Windows. For a step-by-step walkthrough, see the following tutorial:

- [Use Visual Studio Code](../tools/visual-studio-code/sql-server-develop-use-vscode.md)

You can also use command-line tools that are native for Linux. These tools include the following:

- [sqlcmd](../tools/sqlcmd/sqlcmd-utility.md)
- [bcp](sql-server-linux-migrate-bcp.md)
- [mssql-conf](sql-server-linux-configure-mssql-conf.md)

## Related content

- [Install on Red Hat Enterprise Linux](quickstart-install-connect-red-hat.md)
- [Install on SUSE Linux Enterprise Server](quickstart-install-connect-suse.md)
- [Install on Ubuntu](quickstart-install-connect-ubuntu.md)
- [Run on Docker](quickstart-install-connect-ubuntu.md)
