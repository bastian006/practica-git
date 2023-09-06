<h1> configurar un repositorio nuevo desde terminal </h1>
<ol>
    <li> git init </li> <!--inicializar un repositorio vacio en nuestra carpeta-->  
    <li> git add .</li> <!--agregar archivos nuevos y con cambio a la version actual-->
    <li> git commmit -m "Dejar un mensaje"</li> <!--Crea la version nueva con los cambios actuales-->
    <li> Ir a Github y crear un repositorio vacio </li><!--Inicializa el repositorio en nuestra cuenta github-->
    <li> git remote add origin url-del-github-vacio </li><!--Enlaza el repositorio de nuestra cuenta con el repositorio de nuestra carpeta-->
    <li> git push -u origin mastrer </li> <!--Actualiza la version actual de nuestra carpeta en el repositorio de nuestra cuenta-->
</ol>

<h1> Generar una nueva version y actualizar el repositorio </h1>

<ol>
    <li>git add .</li>
    <li>git commit -m "un nuevo mensaje"</li>
    <li>git push -u origin main</li>
</ol>