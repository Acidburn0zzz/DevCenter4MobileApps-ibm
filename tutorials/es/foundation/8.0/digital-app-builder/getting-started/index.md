---
layout: tutorial
title: Iniciación
weight: 3
show_children: true
---
<!-- NLS_CHARSET=UTF-8 -->
## Visión general
{: #getting-started }

Puede iniciar Digital App Builder desde:

* En **MacOS**, efectúe una doble pulsación en el **icono de IBM Digital App Builder** para abrir Digital App Builder. 
* En **Windows**, inicie Digital App Builder seleccionando **Inicio > Programas > IBM Digital App Builder**.

>**Nota**: Si está abriendo Digital App Builder por primera vez, **Acepte** la **Licencia para utilizar IBM Digital App Builder** en la pantalla para continuar. Después de aceptar el acuerdo de licencia, la **Comprobación de requisitos previos** se ejecuta automáticamente por primera vez. Pulse **Aceptar** para continuar, si no se han encontrado errores, de lo contrario, corrija los errores y, a continuación, reinicie Digital App Builder. 

![IBM Digital App Builder](dab-home-screen.png)

Puede **Crear aplicación** o **Abrir aplicación** o utilizar las plantillas disponibles para continuar trabajando con su aplicación. 
>**Nota**: Puede ver la aplicación creada recientemente en la sección **Reciente**. Para una nueva instalación, no verá la sección **Reciente**. 


### Creación de una aplicación
{: #create-new-app }

Puede crear una nueva aplicación pulsando el icono **Crear aplicación** desde el panel de control del constructor. 

1. Pulse el icono **Crear aplicación**. Se visualizará la ventana **Seleccionar canal**. 

    ![Seleccionar canal](dab-select-channel.png)

2. Seleccione el canal para el que desea desarrollar la aplicación, pulsando en el icono correspondiente. Más adelante, puede añadir más canales a la misma aplicación. 

    * **Android**: Seleccione esta opción si está creando una aplicación android.
    * **iOS**: Seleccione esta opción si está creando una aplicación iOS.
        >**Nota**: Puede crear y ejecutar aplicaciones de iOS sólo en MacOS.
    * **Web**: Seleccione esta opción si está creando la aplicación para la web.
    * **PWA**: Seleccione esta opción si está creando una aplicación PWA (Progressive Web App). 

3. Se visualiza la ventana **Seleccionar el tipo de servidor al que conectarse**. 

    ![Seleccionar el tipo de servidor al que conectarse](dab-select-server.png)

4. Puede seleccionar **Servidor de Playground compartido** o **Servidor profesional personalizado**.

    * **Servidor de Playground compartido** – Un servidor de Mobile Foundation compartido alojado en IBM Cloud para que pueda empezar con rapidez. 

        >**Aviso**: El servidor Playground compartido es un servidor común que se comparte entre muchos desarrolladores. Este servidor no se debe utilizar para aplicaciones de producción. Los datos de este servidor se pueden suprimir sin previo aviso. El tiempo de actividad del servidor no está garantizado.

        ![Servidor compartido de IBM](dab-shared-server.png)

        * Especifique la **Clave de API de IBM Cloud**. Para obtener más detalles, consulte [**Cómo crear claves de API de plataforma**](../faq/) en la sección de preguntas más recientes (FAQ).  

        * Pulse **Iniciar sesión** para conectarse al servidor. 

    * **Servidor profesional personalizado** – Puede conectarse a su propio servidor de Mobile Foundation ya sea creado en IBM Cloud o localmente. En la ventana **Configurar la instancia de IBM Mobile Foundation**, seleccione un servidor existente o cree un nuevo servidor.

        ![Configuración de la instancia de IBM Mobile Foundation](dab-config-ibm-cloud-instance.png)
 
        La ventana **Configurar la instancia de IBM Mobile Foundation** muestra la lista de instancias de servidor de Mobile Foundation que ha definido anteriormente. Al seleccionar el servidor, se visualiza el **Nombre de servidor**, el **URL de servidor**, el **Nombre de usuario administrador** y la **Contraseña de administrador**. Para definir un nuevo servidor, puede pulsar el enlace **Crear nuevo servidor**. Esto mostrará la nueva ventana **Configurar la instancia de IBM Mobile Foundation**. 

        ![Crear un nuevo servidor](dab-custom-professional-server.png)

        * Especifique los nuevos detalles de la instancia de IBM Mobile Foundation como, por ejemplo, **Nombre de servidor**, **URL de servidor**, **Nombre de usuario administrador** y **Contraseña de administrador**.
        >**Nota**: Puede obtener el URL de servidor y las credenciales de inicio de sesión desde el panel de control del servidor de Mobile Foundation para la instancia de servidor seleccionada. 
        * Opcionalmente, proporcione un **Nombre de usuario** (nombre de usuario de cliente confidencial) y una **Contraseña de administrador**, para obtener una vista previa de los datos en el visor de datos. 
        * Pulse **Conectar**.

5. Al iniciar sesión/conectarse correctamente, se visualiza la ventana **Crear aplicación** donde puede seleccionar una definición de aplicación existente que puede haber creado o crear una nueva especificando los detalles.  
    * Para una nueva aplicación, proporcione: **Nombre** de la aplicación, **Ubicación** en la que se almacenarán los archivos del proyecto, **Proyecto/ID de paquete**y **Versión** de la aplicación.  
 
        ![Servidor de Playground compartido](dab-create-app.png)

    * Pulse **Crear** para crear la aplicación. Esta opción visualiza la ventana **Bienvenido al entorno de trabajo**. 
    * Pulse **Empecemos**. Esto abre el espacio de trabajo de Digital App Builder para crear una nueva aplicación/modificar una aplicación existente. 

        ![Espacio de trabajo de DAB](dab-workbench.png)

### Cómo abrir una aplicación existente
{: #open-an-existing-app }
 
>**Nota**: Puede abrir una aplicación existente que únicamente se haya desarrollado con Digital App Builder. 

Puede abrir una aplicación existente de una de las siguientes maneras: 

* Pulsar **Abrir una aplicación** desde la página de inicio abre el explorador de archivos. Vaya hasta la carpeta del proyecto de su aplicación y pulse **Aceptar** para abrir la aplicación para editarla. 
* Opcionalmente, puede abrir la aplicación desde la lista de aplicaciones recientes, si se lista, realizando una doble pulsación en el nombre de dicha aplicación. 

### Utilización de plantillas
{: #using-templates }

Puede utilizar plantillas para crear de forma rápida su aplicación. Estas son plantillas de aplicaciones habilitadas para funciones específicas que le ayudarán a modificar y desarrollar rápidamente la aplicación. Ahora mismo únicamente está disponible el chatbot de Watson. 
