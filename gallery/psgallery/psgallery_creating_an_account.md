---
ms.date: 2017-06-12
contributor: JKeithB
ms.topic: conceptual
keywords: gallery,powershell,cmdlet,psgallery
title: "Creación de una cuenta de la Galería de PowerShell"
ms.openlocfilehash: e21575320f220c1ba7ecd9bd464a814b3ebf49d9
ms.sourcegitcommit: 75f70c7df01eea5e7a2c16f9a3ab1dd437a1f8fd
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 06/12/2017
---
## <a name="creating-a-powershell-gallery-account"></a>Creación de una cuenta de la Galería de PowerShell

Es necesario establecer una cuenta de la Galería de PowerShell antes de publicar contenido en la galería. Las cuentas de la Galería de PowerShell se deben vincular a una cuenta habilitada para recibir correo electrónico de Azure Active Directory o a una cuenta de correo electrónico de Microsoft (con dominio outlook.com, hotmail.com, etc.).

Para crear una cuenta de la Galería de PowerShell, vaya a https://PowerShellGallery.com y haga clic en "Register" (Registrarse) (ver imagen a continuación). 

![Registro de una cuenta nueva](./images/CreatingAccount-Register.png)

En la página siguiente, para usar una cuenta de Azure Active Directory, seleccione "Work or School Account" (Cuenta profesional o educativa) e inicie sesión con su cuenta. Para usar una cuenta de Microsoft, como una con dominio hotmail.com o outlook.com, elija "Personal Account" (Cuenta personal) e inicie sesión. 

Una vez que inicie sesión, se le solicitará crear un nombre de usuario para la Galería de PowerShell. Revise los Términos de uso y la Directiva de privacidad a las que se proporcionan vínculos, escriba un nombre de usuario y haga clic en Register (Registrarse).

Nota: Este nombre de cuenta no se puede cambiar una vez creado.  
Consulte [Administrar propietarios de elementos](https://msdn.microsoft.com/en-us/powershell/gallery/psgallery/managing-item-owners) para detalles adicionales al respecto.

## <a name="recommended-practices-for-powershell-gallery-accounts"></a>Procedimientos recomendados para cuentas de la Galería de PowerShell

Es importante supervisar activamente la cuenta de correo electrónico que se usa con la cuenta de la Galería de PowerShell.
Toda comunicación con los propietarios de elementos de la Galería de PowerShell se realiza por correo electrónico con la dirección asociada a la cuenta de la Galería de PowerShell.
Si no podemos ponernos en contacto con el propietario de un elemento, es posible que el equipo de operaciones deba eliminar el elemento en ciertas circunstancias.

Las organizaciones que publican en la Galería de PowerShell a menudo crean una cuenta única con ese fin en Outlook.com o en otro dominio de cuenta de Microsoft.
En muchos casos, no se supervisa con regularidad esa cuenta. En ese caso, un procedimiento recomendado es usar el reenvío de Outlook para enviar el correo electrónico a otra cuenta, habitualmente una dentro de la organización, que el propietario del elemento sí supervisará.

Si un elemento tiene asociados varios propietarios, toda comunicación que provenga de la Galería de PowerShell llegará a todos los propietarios.
Consulte [Administrar propietarios de elementos](https://msdn.microsoft.com/en-us/powershell/gallery/psgallery/managing-item-owners) para detalles adicionales sobre cómo agregar propietarios a un elemento. 

