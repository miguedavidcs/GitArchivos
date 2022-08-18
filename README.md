# Que es un control de Versiones o Control de codigo Fuente?

Es un modelo de practicas donde se puede gestionar y identificar registros de rastreo los cambios del 
codigo de software, se denomina mejor cuando un grupo de desarrolladores se dan la tarea de crear un 
projecto y organizar este projecto por una serie de ramas donde cada programador hace como un CRUD de
codigos y estos pueden ver los cambios.


## Sistemas de control de versiones locales. 

###El método de control de versiones usado por mucha gente es 
copiar los archivos  a otro directorio (quizás indicando la fecha y hora en que lo hicieron, si son 
avispados).

## Revision Control System o RCS.

###Es una implementación en software del control de versiones que automatiza 
las tareas de guardar, recuperar, registrar, identificar y mezclar versiones de archivos. RCS es útil 
para archivos que son modificados frecuentemente, por ejemplo programas informáticos, documentación, 
gráficos de procedimientos, monografías y cartas. RCS también puede ser utilizado para manejar archivos 
binarios, pero con eficacia y eficiencia reducidas. Las distintas versiones son archivadas mediante la 
ayuda de la herramienta diff.

## Sistemas de Control de Versiones Centralizados

###El siguiente gran problema con el que se encuentran las personas que necesitan colaborar con desarrolladores 
en otros sistemas. Los sistemas de Control de Versiones Centralizados (CVCS por sus siglas en inglés) fueron 
desarrollados para solucionar este problema. Estos sistemas, como CVS, Subversion y Perforce, tienen un único
servidor que contiene todos los archivos versionados y varios clientes que descargan los archivos desde ese
lugar central. Este ha sido el estándar para el control de versiones por muchos años.

## Sistemas de Control de Versiones Distribuidos

### Los sistemas de Control de Versiones Distribuidos (DVCS por sus siglas en inglés) ofrecen soluciones para los
problemas que han sido mejorados. En un DVCS (como Git, Mercurial, Bazaar o Darcs), los clientes no solo 
descargan la última copia instantánea de los archivos, sino que se replican completamente el repositorio. 

### De esta manera, si un servidor deja de funcionar y estos sistemas estaban colaborando a través de él, cualquiera 
de los repositorios disponibles en los clientes puede ser copiado al servidor con el fin de restaurarlo. Cada clon
es realmente una copia completa de todos los datos.

# SVN se basa en un sistema de control de versiones centralizado.
### Esto significa que existe un almacén central de 
datos (el repositorio) accesible a todos los usuarios. Dado que los cambios realizados no pueden ser fusionados
entre sí, el sistema evita que dos usuarios puedan editar un mismo archivo al mismo tiempo. El proceso es muy
simple, cuando uno de los usuarios accede a un archivo, el sistema lo marca automáticamente como de solo lectura
para los demás. Además, Apache Subversion ofrece la posibilidad de descargar y editar directorios individuales 
sin depender del árbol general de directorios. De esta manera, es posible asignar diferentes permisos de lectura
y escritura a los diferentes usuarios. Subversion se caracteriza también porque puede registrar directorios 
vacíos, renombrados y mudados de sitio sin pérdidas de su historia.
