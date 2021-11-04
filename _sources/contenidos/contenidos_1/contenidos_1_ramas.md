# Ramas en el repositorio.

* Siempre al principio en el repositorio hay una sola <span style="color: blue; font-family: Babas; font-size: 1.12em;">rama</span> que se llama main y que es la rama principal.

* Trae ahora a tu máquina local, este repositorio GitHub recién creado.

* Por simplicidad, en el escritorio de tu máquina local, crea una nueva carpeta. Por ejemplo, llámale <span style="color: blue; font-family: Babas; font-size: 1.12em;">github</span>.

* Cambia el directorio (<span style="color: blue; font-family: Babas; font-size: 1.12em;">cd</span>) y entra a tu nueva carpeta. Abre tu terminal y activa tu ambiente virtual. Asegúrate de tener instalado python y git.

* Clona el repositorio usando un cliente git.

* Copia la dirección del repositorio que acabamos de crear en GitHub y en la terminal abierta, ejecuta la siguiente línea de comando: 

```console
kasparov@kasparov-MS-7B58:~/Escritorio/github$ git clone <link del repositorio GitHub>
```

* Si todo está bien, deberías ver:

<img src="/figures_readme/git_clone.png" alt="fishy" class="bg-primary" width="550px" align="center"/>

<br/><br/>

## Entra a la carpeta (cd).

* En la terminal abierta, entra a la carpeta ejecutando la línea de comando: 

```console
kasparov@kasparov-MS-7B58:~/Escritorio/github$ cd uso_github
```
* El único archivo que se ve es el <span style="color: blue; font-family: Babas; font-size: 1.12em;">README.md</span>. Deberías ver lo siguiente:

<img src="/figures_readme/readme.png" alt="fishy" class="bg-primary" width="550px" align="center"/>

<br/><br/>

* El archivo <span style="color: blue; font-family: Babas; font-size: 1.12em;">.gitignore</span> está oculto. Para ver los archivos ocultos ejecuta la siguiente línea de comando:

```console
kasparov@kasparov-MS-7B58:~/Escritorio/github/uso_git$ ls -la
```
* Si todo está bien, deberías ver:

<img src="/figures_readme/hidden.png" alt="fishy" class="bg-primary" width="550px" align="center"/>

<br/><br/>

* También, observa la carpeta <span style="color: blue; font-family: Babas; font-size: 1.12em;">.git</span>. Sin esta carpeta no podrías hacer, por ejemplo, lo siguiente:

```console
kasparov@kasparov-MS-7B58:~/Escritorio/github/uso_git$ git status
```
* Lo que te permite ver que esto es un proyecto Git. Siempre para ver el estado de tu repositorio, usa los comandos <span style="color: blue; font-family: Babas; font-size: 1.12em;">git status</span>. Te muestra en qué rama estás y te dice que esta rama ya está actualizada.

