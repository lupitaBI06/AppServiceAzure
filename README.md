# Cómo subir una página Web al App Service de Azure

Azure App Service proporciona una plataforma como servicio (PaaS) ya que puede implementar, compilar y escalar de forma rápida aplicaciones de API, móviles y web. Una de las ventajas que tiene es que satisface los requisitos de rendimiento, escalabilidad y cumplimiento.

**¿Cuándo usar App Service dde Azure?**

App Service de Azure se utiliza cuando:

- No se requiere administrar la infraestructura.
- Requiere escalado automático y alta disponibilidad.

Los tipos de servicios que ofrece incluyen:

- Aplicaciones web.
- API.
- Trabajos web.
- Aplicaciones móviles


En pocas palabras, el App Service de Azure sirve para hacer cualquier cosa web. Los costos son por hora.

### Pasos para subir una página web al App Service de Azure

- Dentro del [portal de azure](www.portal.azure.com) se busca el recurso App Service.

![buscar recurso](Imagenes\crear_app_service.PNG)

- Se crea el recurso, llenando los campos correspondientes (recuerda que a parte de los elementos mínimos que necesita: Suscripción, grupo de recursos, nombre y región se necesitan otros campos obligatorios dependiendo del recurso).

![crear recurso](Imagenes\crear.PNG)

- Una ves modificados los campos rerqueridos se da en revisar y crear, ya validado se crea el recurso.

![campos requeridos](Imagenes\requerimientos_generales.PNG)

![campos requeridos2](Imagenes\requerimientos_generales2.PNG)

Ya que esta creado entramos la recurso, en la parte superior derecha muestra la URL de nuestra página web.

![ubicación url](Imagenes\url.PNG)

Dentro del recurso damos clic en centro de implementación.

![centro de implementación](Imagenes\centro_implementación.PNG)

En este ejemplo se muestra la implementanción desde un repositorio en GitHub.

Dentro del centro de implementación, en origen nos da varias opciones. Se selecciona GitHub.

![centro de implementación abierto](Imagenes\centro_impl_abierto.PNG)

Se inicia sesión en la cuenta de GitHib donde se encuentra el repoitorio.Se selecciona el repositorio y se da en guardar (botón que se encuentra en la esquina superior izquierda).

![seleccion repositorio](Imagenes\seleccion_repositorio.PNG)

Si entramos al repositorio desde GitHub, en actions podemos ver que ya se esta implementando.

![seleccion repositorio](Imagenes\github_actions.PNG)

Cuando aparece la palomita significa que la página ya se subió con éxito.

![seleccion repositorio](Imagenes\cargado.PNG)

Con esto podemos entrar a la URL y encontrar nuesyra página subida con éxito.

![seleccion repositorio](Imagenes\paginasubida.PNG)


____________________________________________________________________________________

Si la página web se ecuentra en otro repositorio de git, se clona el repositorio de la siguiente manera:

- Se copia el link del repositorio que se quiere clonar 

![seleccion repositorio](Imagenes\clonar_reepositorio.PNG)

- Se abre el cmd desde la dirección de la carpeta donde se quiere clonar el repositorio, con las lineas git clone y se pega el link del repositorio que se quiere clonar.

![seleccion repositorio](Imagenes\clone_cmd.PNG)

Abrir la carpeta del repositorio clonado y hacer los pasos para crear el repositorio remoto dentro de nuestra cuenta de GitHUb.


