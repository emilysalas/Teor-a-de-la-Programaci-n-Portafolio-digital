# 📊 Estructuras de Datos: Arreglos en C

Las **estructuras de datos** permiten organizar y almacenar información de manera eficiente. En el lenguaje **C**, los **arreglos (arrays)** son una de las estructuras más fundamentales y utilizadas para manejar conjuntos de datos relacionados [22].

---

## 🔹 ¿Qué es un Arreglo?

Un **arreglo** es una colección **finita y homogénea** de elementos del mismo tipo de dato, almacenados en **posiciones de memoria contiguas**.  
Cada elemento se identifica mediante un **índice numérico**, el cual **siempre inicia en cero** [22].

📌 En C, al declarar un arreglo:
- Se reserva un **bloque de memoria fijo** [23].
- Su tamaño debe conocerse **en tiempo de compilación** o gestionarse mediante **memoria dinámica** para evitar errores de desbordamiento (*overflow*) [23].

---

## 📐 Arreglos Unidimensionales (Vectores)

Los **arreglos unidimensionales**, también llamados **vectores**, permiten almacenar datos en una sola dimensión y acceder a ellos usando un único índice [22][23].

### 🔑 Características principales

| Característica | Descripción |
|---------------|-------------|
| 📦 Tipo de datos | Todos los elementos son del mismo tipo |
| 🔢 Índice | Inicia en 0 |
| 🧠 Memoria | Contigua y de tamaño fijo |
| ⚡ Acceso | Directo y rápido mediante el índice |

---

## 🧮 Arreglos Bidimensionales y Multidimensionales

### 🔷 Arreglos Bidimensionales

Los **arreglos bidimensionales** se representan como **tablas de filas y columnas** [24].  
Para acceder a un elemento se utilizan **dos índices** [24]:  
- el primero indica la **fila**.  
- el segundo indica la **columna**.

### 🔷 Arreglos Multidimensionales (Tridimensionales)

C también permite crear **arreglos de más de dos dimensiones**, conocidos como **arreglos multidimensionales** [25].

**📌 Consideraciones importantes:**
- Son conceptualmente más complejos de visualizar [24][25].
- Internamente, la memoria se organiza de forma **lineal**, elemento tras elemento [25].
- Se utilizan principalmente en problemas matemáticos, científicos o de simulación [25].

---

## 🔤 Cadenas de Caracteres (Strings)

En el lenguaje C **no existe un tipo de dato `String` nativo** [24].  
Las cadenas de texto se manejan como **arreglos unidimensionales de tipo `char`** [24][26].

### ⚠️ Característica clave

Toda cadena en C **debe finalizar con el carácter nulo `\0`**, el cual indica el final del texto [26].

❗ Si este carácter se omite [24]:
- Las funciones continuarán leyendo memoria de forma indefinida.
- Se pueden producir **errores de ejecución** o comportamientos inesperados.

---

## 📚 Librería `<string.h>`

Para facilitar el manejo de cadenas, C ofrece la librería estándar **`<string.h>`**, que incluye funciones optimizadas para trabajar con texto [27].

### 🛠️ Funciones más utilizadas

| Función | Descripción |
|-------|-------------|
| `strlen()` | Obtiene la longitud de una cadena |
| `strcpy()` | Copia una cadena en otra |
| `strcat()` | Concatena dos cadenas |
| `strcmp()` | Compara dos cadenas |

📌 Es importante destacar que los operadores relacionales como `==` **no funcionan correctamente con cadenas**, por lo que `strcmp()` es la forma adecuada de compararlas [27].

---
💡Desea regresar? [🔙](Unidad3.md)
