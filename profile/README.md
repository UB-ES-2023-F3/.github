<p style="color: red; font-weight: bold">>>>>>  gd2md-html alert:  ERRORs: 0; WARNINGs: 0; ALERTS: 1.</p>
<ul style="color: red; font-weight: bold"><li>See top comment block for details on ERRORs and WARNINGs. <li>In the converted Markdown or HTML, search for inline alerts that start with >>>>>  gd2md-html alert:  for specific instances that need correction.</ul>

<p style="color: red; font-weight: bold">Links to alert messages:</p><a href="#gdcalert1">alert1</a>

<p style="color: red; font-weight: bold">>>>>> PLEASE check and correct alert issues and delete this message and the inline alerts.<hr></p>


Socialify

Saludos, el equipo DevOps está a su disposición. 

**Introducción**

En el presente documento, se brindará una explicación detallada sobre la arquitectura del código y las diversas utilidades que los desarrolladores pueden aprovechar al máximo.

**Arquitectura**

El uso de Github Actions se caracteriza por su sencillez. En calidad de DevOps, disponemos de ficheros denominados YAML que permiten la creación de máquinas virtuales con el propósito de ejecutar el código desarrollado por nuestros compañeros. Esta ejecución puede automatizarse al ocurrir ciertos eventos específicos. En nuestro caso, garantizamos que todas las pruebas mínimas se ejecuten al realizar un pull request o commit en la rama principal (main), asegurando así la integridad y calidad del código en un 100%. Esto también conlleva la disminución de la carga de trabajo para el equipo de Control de Calidad, un hecho que preferimos mantener en reserva.

**Aplicación**

Si está leyendo esta documentación, es de esperar que cuente con un conocimiento básico en el ámbito informático. Dado que trabajamos con dos repositorios a fin de evitar posibles conflictos, hemos adaptado la aplicación de nuestro trabajo a las preferencias de cada grupo de desarrolladores. Por lo tanto, posteriormente desglosaremos el contenido en sus respectivas secciones.

**Operaciones para Desarrolladores**

Ahora bien, adentrémonos en la parte que llamará la atención de todos...

Empecemos por los desarrolladores del Backend. La lista de operaciones necesarias para ejecutar las pruebas es la siguiente: y es relevante mencionar que estas pruebas se ejecutan automáticamente con cada pull request, lo que esperamos haga que el proceso sea menos tedioso y sin complicaciones.

Para los desarrolladores de Frontend, 'e un mondo difficile' (es un mundo complicado), como dicen. 

No obstante, su DevOps de confianza se lo pone sencillo. Para ejecutar todas las pruebas, basta con agregar la etiqueta "RunTest" a un pull request, lo cual automáticamente ejecutará todos los test disponibles en la rama. ¿Sencillo, verdad? 

**Despliegue (Deploy)**

En aras de reducir el tiempo computacional en GitHub Actions, hemos limitado las operaciones de despliegue (deploy) exclusivamente al push en la rama "Developing" y a cualquier interacción con la rama principal (main).

**Pruebas**

Seguramente se preguntarán acerca de los desafíos que nuestro código debe superar. Permítanos explicarles:


    **Backend:**



* Pruebas Unitarias
* Lint (análisis estático del código)
* Pruebas de Postman

    **Frontend:**

* Lint (análisis estático del código)
* Prettier (formateo de código)
* Pruebas unitarias con Vitest
* Pruebas de Selenium

**Mantenimiento**

Si usted es un desarrollador de Socialify y desea personalizar el flujo de trabajo de acuerdo a sus preferencias, no dude en ponerse en contacto con nosotros a través de Slack o WhatsApp. Estamos a su disposición para atender sus solicitudes.

Del mismo modo, si identifica algún error, le instamos a informárnoslo. Agradecemos su colaboración.

**Conclusión**

Si ha llegado hasta este punto, le agradecemos por valorar nuestro trabajo. No obstante, es evidente que su tiempo es valioso &lt;3.


    

<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.jpg "image_tooltip")
 \