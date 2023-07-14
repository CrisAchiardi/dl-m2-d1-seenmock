# Desafío Latam
# Módulo 02 - Desafío 01
* Construir un mockup de una web de mensajería instantánea.
* Utilizar solo flexbox para el layout.
* El diseño debe tener una barra lateral y una sección de contenido.

<img width="1179" alt="Captura de pantalla 2023-07-14 a la(s) 10 28 20" src="https://github.com/CrisAchiardi/dl-m2-d1-seenmock/assets/135924451/5e73545f-83e2-433b-8c67-4a2a6f21a7cb">


# Cómo lo hice
Dentro de un "main" cree 2 "section", una para una barra lateral y otra para el contenido. El contenido incluye un logo, un título y un párrafo. En la barra lateral hay 2 elementos principales; un contacto activo con íconos y un botón de iniciar chat. Y un listado de contactos recientes con scroll independiente utilizando solo CSS.

# Nuevos Aprendizajes
* Fijar contenido con position: fixed;
* Usar los atributos top y bottom para fijar la posición del contenido.
* Usar overflow-y: scroll; para que el contenido excedente sea escroleable en el eje vertical.
* Usar el valor inherit para aplicar el tamaño del padre al contenido escroleable, para lograr que mantenga el diseño y el responsive.
* Usar el atributo flex: 1 1; para que la section contenido ocupe todo el espacio disponible.

# Code Snippets

* Sidebar - barra lateral</br><img width="400" alt="sidebar" src="https://github.com/CrisAchiardi/dl-m2-d1-seenmock/assets/135924451/921ad057-d746-4a35-aaae-44976ac08ee3"></br></br></br>
* Contacts - elemento con contactos scroleables</br><img width="400" alt="sidebar" src="https://github.com/CrisAchiardi/dl-m2-d1-seenmock/assets/135924451/edab4e4e-d635-4af1-aa9b-1c5552962bae"></br></br></br>
* Contents - contenido</br><img width="400" alt="sidebar" src="https://github.com/CrisAchiardi/dl-m2-d1-seenmock/assets/135924451/0be1252f-57b1-44ec-8b2d-646e3992639f">
