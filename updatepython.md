# Actualización de Python

Es altamente recomendable tener actulizado el Python en su versión 3.8

Primero revisamos que versión tenemos. En una consola escribimos

~~~
python3 --version
~~~

Si obtenemos un versión menor a 3.8, simplemente ponemos en sistemas basados en Debian (xUbuntu)

~~~
sudo apt-get install python3.8
~~~

En principio nos preguntar sí queremos fijar a python3.8 como nuestra versión por defecto (esto dependerá de los intereses particulares).
Checamos la versión de Python que tenemos

~~~
python3 --version
~~~

Obtendremos la versión 3.8, si la fijamos por defecto. En caso contrario, escribimos 

~~~
python3.8 --version
~~~
Actulizamos PIP con
~~~
sudo apt-get install python3-pip
sudo pip3 install --upgrade pip
~~~
