# Proyecto: ```Aplicaciones para el gimnasio de la UFRO```

El proyecto que a continuación se presenta fue diseñado y creado durante la asignatura de Ingeniería de Software, y su proceso de diseño se basó en la metodología tradicional iterativa. Su intención es contribuir a la Universidad de La Frontera (UFRO) mediante la implementación de tecnología en el gimnasio de la institución. De esta manera, se busca permitir a los socios del gimnasio inscribirse en clases impartidas por profesionales y gestionadas por un administrador.


### Stack de tecnologías.
<p align="center">
  <img src="./IMG/StackTec.PNG" alt="Descripción de la imagen">
</p>

En cuanto a las tecnologías ocupadas para el desarrollo del proyecto, se pueden observar en la imagen anterior. En primer lugar, se diseñó la plataforma de escritorio ocupando WindowBuilder y Java, haciendo uso de la biblioteca Javax.Swing. Posteriormente, debido a requerimientos de la asignatura, se migró la versión de escritorio a una plataforma web, para lo cual se emplearon frameworks de Java como SpringMVC, con el fin de separar la lógica y los modelos de la vista, e Hibernate, para conectarse a la base de datos.  
#### Cabe destacar que la plataforma web es un prototipo y no una versión comercial, y que su versión ha sido actualizada en el año 2023.
Si algún reclutador está interesado en obtener más detalles o visualizar las aplicaciones en funcionamiento, puede ponerse en contacto conmigo a través de mi correo 
electrónico: manriquezfernando.ns@gmail.com

### ```Login's``` de las aplicaciones.

<p align="center">
  <img src="./IMG/LoginWEB.PNG" alt="Descripción de la imagen">
</p>
<p align="center">
  <img src="./IMG/LoginDesktop.PNG" alt="Descripción de la imagen">
</p>

#### Es importante mencionar que ambas aplicaciones cuentan con tres tipos de cuenta distintos que heredan de una clase común denominada ```Usuario```. Debido a esto, las siguientes secciones se organizarán en función de estos tres tipos de cuenta para brindar una mejor comprensión de las funcionalidades y características de cada uno de ellos.
## Tipo de cuenta: ```Administrador```
El Administrador es fundamental en la gestión del sistema, ya que su principal función es agregar clases al mismo. Para ello, resulta indispensable que hayan Profesionales disponibles en el sistema, ya que son ellos quienes se encargarán de impartir dichas clases en el gimnasio.

### Vista gráfica ```Inicio```
<p align="center">
  <img src="./IMG/W-InicioAdmin.PNG" alt="Descripción de la imagen">
</p>
<p align="center">
  <img src="./IMG/D-InicioAdmin.PNG" alt="Descripción de la imagen">
</p>

### Vista gráfica ```Agregar clase```
<p align="center">
  <img src="./IMG/W-RCAdmin.PNG" alt="Descripción de la imagen">
</p>
<p align="center">
  <img src="./IMG/D-RCAdmin.PNG" alt="Descripción de la imagen">
</p>

## Tipo de cuenta: ```Socio```
En cuanto al tipo de cuenta ```Socio```, cabe destacar que se trata de una opción que permite a las personas inscribirse en las clases que han sido previamente registradas por el ```Administrador``` y que están siendo impartidas por un ```Profesional```. De esta manera, los socios pueden acceder a una amplia variedad de clases y actividades físicas dentro del gimnasio, adaptándose a sus requerimientos y preferencias.

### Vista gráfica ```Reservar inscripción```
<p align="center">
  <img src="./IMG/W-ReservarSocio.PNG" alt="Descripción de la imagen">
</p>
<p align="center">
  <img src="./IMG/D-ReservarSocio.PNG" alt="Descripción de la imagen">
</p>

### Vista gráfica ```Transferencia```
<p align="center">
  <img src="./IMG/W-Transferencia.PNG" alt="Descripción de la imagen">
</p>
<p align="center">
  <img src="./IMG/D-Transferencia.PNG" alt="Descripción de la imagen">
</p>

## Tipo de cuenta: ```Profesional```
Como ya se ha mencionado en secciones anteriores, el ```Profesional``` es la persona encargada de impartir las clases. Por lo tanto, aquellos usuarios que poseen una cuenta de tipo ```Profesional``` tienen la capacidad de visualizar quiénes se han registrado en sus clases.

### Vista gráfica ```Clases asignadas```
<p align="center">
  <img src="./IMG/W-Profesional.PNG" alt="Descripción de la imagen">
</p>
<p align="center">
  <img src="./IMG/D-Profesional.PNG" alt="Descripción de la imagen">
</p>