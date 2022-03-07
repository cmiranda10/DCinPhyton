# DCinPython
Tutorial Github

![Link an image.](/GH1.png)

## Qué es Github
 
Github es un portal creado para alojar el código de las aplicaciones de cualquier desarrollador, y que fue comprada por Microsoft en junio del 2018. La plataforma está creada para que **los desarrolladores suban el código de sus aplicaciones y herramientas**, y que como usuario no sólo puedas descargarte la aplicación, sino también entrar a su perfil para leer sobre ella o colaborar con su desarrollo.
Como su nombre indica, la web utiliza el sistema de control de versiones Git diseñado por [Linus Torvalds](https://www.xataka.com/preview-main/219296/d48f7c92ccc696c85361158ae4ac26f8). Un sistema de gestión de versiones es ese con el que **los desarrolladores pueden administrar su proyecto**, ordenando el código de cada una de las nuevas versiones que sacan de sus aplicaciones para evitar confusiones. Así, al tener copias de cada una de las versiones de su aplicación, no se perderán los estados anteriores cuando se va a actualizar.

## Instalación en el computador de Git
En la página oficial de Git, que es 'git-scm.com'. Se descarga el archivo dentro de el navegador. Ahora, una vez que se ha descargado, simplemente se presiona el botón Ejecutar y esto va a ejecutar el instalador de Git dentro del ordenador.  Después se busca el programa Git Bash. Esta aplicación lo que permite es acceder a Git desde la consola. 

![Link an image.](/05Screen.png)

## Iniciar un repositorio en GitHub
Se selecciona el botón de New. Esto permite comenzar un nuevo repositorio.  También podemos encontrar dentro del menú principal la opción de crear un nuevo repositorio. Lo cual lleva a esta página donde se generar el repositorio nuevo, donde se define con descripción. Un repositorio público es un repositorio en el que cualquier persona que entre a 'github.com' va a poder acceder. Tenemos acá la opción de crear un 'README'. El 'README' es un archivo especial que permite desplegar información sobre el repositorio. 'gitignore' permite ignorar archivos específicos que, por ejemplo, pueden ser archivos que no necesariamente van a aportar un valor al repositorio.  Y el archivo 'README' utiliza un formato llamado **"markdown"**, Se pueden incluir imágenes y enlaces.  Se puede incluir acá la información de un **'commit'**. en este caso simplemente se presiona Commit changes y se guarda el archivo como si se hubiese hecho un 'commit' utilizando la terminal o algún programa de envío trabajando con Git. 

![Link an image.](/07Screen.png)

## Comenzando un repositorio
Se crea un repositorio de manera local que después puede ser integrado con GitHub, utilizando la consola. Se usa el programa **Git Bash**, Primero se abre la carpeta donde se va a encontrar el repositorio.  Se ingresa a esta carpeta desde la terminal, se escribe el comando **'cd'** y esto nos va a permitir cambiar de directorio. Y se arrastra la carpeta y aparece automáticamente la ruta. Se presiona Enter y se encuentra dentro de esta carpeta a través de la consola. Para inicializar el repositorio de Git, simplemente se llama al comando **'git init'** y esto va a inicializar un repositorio dentro de esta carpeta. Al abrirla se encuentra una carpeta '.git'. Una vez que se tenga creado este repositorio, se va a trabajar el código dentro de esta carpeta y todo va a quedar almacenado, y todas las versiones van a quedar también almacenadas dentro de Git. En la imagen se puede ver la ruta de mi pc.

![Link an image.](/08Screen.png)

## Estado del repositorio
Git permite conocer cuál es el estado actual. Se sabe exactamente si todas las versiones de los archivos o si todos los archivos que tenemos dentro del repositorio están correctamente almacenados.  Se llama el comando **'git status'**, que permite saber cuál es el estado actual de este repositorio. Por ahora, se encuentra dentro del **"commit"** o envío de datos inicial y que todos los datos se encuentran sincronizados correctamente. Si se agrega un nuevo archivo.  Se ve ahora cómo ha cambiado el estado de este repositorio. Se vuelve a poner el comando **'git status'** y vamos a ver que muestra un mensaje donde se dice que este repositorio no se encuentra debidamente actualizado. De hecho, se ve el archivo que se acaba de agregar, el archivo **“muestra”**,  Esto significa que no se encuentra debidamente incluido dentro del repositorio Git. De esta forma, se sabe cuál es el estado en el que se encuentra el repositorio y llevar un control de todos los archivos sin necesidad de inicializar ninguna herramienta; se puede hacer directamente desde la consola.

![Link an image.](/09Screen.png)

## Agregando archivos y guardando versiones en GitHub
Para a agregar directamente un archivo; en este caso, “muestra”.  Para agregarlo, utilizaremos el comando **'git add’** ver imagen anterior y utilizar diferentes opciones para este comando. Por ejemplo, que agregue directamente este archivo o que agregue, por ejemplo, únicamente los archivos con la extensión txt, o la forma más sencilla, s**olo dejar un espacio, se pone punto y esto va a agregar cualquier archivo que necesite ser agregado**.  Se repite el comando **'git status'** y se ve que ahora el repositorio está listo para agregar este nuevo archivo. Se va a incluir esta versión dentro del repositorio con el comando **'git commit'**. **'Git commit'** lo que va a hacer es que va a enviar datos para que queden almacenados dentro del repositorio de manera permanente. Se puede incluir también un mensaje. Se escribe entonces **'-m' y este comando permite incluir un mensaje**, que es una opción recomendada. Lo ideal es que siempre se incluya cada vez que se envien datos, porque así las personas que revisen el repositorio puedan entender cuál fue el cambio que se hizo. Entonces, **se ponen entre comillas y se presiona Enter** y ya se tiene listo el repositorio con este cambio. Ahora se tiene el archivo en un estado de **"staging"**. **El "staging"** es básicamente una opción que permite guardar los cambios, pero todavía no están listos para estar dentro del repositorio.

![Link an image.](/10Screen.png)

## Enviar repositorios a GitHub
Este es el punto de entrada para poder interactuar con el repositorio. De hecho, acá aparece una serie de comandos. Primero, se agrega esta línea de comando **'git remote add origin'**. Git agregua un nuevo repositorio remoto y se le pone la dirección que va a tener. Esta es la dirección del repositorio dentro de GitHub. Ahora, este repositorio remoto se encuentra relacionado con el proyecto. Aún los archivos no se encuentran en la nube, pero ya se pueden enviar. Para esto, se utiliza un segundo comando: **'git push -u origin máster'**. Se copia y lo que se está haciendo es dicirle a Git que ejecute el comando **'push'**. **'Push'** lo que hace es que va a enviar información a otro repositorio. El repositorio al que se envia es **'origin máster'**.  Se esta definiendo que **'origin'** es el repositorio de GitHub y **'master'** es específicamente el **"branch"** o la rama en la que se encuentra. Al definir **'máster'**, se habla de la rama principal del repositorio. Se presiona Enter y, si es la primera vez que se ejecuta, pide el nombre de usuario para GitHub.  También pide el "password" y va a enviar toda la información a través de la consola.... la consola se va a encargar de enviar toda la información del equipo a la nube de GitHub. Se revisa ahora el repositorio creado en GitHub. Hasta hace unos segundos estaba vacío. Ahora está el archivo debidamente guardado, en este momento hay sincronizados dos diferentes repositorios y se puede seguir trabajando haciendo cambios de manera local, modificando repositorio y, cada vez que esté listo para almacenar la información en la nube, se repite este mismo proceso para tener todos los datos dentro de GitHub.

![Link an image.](/11Screen.png)

Se puede observar en las imagenes el procedimiento relaizado en mi pc. Repositorio https://github.com/cmiranda10/Lab1.git

Egrafia
(https://www.xataka.com/preview-main/219296/d48f7c92ccc696c85361158ae4ac26f8)










 

