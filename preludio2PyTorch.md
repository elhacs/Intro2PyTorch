# Predulio a PyTorch

## Instalación de Python

#### En Windows: 
La mejor opción es **Anaconda** ya que incluye al intérprete de Python3, Jupyter y al manejador de paquetes Conda.

Dependiendo de la arquitectura de nuestra maquina, debemos elegir al instalador correspondiente

* [64-bits](https://repo.anaconda.com/archive/Anaconda3-2020.11-Windows-x86_64.exe)
* [32-bits](https://repo.anaconda.com/archive/Anaconda3-2020.11-Windows-x86.exe)

Como cualquier programa de Windows, la instalación se reduce a Aceptar, Siguiente, Siguiente y Finalizar. Sin embargo, en uno de los pasos nos pregunta, si queremos que Anaconda3 se agregue a *PATH environment variable* y marcamos la casilla. Además, si tenemos algún otro intérprete de Python, marcaremos a Anaconda3 como el intérprete por defecto.

Al finalizar, nos preguntará si queremos descargar PyCharm (IDE de Python), de momento no será necesario.

#### En MacOS:

Es algo similar al caso de Windows, lo único que cambia son los instaladores:

* [64-bits](https://repo.anaconda.com/archive/Anaconda3-2020.11-MacOSX-x86_64.pkg)

#### En GNU/Linux:

En este caso, si usamos una distribución basada en Debian/Ubuntu, el sistema ya tiene por defecto al intéprete de Python3, para comprobar que todo este correcto, tecleamos en una terminal 
~~~
python3 --version
~~~
Es importante el 3 después de Python debido a que algunas distribuciones aún incluyen al interprete en su versión 2 que **No** utilizaremos (y cada vez está más en desuso).

Solo debemos instalar el manejador de paquetes *PIP* para eso en una terminal tecleamos:
~~~
sudo apt-get install python3-pip
~~~

Una vez instalado el manejador debemos instalar las dependencias necesarias para trabajar, una vez más en una terminal teclamos

~~~
sudo pip3 install torch torchvision torchaudio matplotlib numpy utils jupyter
~~~

Una vez terminado el proceso de instalación, corroboramos que todo funciona bien tecleando en la terminal

~~~
jupyter notebook
~~~

Y nos debería abrir nuestro navegador web una página como la siguiente.
![Jupyter](https://github.com/elhacs/Intro2PyTorch/blob/main/home.png)

Eso es lo que necesitaremos para iniciar a trabajar.

