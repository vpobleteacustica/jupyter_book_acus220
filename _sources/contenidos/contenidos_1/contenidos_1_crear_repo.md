# Crear un nuevo repositorio en GitHub.

* Entrar a su cuenta en GitHub y crear un repositorio nuevo.

* Darle un nombre al repositorio Git.
    * Por ejemplo, le llamaremos <span style="color: blue; font-family: Babas; font-size: 1.12em;">uso_git</span>.

* Redactar una descripción inicial.
    * Por ejemplo: Uso básico de Git y primeras aplicaciones.

* 4\. Elegir entre Privado o Público.
    * 4.1\. Sugerencia seleccionar Público.

* 5\. Agregar un archivo README. 
    * 5.1\. Este es un instructivo global del repositorio que se está creando.

* 6\. Agregar un <span style="color: blue; font-family: Babas; font-size: 1.12em;">.gitignore</span>
    * 6.1\. Este es importante porque es aquí donde uno declara qué archivos o carpetas, uno <span style="color: blue; font-family: Babas; font-size: 1.12em;">no quiere</span> que se suban al repositorio Git, que se mantengan de manera local solamente. Como por ejemplo, las carpetas y archivos del entorno virtual ya que uno no quiere que esas instalaciones, que uno tiene en local, se suban al repositorio Git. 
    * 6.2\. Observar las opciones que ofrece. Dependiendo del lenguaje y del proyecto, uno puede elegir un .gitignore en particular, como por ejemplo, <span style="color: blue; font-family: Babas; font-size: 1.12em;">Python</span>, que tiene ya una lista de archivos posible que uno no quiere subir.
* 7\. Omitir por esta vez <span style="color: blue; font-family: Babas; font-size: 1.12em;">Choose a license</span>. 
* 8\. Crear el repositorio.

# Observar lo que se muestra en el repositorio.

* 1\. El Readme que se ve al principio.
* 2\. El .gitignore para Python que se seleccionó, que muestra archivos y carpetas que se generaron en Python. Por ejemplo, se observan los <span style="color: blue; font-family: Babas; font-size: 1.12em;"># Jupyter Notebook</span>, <span style="color: blue; font-family: Babas; font-size: 1.12em;"># Environments</span>, entre otros.
* 3\. Este archivo .gitignore es totalmente editable.
* 4\. Ir a <span style="color: blue; font-family: Babas; font-size: 1.12em;">main</span>

# Ramas en el repositorio.

* 1\. Siempre al principio en el repositorio hay una sola <span style="color: blue; font-family: Babas; font-size: 1.12em;">rama</span> que se llama main, que es la principal.

* 2\. Vamos a traer este repositorio Git que hemos creado a nuestra máquina.

* 3\. Crear en el escritorio de su máquina una nueva carpeta. Por ejemplo, le llamaremos <span style="color: blue; font-family: Babas; font-size: 1.12em;">github</span>.

* 4\. Ya en en su nueva carpeta, abrir una terminal.

* 5\. Copiar la dirección del repositorio que acabamos de crear en GitHub y en la terminal abierta, ejecutemos la línea de comando: 

```console
kasparov@kasparov-MS-7B58:~/Escritorio/github$ git clone <link del repositorio GitHub>
```

* 6\. Si todo está bien, deberíamos ver:

<img src="/figures_readme/git_clone.png" alt="fishy" class="bg-primary" width="550px" align="center"/>

<br/><br/>

# Entrar a la carpeta.

* 1\. En la terminal abierta, vamos a entrar a la carpeta ejecutando la línea de comando: 

```console
kasparov@kasparov-MS-7B58:~/Escritorio/github$ cd uso_git
```
* 2\. El único archivo que se ve es el <span style="color: blue; font-family: Babas; font-size: 1.12em;">README.md</span>. Se debería ver lo siguiente:

<img src="/figures_readme/readme.png" alt="fishy" class="bg-primary" width="550px" align="center"/>

<br/><br/>

* 3\. El archivo <span style="color: blue; font-family: Babas; font-size: 1.12em;">.gitignore</span> está oculto. Para ver los archivos ocultos ejecutar la línea de comando:

```console
kasparov@kasparov-MS-7B58:~/Escritorio/github/uso_git$ ls -la
```
* 4\. Si todo está bien, deberíamos ver:

<img src="/figures_readme/hidden.png" alt="fishy" class="bg-primary" width="550px" align="center"/>

<br/><br/>

* 5\. También, vemos la carpeta <span style="color: blue; font-family: Babas; font-size: 1.12em;">.git</span>. Sin esta carpeta, no se podría hacer por ejemplo, lo siguiente:

```console
kasparov@kasparov-MS-7B58:~/Escritorio/github/uso_git$ git status
```
* 6\. Lo que nos permite ver que esto es un proyecto Git. Siempre para ver el estado de un repositorio usamos <span style="color: blue; font-family: Babas; font-size: 1.12em;">git status</span>. Nos muestra en qué rama estamos y que esta rama está actualizada.

