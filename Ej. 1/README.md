# Reporte EJERCICIO1

Este ejercicio trata sobre un error de compilación en el código fuente de un servicio web que tiene como
objetivo proporcionar una respuesta simple al invocar un método llamado "HelloWorld()".

El error se encuentra en la línea 30 del archivo "EJERCICIO1.asmx" y su mensaje de error específico indica
que la cadena de texto "Hola a todos" está siendo usada como una expresión independiente, lo que está
generando un error.

El framework utilizado es .NET FRAMEWORK.

La versión es: Versión de Microsoft .NET Framework:4.0.30319; Versión ASP.NET:4.8.4654.0
El error en código fuente es

![imagen1.png](assets%2Fimg%2Fimagen1.png)

***El error en compilador tiene como código: CS0201 que tiene como descripción: Only assignment, call,
increment, decrement, await, and new object expressions can be used as a statement**
Y el resultado del compilador detallados:
C:\Program Files\IIS Express> "C:\Windows\Microsoft.NET\Framework64\v4.0.30319\csc.exe" /t:library /utf8output /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System.Drawing\v4.0_4.0.0.0__b03f5f7f11d50a3a\System.Drawing.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System.Xml.Linq\v4.0_4.0.0.0__b77a5c561934e089\System.Xml.Linq.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System\v4.0_4.0.0.0__b77a5c561934e089\System.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System.Xml\v4.0_4.0.0.0__b77a5c561934e089\System.Xml.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System.ServiceModel.Activation\v4.0_4.0.0.0__31bf3856ad364e35\System.ServiceModel.Activation.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System.Configuration\v4.0_4.0.0.0__b03f5f7f11d50a3a\System.Configuration.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\Microsoft.VisualStudio.Web.PageInspector.Loader\v4.0_1.0.0.0__b03f5f7f11d50a3a\Microsoft.VisualStudio.Web.PageInspector.Loader.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System.Core\v4.0_4.0.0.0__b77a5c561934e089\System.Core.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\Microsoft.CSharp\v4.0_4.0.0.0__b03f5f7f11d50a3a\Microsoft.CSharp.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_64\System.Web\v4.0_4.0.0.0__b03f5f7f11d50a3a\System.Web.dll" /R:"C:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscorlib.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System.Web.DynamicData\v4.0_4.0.0.0__31bf3856ad364e35\System.Web.DynamicData.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System.ServiceModel\v4.0_4.0.0.0__b77a5c561934e089\System.ServiceModel.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System.IdentityModel\v4.0_4.0.0.0__b77a5c561934e089\System.IdentityModel.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_64\System.Data\v4.0_4.0.0.0__b77a5c561934e089\System.Data.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System.Web.ApplicationServices\v4.0_4.0.0.0__31bf3856ad364e35\System.Web.ApplicationServices.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System.Activities\v4.0_4.0.0.0__31bf3856ad364e35\System.Activities.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System.Web.Extensions\v4.0_4.0.0.0__31bf3856ad364e35\System.Web.Extensions.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System.Data.DataSetExtensions\v4.0_4.0.0.0__b77a5c561934e089\System.Data.DataSetExtensions.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System.ServiceModel.Activities\v4.0_4.0.0.0__31bf3856ad364e35\System.ServiceModel.Activities.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System.ServiceModel.Web\v4.0_4.0.0.0__31bf3856ad364e35\System.ServiceModel.Web.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_64\System.EnterpriseServices\v4.0_4.0.0.0__b03f5f7f11d50a3a\System.EnterpriseServices.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System.WorkflowServices\v4.0_4.0.0.0__31bf3856ad364e35\System.WorkflowServices.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System.Runtime.Serialization\v4.0_4.0.0.0__b77a5c561934e089\System.Runtime.Serialization.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System.ComponentModel.DataAnnotations\v4.0_4.0.0.0__31bf3856ad364e35\System.ComponentModel.DataAnnotations.dll" /R:"C:\windows\Microsoft.Net\assembly\GAC_MSIL\System.Web.Services\v4.0_4.0.0.0__b03f5f7f11d50a3a\System.Web.Services.dll" /out:"C:\Users\Rafael\AppData\Local\Temp\Temporary ASP.NET Files\vs\0d8209fc\23b238e9\App_Web_ejercicio1.asmx.cdcab7d2.rwgp5cow.dll" /debug- /optimize+ /w:4 /nowarn:1659;1699;1701;612;618 /warnaserror-  "C:\Users\Rafael\AppData\Local\Temp\Temporary ASP.NET Files\vs\0d8209fc\23b238e9\App_Web_ejercicio1.asmx.cdcab7d2.rwgp5cow.0.cs" "C:\Users\Rafael\AppData\Local\Temp\Temporary ASP.NET Files\vs\0d8209fc\23b238e9\App_Web_ejercicio1.asmx.cdcab7d2.rwgp5cow.1.cs"


Microsoft (R) Visual C# Compiler version 4.8.9037.0

for C# 5
Copyright (C) Microsoft Corporation. All rights reserved.



This compiler is provided as part of the Microsoft (R) .NET Framework, but only supports language versions up to C# 5, which is no longer the latest version. For compilers that support newer versions of the C# programming language, see http://go.microsoft.com/fwlink/?LinkID=533240

c:\Users\Rafael\Downloads\EJERCICIO1.asmx(30,9): error CS0201: Only assignment, call, increment, decrement, await, and new object expressions can be used as a statement

Una recomendación para solucionarlo, es necesario agregar "return" a la cadena de texto "Hola a todos"
para que pueda ser utilizada como valor de retorno para el método "HelloWorld()". De esta manera, la
cadena cumplirá con los requisitos de sintaxis del lenguaje y estará en un contexto en el que tiene un
propósito específico.

![imagen2.png](assets%2Fimg%2Fimagen2.png)

***Asi se vería con la correción***

![imagen3.png](assets%2Fimg%2Fimagen3.png)

