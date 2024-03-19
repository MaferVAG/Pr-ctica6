**1. ¿Como se inicializa un repositorio en Git?**   
Primero debemos de iniciar git desde la terminal de git-bash, ahí deberemos de colocar el comando de 
``` 
git init
``` 
con esto se creara una rama principal.

**2. ¿Cómo creas un repositorio en GitHub?**  
Deberás iniciar sesión en GitHub, dentro de la página tendrás que picar el signo de + y seleccionar crear un nuevo repositorio, deberás de darle un nombre y configurar las demás opciones según lo que necesites, finalmente solo deberás de presionar en crear repositorio y listo.

**3. ¿Cómo vinculas un repositorio local de Git con uno remoto de GitHub?**  
Ya que iniciaste git en tu repositorio local deberás de agregar todos los archivos deseados con el comando 
```
git add .
 ``` 
 para después crear el primer commit con el comando 

```
git commit -m "Primer commit"
``` 

y cambiar la rama principal de master a main con el comando 
```
git branch -M main
``` 
Después con el comando 
```
git remote add origin *link de tu repositorio**
``` 
uniras el repositorio local con el remoto y finalmente solo deberás de subir todo tu repositorio con el comando 
``` 
git push -u origin main
``` 

**4. ¿Cuál es el flujo básico de trabajo en Git y GitHub?**  
Git tiene tres estados locales que es donde se trabaja y uno más de manera remota que es cuando entramos con GitHub.
Los estados son:  
- _Modified:_ es la carpeta local de la computadora donde almacenas tu proyecto.
- _Staged:_ es donde Git indexa y agrega cambios de los archivos en su registro.
- _Commited:_ aqui los cambios ya se registaron en el repositorio.
- _Remote:_ es el repositorio remoto donde almacenamos nuestro proyecto en este caso GitHub.

**5. ¿Para que sirve el archivo .gitignore?**  
Es un archivo de git el cual agregamos para que dentro de este podamos indicar que archivos no queremos incluir o agregar en nuestro repositorio.

**6. ¿Cuál es el propósito de una rama?**
Nos ayuda a crear una nueva línea independiente a la main, en esta podremos desarrollar nuevas características a nuestro código sin alterar el repositorio principal. Es como crear una realidad alterna de nuestro código la cual podemos agregar al original despues sin afectarlo.

**7. Qué es una fusión?**  
Unes dos ramas de tu repositorio, las combinas.

**8. Explica los diferentes tipos de fusión que existen.**  
Existen dos:
- _Fast-Forward:_ se hace en automático la fusión.
- _Manual-Merge:_ se debe hacer la fusión manual ya que hay problemas que resolver en el contenido.

**9. ¿Cómo puede ver el historial de tu repositorio?**  
Dentro de la terminal de comandos podemos escribir el comando de 
```
git log
```
esto causará que se imprima todo el historial en la consola.

**10. ¿Cuál es el propósito de una etiqueta?**  
Las etiquetas nos ayudan a versionar nuestro proyecto, por ejemplo para cuando corregimos errores, bugs o simplemente actualizamos una nueva versión del código, es como marcar un punto en el historial de tu código.