# T2.4Fase1APE5.-Creaci-n-Lectura-y-Escritura-de-Ficheros
# Práctica APE 5: Manejo de Ficheros en Java

Este repositorio contiene la solución a los ejercicios prácticos de la **APE 5 (Primera Parte)**, enfocados en las operaciones básicas de manipulación, escritura y eliminación de archivos de texto utilizando el lenguaje de programación Java[cite: 1].

---

## 🛠️ Contenido de la Práctica

El proyecto se encuentra estructurado en tres programas independientes que resuelven los siguientes requerimientos:

* **Ejercicio 1: Crear un fichero en Java**[cite: 1]
  * **Descripción:** Programa que crea un nuevo archivo de texto llamado `curso.txt` utilizando la clase `File` y el método `createNewFile()`[cite: 1]. Incluye control de errores con `try-catch` y validación de existencia previa[cite: 1].
* **Ejercicio 2: Escribir información en un fichero**[cite: 1]
  * **Descripción:** Permite ingresar un mensaje por teclado mediante la clase `Scanner` y lo almacena en un archivo existente llamado `estudiantes.txt`[cite: 1]. Utiliza `FileWriter` con el parámetro `true` para conservar la información anterior y agregar el nuevo texto al final[cite: 1].
* **Ejercicio 3: Eliminar un fichero en Java**[cite: 1]
  * **Descripción:** Programa encargado de eliminar el archivo de texto `estudiantes.txt` de forma segura mediante el método `delete()`, validando con estructuras condicionales (`if-else`) si la operación se completó con éxito[cite: 1].

---

## 📂 Estructura del Proyecto

```text
APE5_ManejoDeArchivos/
│
├── .gitignore
├── README.md
└── ejercicios/
   ├── Ejercicio1CrearFichero.java
            ├── Ejercicio2EscribirFichero.java
            └── Ejercicio3EliminarFichero.java
