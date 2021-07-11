Habcat Event Framework
=======================

Documentación del *framework* de habcat orientado a eventos.


Contenido
*********

Para emplear el framework siga los siguientes pasos.

- Instalación del framework
- Desarrollo
   + Teoría
   + Entorno de desarrollo
   + Desarrollo de componentes


Instalación del framework
*************************

Nos conectamos vía *ssh* a la *Raspberry pi* y descargamos e instalamos el framework
mediante los siguientes comandos:

.. code-block:: console

   wget https://raw.githubusercontent.com/alpeza/habcatpi/main/install.sh
   chmod +x install.sh
   ./install.sh


Una vez realizada la instalación la *Rpi* se reiniciará. Nos volvemos
a conectar vía ssh y actualizamos el framework con los últimos 
componentes.

.. code-block:: console

   habcat update --uall

Listamos los componentes de los que disponemos

.. code-block:: console

   habcat components

Listamos los dispositivos de los que disponemos

.. code-block:: console

   habcat devices


.. toctree::
   :maxdepth: 4

   all-about-me
   hola/index

.. toctree::
   :caption: Instalación del framework

   all-about-me

.. toctree::
   :caption: Framework Python

   all-about-me

