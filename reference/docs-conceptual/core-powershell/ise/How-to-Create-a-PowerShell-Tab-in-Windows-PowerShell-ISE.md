---
ms.date: 2017-06-05
keywords: powershell,cmdlet
title: "Cómo crear una pestaña de PowerShell en Windows PowerShell ISE"
ms.assetid: c10c18c7-9ece-4fd0-83dc-a19c53d4fd83
ms.openlocfilehash: 3cfeb18babe6b63f0e02da8cf0fd460950f1afce
ms.sourcegitcommit: d6ab9ab5909ed59cce4ce30e29457e0e75c7ac12
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 09/08/2017
---
# <a name="how-to-create-a-powershell-tab-in-windows-powershell-ise"></a>Cómo crear una pestaña de PowerShell en Windows PowerShell ISE
Las pestañas del Entorno de scripting integrado de Windows PowerShell permiten crear y usar varios entornos de ejecución simultáneamente dentro de la misma aplicación.
Cada pestaña de PowerShell corresponde a una sesión o un entorno de ejecución independiente.

> **NOTA**:
>
> Las variables, las funciones y los alias que se crean en una pestaña no se mantienen en otra. Son sesiones diferentes de Windows PowerShell.

Use los pasos siguientes para abrir o cerrar una pestaña en Windows PowerShell.
Para cambiar el nombre de una pestaña, configure la propiedad [DisplayName](The-PowerShellTab-Object.md#displayname) del objeto de scripting Tab de Windows PowerShell.

## <a name="to-create-and-use-a-new-powershell-tab"></a>Para crear y usar una nueva pestaña de PowerShell

En el menú **Archivo**, haga clic en **Nueva pestaña de PowerShell**. La nueva pestaña de PowerShell se abre siempre como la ventana activa.
Las pestañas de PowerShell se numeran de forma incremental en el orden en que se abren.
Cada pestaña está asociada a su propia ventana de la consola de Windows PowerShell.
Puede tener hasta 32 pestañas de PowerShell con su propia sesión abierta a la vez (este valor se limita a 8 en Windows PowerShell ISE 2.0).

Tenga en cuenta que al hacer clic en los iconos **Nuevo** o **Abrir** de la barra de herramientas no se crea una nueva pestaña con una sesión independiente.
En su lugar, estos botones abren un archivo de script nuevo o existente en la pestaña activa con una sesión.
Puede tener varios archivos de script abiertos con cada pestaña y cada sesión.
Las pestañas de script de una sesión solo aparecen debajo de las pestañas de la sesión cuando la sesión asociada está activa.

Para activar una pestaña de PowerShell, haga clic en ella. Para seleccionar entre las pestañas de PowerShell abiertas, en el menú **Ver**, haga clic en la pestaña de PowerShell que quiera usar.

## <a name="to-create-and-use-a-new-remote-powershell-tab"></a>Para crear y usar una pestaña de PowerShell remoto

En el menú **Archivo**, haga clic en **Nueva pestaña de PowerShell en remoto** para establecer una sesión en un equipo remoto.
Aparece un cuadro de diálogo que le pide que escriba los detalles necesarios para establecer la conexión remota.
La pestaña remota funciona igual que una pestaña de PowerShell local, pero los comandos y los scripts se ejecutan en el equipo remoto.

## <a name="to-close-a-powershell-tab"></a>Para cerrar la pestaña de PowerShell

Para cerrar una pestaña, puede usar cualquiera de las técnicas siguientes:

- Haga clic en la pestaña que quiera cerrar.

- En el menú **Archivo**, haga clic en **Cerrar pestaña de PowerShell**, o bien haga clic en el botón Cerrar (**X**) en una pestaña activa para cerrarla.

Si tiene archivos sin guardar abiertos en la pestaña de PowerShell que está cerrando, se le pedirá que los guarde o los descarte.
Para obtener más información acerca de cómo guardar un script, consulte [Cómo guardar un script](How-to-Write-and-Run-Scripts-in-the-Windows-PowerShell-ISE.md#how-to-save-a-script).

## <a name="see-also"></a>Véase también

- [Usar Windows PowerShell ISE](Using-the-Windows-PowerShell-ISE.md)
- [Cómo usar el panel de consola en Windows PowerShell ISE](How-to-Use-the-Console-Pane-in-the-Windows-PowerShell-ISE.md)

