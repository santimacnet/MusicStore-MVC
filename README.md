MUSIC STORE MATERIAL PARA FORMACION ASP.NET MVC3

Este repositorio contiene la solucion original Microsoft que sirve como guia de ejemplo y aprendizaje.

MVC Music Store tutorial for ASP.NET MVC 3 

The code for this project is available under the Microsoft Public License (Ms-PL). 
The tutorial document is licensed under Creative Commons Attribution 3.0 License.

The following items are included in this tutorial:
1. MVC Music Store - Tutorial - v3.0.pdf
This is the tutorial document which will guide you through building the MVC Music Store application from start to finish.

2. MvcMusicStore-Assets
This folder contains the assets you will need to build the application, including images, CSS, database files, etc.

3. MvcMusicStore-Completed
This folder contains the source for the completed application, after you have completed the entire tutorial. You can refer to it if your application isn't working.

For more information, see the included tutorial document PDF.


NOTAS
--------------------------------------------------------------------------------
Para realizar el tutorial se ha migrado la solucion a Visual Studio 2017

La solucion original estaba con Visual Studio 2010, se han tenido que realizar ajustes en los paquetes de MVC.

Dentro de VS2017 en Consola Nuget se ha realizado el siguiente comando:

PM> Install-Package Microsoft.AspNet.Mvc -Version 3.0.50813.1

Despues del comando Nuget se pueden ver los cambios en web.config

  <runtime>
    <assemblyBinding xmlns="urn:schemas-microsoft-com:asm.v1">
      <dependentAssembly>
        <assemblyIdentity name="System.Web.Mvc" publicKeyToken="31bf3856ad364e35"/>
        <bindingRedirect oldVersion="3.0.0.0-3.0.0.1" newVersion="3.0.0.1"/>
      </dependentAssembly>
    </assemblyBinding>
  </runtime>

