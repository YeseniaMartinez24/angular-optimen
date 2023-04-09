# Integradora II

## Contenido
<details>
  <summary>Tabla contenido</summary>
  <ol>
    <li>
      <a href="#acerca-del-proyecto">Acerca del Proyecto</a>
      <ul>
        <li><a href="#descripción">Descripción</a></li>
        <li><a href="#objetivos">Objetivos</a></li>
        <li><a href="#organigrama">Organigrama</a></li>
        <li><a href="#diagrama-gantt">Diagrama Gantt</a></li>
      </ul>
    </li>
    <li>
      <a href="#análisis-de-la-solución">Análisis de la Solución</a>
      <ul>
        <li><a href="#requerimientos">Requerimientos</a></li>
        <li><a href="#diagrama-casos-de-uso">Diagrama de Casos de Uso</a></li>
      </ul>
    </li>
    <li>
      <a href="#diseño-de-la-solución">Diseño de la Solución</a>
      <ul>
        <li><a href="#modelo-relacional">Modelo Relacional</a></li>
        <li><a href="#diagrama-de-clases">Diagrama de Clases</a></li>
        <li><a href="#diagrama-de-componentes">Diagrama de Componentes</a></li>
      </ul>
    </li>    
    <li>
      <a href="#implementación">Implementación</a>
      <ul>
        <li><a href="#estándares-codificación">Estándares Codificación</a></li>
        <li><a href="#arquitectura">Arquitectura</a></li>
        <li><a href="#código-fuente">Código Fuente</a></li>
      </ul>
    </li>      
    <li>
      <a href="#pruebas">Pruebas</a>
      <ul>
        <li><a href="#casos-de-prueba">Casos de prueba</a></li>
        <li><a href="#ejecución">Ejecución</a></li>
      </ul>
    </li>       
    <li><a href="#guias">Guias</a></li>
    <li><a href="#contribucion">Contribución</a></li>
    <li><a href="#licencia">licencia</a></li>
    <li><a href="#contacto">Contacto</a></li>
    <li><a href="#participantes">Participantes</a></li>
  </ol>
</details>

<!-- Acerca del proyecto -->
#### Acerca del proyecto
Requisitos.
* Internet 
* Equipo de computo 
* Tener instalado React Js
* Tener instalado Node JS
* Tener instalado Visual Studio Code 

<!-- Descripción -->
#### Descripción.
Principalmente el objetivo es el rediseño de la apariencia y la estructura de la página de oficial de Optimen S.A de C.V, con la intención de agregar nuevas características, novedosas y funcionales para el funcionamiento y la interacción del usuario. Se busca añadir la disponibilidad de dos idiomas; inglés y español y asi mismo añadir la funcionalidad de “inicio de sesión”, en donde el objetivo será crear vista especial para usuarios que actualizan el contenido como noticias o eventos. De igual manera una vista de “administrador root”(usuario raíz) el cual podrá otorgar los diferentes permisos a los usuarios registrados como creadores de contenido, así también podrá administrar estos usuarios.
* Financieros : $9000
* Tiempos: 3 meses y 21 días (25 de Enero - 14 de Abril)


<!-- Objetivos -->
#### Objetivos.
El proyecto consiste en el rediseño de la página oficial de la empresa Optimen S.A de C.V. para incluir nuevas funcionalidades que brinden información actualizada sobre la empresa y sus avances en TI. Se busca lograr un sitio web altamente eficiente, con una rápida velocidad de carga para una navegación óptima. El administrador root podrá controlar los permisos de acceso de los usuarios, mientras que los creadores de contenido podrán crear, editar, eliminar y consultar noticias y eventos. Además, las noticias y eventos se mostrarán en la página principal para mantener a los usuarios visitantes informados acerca de las últimas novedades de la empresa.

<!-- Organigrama -->
#### Organigrama.
![image](https://user-images.githubusercontent.com/114689978/230801062-b77f3be3-2947-4682-91a2-e597e14a59ab.png)


<!-- Diagrama Gantt -->
#### Diagrama Gantt.
![image](https://user-images.githubusercontent.com/114689978/230801085-b3c3eeb1-1dd4-4e30-98ea-cc5086afceae.png)


<!-- Análisis del proyecto -->
## Análisis de la Solución.
En ésta sección se indicará los artefactos generados en base a la solución.

<!-- Requerimientos -->
#### Requerimientos.
![image](https://user-images.githubusercontent.com/114689978/230801047-5201cf6a-d730-4d71-8d00-69619ff19a1a.png)


<!-- Diagrama de Casos de Uso -->
#### Diagrama Casos de Uso.
Creador de contenido
![image](https://user-images.githubusercontent.com/114689978/230800603-6aad82b3-8da4-450a-93bf-3bc535d55649.png)

Usuario visitante
![image](https://user-images.githubusercontent.com/114689978/230800671-5d1a9acd-9c09-42b1-b6be-19e5e14db51a.png)

Administrador

![image](https://user-images.githubusercontent.com/114689978/230800684-c7ac7538-7e2e-4c06-bf33-0a83363607fe.png)


<!-- Diseño del proyecto -->
## Diseño de la Solución.
En ésta sección se indicará los artefactos generados en base a la solución.

<!-- Modelo Relacional -->
#### Modelo Relacional.
Esquema de la base de datos (nombre de campo, tipo de datos, restricciones, etc)
Colección eventos      
![image](https://user-images.githubusercontent.com/114689978/230801441-5b678d3f-bb11-4a84-b2ef-fdd9a7e88503.png)

Colección noticias     
![image](https://user-images.githubusercontent.com/114689978/230801465-93270940-15f1-4c02-9ba1-c1c22552934e.png)

Colección de usuarios     
![image](https://user-images.githubusercontent.com/114689978/230801477-492b196b-0842-442b-9a66-d9ac5dacbb68.png)


<!-- Diagrama de Clases -->
#### Diagrama de Clases.
Evento 

![image](https://user-images.githubusercontent.com/114689978/230801508-4bb73b6f-295a-4a29-b977-e55b87f8bc8d.png)

Noticias 

![image](https://user-images.githubusercontent.com/114689978/230801518-fa29683e-e1c0-4b6c-9cdd-2e52077a18bf.png)


<!-- Diagrama de Componentes -->
#### Diagrama de Componentes.
Esquema de los componentes que interactúan (Modelo, Vista, Controlador, Servidor Web, Servidor de base de datos)

![image](https://user-images.githubusercontent.com/114689978/230801793-4bc4700f-82c0-4b81-b813-9c4420163a36.png)


<!-- Implementación del proyecto -->
## Implementación.
En ésta sección se describe  los artefactos generados en base a la solución.

<!-- Estándares de Codificación -->
#### Estándares Codificación.
Estándares empleados en la codificación

<!-- Arquitectura MVC y Middleware -->
#### Arquitectura.
Definir los patrones empleados y de seguridad.

<!-- Código Fuente -->
#### Código Fuente.
Código Fuente de la solución


<!-- Pruebas proyecto -->
## Pruebas.
En ésta sección se describe  los artefactos generados en base a la solución.

<!-- Casos de prueba -->
#### Casos de prueba.
Indicar los casos de prueba

<!-- Ejecución Casos de prueba -->
#### Ejecución.
Evidencia de Ejecución de Casos de prueba.


<!-- Iniciando -->
## Iniciando
Iniciando.

<!-- Requisitos -->
### Requisitos
Antes de utilizar las nuevas funcionalidades de administración de contenido del sitio web, se deben cumplir los siguientes requisitos previos:
*	Navegador web
*	Dispositivo electrónico
*	Permisos de usuario
*	Conexión a internet 
*	Edición de contenido


<!-- Instalación -->
### Instalacion
Instalación del Software


## Guias
Guias de Uso.

## Contribucion
Contribucion.

## Licencia
Licencia.

## Contacto
Contacto.

## Participantes
* [Arvizu Sotelo Fernando]()
* [Duarte Vázquez José Carlos]()
* [Espinoza Gómez Abraham Salvador]()
* [Fuentes Cabrera Itzel Alessandra]()
* [Martínez Aldavera Alma Yesenia]()
