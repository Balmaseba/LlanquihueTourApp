# Gestión de Colaboradores

## Autor del proyecto

* **Nombre completo:** Sebastián Alejandro Reinoso Ortega
* **Sección:** DESARROLLO ORIENTADO A OBJETOS I_001A
* **Carrera:** ANALISTA PROGRAMADOR COMPUTACIONAL
* **Sede:** Online

---

## Descripción general del sistema

Este proyecto corresponde a una actividad de la asignatura **Desarrollo Orientado a Objetos I**. Se trata de una aplicación desarrollada en **Java** que permite gestionar información de colaboradores mediante la lectura de datos almacenados en un archivo de texto.

El sistema carga los registros desde un archivo externo llamado `colaboradores.txt`, crea objetos a partir de la información leída y los almacena en una colección dinámica (`ArrayList`). Posteriormente, permite visualizar el listado completo de colaboradores y realizar búsquedas filtradas por categoría, mostrando por consola los resultados encontrados.

El objetivo principal del proyecto es aplicar conceptos de **Programación Orientada a Objetos**, incluyendo el uso de **clases, composición, encapsulamiento, colecciones dinámicas, lectura de archivos y organización modular del código en paquetes**.

---

## Estructura general del proyecto

📁 src/

├── 📁 app/              # Clase principal con el método main (`Main.java`)

├── 📁 model/            # Clases del dominio (`Contacto.java` y `Persona.java`)

├── 📁 service/          # Clase encargada de la carga, almacenamiento y búsqueda de colaboradores (`GestionContactos.java`)

└── 📄 colaboradores.txt # Archivo de texto con los datos de los colaboradores

---

## Instrucciones para ejecutar el proyecto

1. Clonar el repositorio o descargar el proyecto.

2. Abrir el proyecto en **IntelliJ IDEA** o **Apache NetBeans**.

3. Verificar que el archivo `colaboradores.txt` se encuentre en la ruta esperada por el programa para su correcta lectura.

4. Ejecutar el archivo `Main.java` ubicado en el paquete `app`.

5. El sistema cargará automáticamente los datos del archivo y mostrará por consola:

   * El listado completo de colaboradores.
   * El resultado de la búsqueda por categoría.
   * La información de los colaboradores filtrados según el criterio ingresado.

---

## Funcionalidades principales

* Carga de datos desde archivo de texto.
* Creación de objetos de tipo `Contacto` y `Persona`.
* Almacenamiento de los colaboradores en un `ArrayList`.
* Visualización completa de los registros cargados.
* Búsqueda de colaboradores por categoría.

---

## Tecnologías utilizadas

* **Java**
* **Programación Orientada a Objetos**
* **Manejo de archivos con `Scanner`**
* **Colecciones dinámicas con `ArrayList`**

---

## Repositorio GitHub

https://github.com/Balmaseba/LlanquihueTourApp

**Fecha de entrega:** 22/06/2026
