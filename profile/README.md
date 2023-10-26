<img src="https://github.com/UB-ES-2023-F3/SocialifyFrontend/assets/44063174/509e9256-8887-4a14-831e-0a6d726ae7b1" width="400" align="center" />

# Socialify

Saludos, el equipo DevOps está a su disposición. 

**Introducción**

En el presente documento, se brindará una explicación detallada sobre la arquitectura del código y las diversas utilidades que los desarrolladores pueden aprovechar al máximo.

**Arquitectura**

El uso de Github Actions se caracteriza por su sencillez. En calidad de DevOps, disponemos de ficheros denominados YAML que permiten la creación de máquinas virtuales con el propósito de ejecutar el código desarrollado por nuestros compañeros. Esta ejecución puede automatizarse al ocurrir ciertos eventos específicos. En nuestro caso, garantizamos que todas las pruebas mínimas se ejecuten al realizar un pull request o commit en la rama principal (main), asegurando así la integridad y calidad del código en un 100%. Esto también conlleva la disminución de la carga de trabajo para el equipo de Control de Calidad o QA.

**Aplicación**

Si está leyendo esta documentación, es de esperar que cuente con un conocimiento básico en el ámbito informático. Dado que trabajamos con dos repositorios a fin de evitar posibles conflictos, hemos adaptado la aplicación de nuestro trabajo a las preferencias de cada grupo de desarrolladores. Por lo tanto, posteriormente desglosaremos el contenido en sus respectivas secciones.

**Operaciones manuales para Desarrolladores**

Ahora bien, adentrémonos en la parte que interesará a todos...

Empecemos por los desarrolladores del Backend. La lista de operaciones necesarias para ejecutar las pruebas es la siguientes: FIN. Es relevante mencionar que estas pruebas se ejecutan automáticamente con cada pull request, lo que esperamos haga que el proceso sea menos tedioso y sin complicaciones.

Para los desarrolladores de Frontend, 'e un mondo difficile' (es un mundo complicado), como dicen. 

<img src="difficile.png"/>

No obstante, su DevOps de confianza se lo pone sencillo. Para ejecutar todas las pruebas, basta con agregar la etiqueta "RunTest" a un pull request, lo cual automáticamente ejecutará todos los test disponibles en la rama. ¿Sencillo, verdad? 

**Despliegue (Deploy)**

En aras de reducir el tiempo computacional en GitHub Actions, hemos limitado las operaciones de despliegue (deploy) exclusivamente al push en la rama "Developing" y a cualquier interacción con la rama principal (main). Adicionalmente, antes de hacer u push a la rama de produción se ejecutaran todos los test de nuevo para garantizar la integridad del codigo.

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

Si ha llegado hasta este punto, le agradecemos por valorar nuestro trabajo.<3.


    

