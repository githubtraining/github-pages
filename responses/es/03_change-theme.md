## Paso 4: Personaliza los detalles del sitio

¡Buen trabajo! Puedes ver tu sitio publicado [aquí]({{ deploymentUrl }}). Si no ves tus cambios inmediatamente, refresca la página.

### Preparar tu página para usarla como blog

Jekyll utiliza un archivo llamado `_config.yml` para almacenar los ajustes de tu sitio web, la plantilla o el tema del sitio y contenido reutilizable como el título de tu sitio y tu nombre de usuario de GitHub.

Puedes comprobar el archivo `_config.yml` en la pestaña **Code** de tu repositorio.

### :keyboard: Actividad: Modifica el archivo de configuración

Vamos a modificar `_config.yml` para que refleje perfectamente con tu nuevo blog. Primero, tenemos que aplicar una plantilla o tema que funcione con blogs. Para esta actividad, usaremos un tema llamado `minima`.



1. Navega a la pestaña **Code** de este repositorio y hasta el archivo `_config.yml`, o haz clic en [este enlace]({{ repoUrl }}/blob/master/_config.yml).
2. En la esquina superior derecha, haz clic en :pencil2: para abrir el editor.
3. Añade un `theme:` que especifique **minima**, de forma que se vea así en tu archivo `_config.yml`:
    ```
    theme: minima
    ```
4. Modifica las otras variables de configuración, como `title:`, `author:` y `description:`, para personalizar tu sitio web.
5. Haz clic en **Create a new branch for this commit and start a pull request**.
6. Abre un pull request.

<hr>
<h3 align="center">Busca mi siguiente respuesta en tu pull request.</h3>
