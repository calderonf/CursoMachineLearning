# CursoMachineLearning
Repositorio Oficial del curso de Machine learning y del material que vamos a trabajar. 

## Semana 1
Introducción al curso: https://web.microsoftstream.com/video/4b301efd-3e6c-4145-a1ee-9f311fbd94a4

Definiciones y glosario del curso: https://web.microsoftstream.com/video/ccc7e6aa-a973-4213-89cf-612278d1e38c

## Semana 2
Repaso de Probabilidad :https://www.youtube.com/watch?v=8tDOF1f2i8M

Preguntas e instalación de anaconda: https://web.microsoftstream.com/video/e08f6545-4415-4d2d-949a-f12f80946d24

Introducción al python Lista de reproducción: 
https://www.youtube.com/playlist?list=PLar_Hmbx3oKp40i8_mHnbiK_Nw-GVru5F
 
## Semana 3
La descripción del taller la encuentran en el siguiente video: https://web.microsoftstream.com/video/8e0c7b4a-5994-4edb-9548-fbb780570da3.

Clase Viernes teórica Semana 3:  https://www.youtube.com/watch?v=yJ8J0bfgXrI

La presentación y la tabla de excel de anexo lo encuentran en la sección de archivos.  
Clase práctica: https://web.microsoftstream.com/video/da3eaa73-195a-4b65-9e61-e8449a340704
 
## Semana 4
Segunda parte de regresión lineal univariada: https://www.youtube.com/watch?v=XvHlS_mFGWQ

Muestra del código base en google colab, https://colab.research.google.com/drive/1NqTz8dU4F29i4yOD9bffwF4ppYDZLcZ4?usp=sharing

Videos de clase de dudas semana 4:

https://www.dropbox.com/s/z4ojx7czcypctn3/SolucionDudas_AI_ClaseSemana4_1.mp4?dl=0

https://www.dropbox.com/s/wa8vi54hyf048e2/SolucionDudas_AI_ClaseSemana4_2.mp4?dl=0

Tercera parte regresión lineal: https://youtu.be/kiic4zuHDik
 
## Semana 5

Cuarta parte regresión lineal: https://www.youtube.com/watch?v=t_U-cqpKmag

Regresión logística:  https://www.youtube.com/watch?v=1aHT2sDftYM&feature=youtu.be
 
## Semana 6

K-Means, Parte 1: https://youtu.be/duCdeTh-4yc

Clasificación Multiclase: https://youtu.be/L3jQXeNIXMI

## Semana 7

K-Means, Parte 2:https://www.youtube.com/watch?v=SO2_am1OeCI 

KNN: https://www.youtube.com/watch?v=HHsA2ZqIa2M

# Instalación de anaconda python:

## Windows:
En windows primero se debe descargar el ejecutable, 
64-Bit Graphical Installer (466 MB)
simplemente dar doble click con las opciones por defecto, para no tener problemas con otras versiones de python en su sistema puede dejar sin seleccionar la casilla de verificación de instalar en el PATH de windows. es decir las opciones por defecto.
Para abrir spyder, jupyer o JupyterLab simplemente basta con abrir anaconda navigator usando el menú de inicio. 
Si quiere instalar cualquier paquete basta con buscar en el menú de inicio por la terminal de Anaconda Prompt. una vez abierto se sabe que está en la terminal adecuada al  ver que esta inicia con un (base).
Instalación de módulos
La instalación de módulos puede realizarse con pip o con conda, para este curso vamos a usar por ahora scikit-learn, puede instalarlo escribiendo en la terminal :
 pip install -U scikit-learn

## MacOS:
En MacOS primero se debe descargar el ejecutable:
64-Bit Graphical Installer (462 MB)
simplemente dar doble click con las opciones por defecto, 
Para abrir spyder, jupyer o JupyterLab simplemente basta con abrir anaconda navigator buscando en su carpeta de aplicaciones, la ruta de instalación por defecto está en 
/Users/usuario/opt/anaconda3
Si quiere instalar cualquier paquete basta con abrir su terminal, una vez abierta se sabe que está en la terminal adecuada al  ver que esta inicia con un (base).
Instalación de módulos
La instalación de módulos puede realizarse con pip o con conda, para este curso vamos a usar por ahora scikit-learn, puede instalarlo escribiendo en la terminal :
pip install -U scikit-learn

## GNU/Linux:
En el poderoso Linux, en especial las distros basadas en debian  primero se debe descargar el archivo ejecutable: puede hacerlo abriendo una terminal y escribiendo:
$ wget https://repo.anaconda.com/archive/Anaconda3-2020.07-Linux-x86_64.sh
obviamente sin el $ esto siempre denota que el comando debe ser escrito en una bash shel
Cuando termine de descargar puede ejecutar el instalador desde una terminal escribiendo:
$ bash Anaconda3-2020.07-Linux-x86_64.sh
siga las instrucciones en pantalla , primero la licencia puede saltarla oprimiendo la tecla q y luego escribiendo yes y enter.
puede usar la ruta por defecto en ([/home/usuario/anaconda3] >>>) dando enter en esta parte tal como se especifica en la ayuda:
  - Press ENTER to confirm the location
  - Press CTRL-C to abort the installation
  - Or specify a different location below
Al final puede seleccionar en 
installation finished.
Do you wish the installer to initialize Anaconda3
by running conda init? [yes|no]
dando simplemente enter, esto no inicializará el entorno de conda al puede hacerlo luego ejecutando el comando
si escribe yes esto inicializará el archivo .basrc en su carpeta home para que cargue las variables de entorno necesarias para que se ejecute bien el entorno de anaconda 
$ /Users/usuario/opt/anaconda3/bin/conda init
y reiniciando la consola. 
Puede abrir Anaconda navigator abriendo en una nnueva consola:
(base) usuario@usuario:~$ anaconda-navigator
Si quiere instalar cualquier paquete basta con abrir su terminal, una vez abierta se sabe que está en la terminal adecuada al  ver que esta inicia con un (base).
Instalación de módulos
La instalación de módulos puede realizarse con pip o con conda, para este curso vamos a usar por ahora scikit-learn, puede instalarlo escribiendo en la terminal :
pip install -U scikit-learn
 

