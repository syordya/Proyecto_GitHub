# Tutorial de Git
Guia de comandos de Git y GitHub

# Pasos
<p>mkdir.. : Crear la carpeta de nuestro proyecto
<p>pwd : Localizar el proyecto
<p>cd.. : Ubicar el proyecto en el terminal

<p>git init : Para inicializar un repostorio Git</p>
<p>git status : Para ver los cambios, agregar archivos y decirme que archivos no estoy llevndo registro</p>
<p>git add . : Para agregar todos los archivos dentro de la carpeta</p>
<p>git --global user.email "brian4silva@live.com"</p>
<p>git --global user.name "Brian"</p>
<p>git commit -m "Comment": Para realizar el commit con un comentario</p>

<p>Al cambiar un archivo puedo saber que archivos cambiaron con git status y saber que cambio exactamente con git diff</p>

<p>git checkout -- myHuerto/app/Http/Controllers/AddController.php : Para regresar a los cambios anteriores</p>
<p>git branch : Para ver todas las ramas</p>
<p>git branch prueba : Rama llamada prueba</p>
<p>git checkout prueba : Entrar a la rama prueba</p>
<p>git add .</p>
<p>git commit -m "Prueba de commit en branch prueba" : Para hacer commit en una rama</p>


<p>git remote add origin https://github.com/Brian022/PruebaGit.git</p>
<p>git push -u master : Para subir los cambios a github en master pedira Iniciar sesión</p>
<p>git push -u prueba : Para subir los cambios a github en la rama prueba</p>
