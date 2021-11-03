# Queremos ahora hacer una actualización de nuestro repositorio.

* Como ya vemos, estamos en la rama <span style="color: blue; font-family: Babas; font-size: 1.12em;">main</span>.

* Vamos a hacer una nueva <span style="color: blue; font-family: Babas; font-size: 1.12em;">rama</span>. En ocasiones se le llama rama de producción, es decir, la rama que queremos mostrar, que queremos subir como la versión funcional de nuestro proyecto.

* Supongamos que queremos hacer alguna tarea en específico, por ejemplo, extraer <span style="color: blue; font-family: Babas; font-size: 1.12em;">features</span> de una señal de audio. Para eso, crearemos una nueva rama que la llamaremos <span style="color: blue; font-family: Babas; font-size: 1.12em;">feature_1</span>. Para esto, vamos a ejecutar <span style="color: blue; font-family: Babas; font-size: 1.12em;">git checkout -b</span> y agregaremos a continuación, el nombre que le queremos dar a la nueva rama:

```console
kasparov@kasparov-MS-7B58:~/Escritorio/github/uso_git$ git checkout -b feature_1
```

* La idea es que el nombre de la rama sea lo más descriptivo posible de lo que contiene esa rama. Si todo está bien, deberíamos ver:

<img src="/figures_readme/nueva_rama.png" alt="fishy" class="bg-primary" width="550px" align="center"/>

* Lo que hemos hecho en este paso anterior, es que hemos tomado todo el código que se encuentra en la rama <span style="color: blue; font-family: Babas; font-size: 1.12em;">main</span> y lo hemos copiado a esta nueva rama <span style="color: blue; font-family: Babas; font-size: 1.12em;">feature_1</span>. Imagínenselo como que ambas ramas ahora van en el mismo nivel de código, porque hasta ahora no hemos hecho ningún cambio.

* Aquí en esta rama nueva es donde empezamos a trabajar, a crear archivos y cambiar en el código.

# Crear un archivo nuevo de Python y poner algo de código.

* Ejecutaremos el siguiente comando para crear un archivo nuevo de Python:

```console
kasparov@kasparov-MS-7B58:~/Escritorio/github/uso_git$ touch tutorial_1.py
```

* Vamos a abrir el archivo recién creado usando Visual Studio Code y agregaremos un poco de cógido Python:

```
def hello_world(name):
    print(f'Hello world {name}')

hello_world('Víctor') # aquí vamos a llamar a nuestra función
```

* Para probar, vamos a ejecutar el código desde la terminal y si todo está bien, deberíamos ver:

<img src="/figures_readme/hello_world.png" alt="fishy" class="bg-primary" width="550px" align="center"/>

* En este ejemplo que ya funciona, vemos que estaríamos listos con nuestro <span style="color: blue; font-family: Babas; font-size: 1.12em;">feature_1</span>.

# Uso de Source Control en Visual Studio Code (VSC).

* <span style="color: blue; font-family: Babas; font-size: 1.12em;">Source Control</span> en VSC está integrado y se conecta con <span style="color: blue; font-family: Babas; font-size: 1.12em;">Git</span>.

* En VSC, vamos a abrir una carpeta. Desde VSC nos vamos a nuestro repositorio que está en el escritorio, en la carpeta que llamamos: <span style="color: blue; font-family: Babas; font-size: 1.12em;">github</span>, y llegamos a nuestro repositorio: <span style="color: blue; font-family: Babas; font-size: 1.12em;">uso_git</span>.

* Y abrimos nuestro repositorio <span style="color: blue; font-family: Babas; font-size: 1.12em;">uso_git</span>.

* Podemos observar en VSC todos los archivos que están en nuestro repositorio.

* Pero, también a mano izquierda, podemos observar una pestaña que se llama <span style="color: blue; font-family: Babas; font-size: 1.12em;">Source Control</span>, en donde se muestran todos los cambios que hemos ido realizando. Debería decir que solamente hemos cambiado <span style="color: blue; font-family: Babas; font-size: 1.12em;">tutorial_1.py</span>.

* Otra cosa importante que observar es que al fondo de VSC nos dice en qué rama nos encontramos, en este caso, <span style="color: blue; font-family: Babas; font-size: 1.12em;">feature_1</span>.