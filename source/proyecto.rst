El proyecto
===========

Descripción General
-------------------

El proyecto consiste en implementar una aplicación web que sea accedida desde
cualquier parte del mundo, la cual deberá contar con un directorio de artistas
clasificados por categoría, según el tipo de arte que practiquen. Deberá permi-
tir a los usuarios visitantes poder registrarse, por medio de Facebook o por
e-mail en su defecto para tener una mayor interacción en la aplicación, como
calificar eventos y dejar reseñas, seguir artistas y/o eventos, suscribirse
para recibir información de los temas de su interés, etc.

La aplicación debe permitir registrar nuevos artistas, cuya información debe ser
validada por un delegado en el área de comunicación de la casa de la cultura.
Se debe poder agregar notas educativas, referente a cualquier tipo cultura.

Del lado de la casa de la cultura, la aplicación debe permitir calendarizar nuevos
eventos y asignar a estos cualquiera de los artistas que esté disponible, al igual
que la reservación de alguna instalación propia que este disponible o una instala-
ción externa, con la opción de incluir la ubicación en formato de mapa. También,
deben poder consultar información estadística sobre la cantidad de eventos en un
lapso, usuarios y artistas registrados, categorías preferidas, entre otras.


Modulos
-------

Artistas:
^^^^^^^^^
En éste módulo se llevará el control de los artistas que se registrarán en el
sistema. Permitirá gestionar la información de los artistas que estarán en el
directorio de la aplicación, desde registrar y validar un artista, hasta editar
su propio perfil, borrar la cuenta, entre otras operaciones. Acá también se
abarcará la validación de los datos del artista que desee registrarse.

Usuarios:
^^^^^^^^^
En este módulo, de manera similiar al de los artistas, permitirá llevar el control
de los usuarios particulares que deseen registrarse en el sistema. Con la salvedad
de que estos tienen la alternativa de registrarse mediante su cuenta de Facebook,
desde donde se obtendrán sus datos, o en caso contrario ingresará su información
personal necesaria. Permitirá editar su perfil, comentar eventos y notas educativas
y calificar eventos.

Logística:
^^^^^^^^^^
Este módulo será uno de los más complejos por las operaciones que permitirá realizar.
Este será el módulo que estará enfocado a los eventos, acá se permitirá asignar los
artístas al evento y también se agregará toda la información relacionada. Acá se hará
la programación de eventos o el cronograma. Es decir que este módulo estará más
orientado a los responsables de manejar la aplicación en la casa de la cultura.

Recolección:
^^^^^^^^^^^^
Este módulo, como su nombre lo indica, será el encargado de la recolección de datos
estadísticos de los demás módulos, fechas, cantidades, categorías, etc. Se encargará
de consultar en la base de datos los datos correspondientes a los demás módulos y
luego pasarle los filtros adecuados para presentar la información estadística relevante
a los usuarios de casa de la cultura.
