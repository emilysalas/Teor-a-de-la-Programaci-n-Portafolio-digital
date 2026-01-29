## 🧩 Modularidad y Funciones en C

---

### 🧠 ¿Qué es la Modularidad?

La **modularidad** es una técnica fundamental en el diseño de software que consiste en dividir un sistema complejo en partes más pequeñas llamadas **módulos**, los cuales son independientes entre sí y cumplen una función específica [17].  

En el lenguaje **C**, esta idea se aplica principalmente mediante el uso de **funciones** y la organización del código en **archivos fuente (.c)** y **archivos de cabecera (.h)**. Gracias a esta estructura, es posible manejar programas grandes de forma ordenada, reduciendo la complejidad y mejorando la comprensión del código [18].

---

### 🔧 El Rol de las Funciones

Las **funciones** representan los bloques básicos de la modularidad en C. Cada función recibe datos de entrada, realiza un procesamiento específico y puede devolver un resultado [19].  

Su principal ventaja es que permiten **encapsular tareas**, lo que evita la duplicación de instrucciones dentro del programa. De esta manera, una función puede reutilizarse tantas veces como sea necesario sin reescribir su lógica interna, facilitando el **mantenimiento**, la **lectura** y la **organización** del código [20].

---

### 🔁 Envío de Parámetros: Valor y Referencia

El **envío de parámetros** es el mecanismo que permite a una función recibir información para operar. En el lenguaje C existen dos formas principales:

🔹 **Paso por valor**  
En este método, la función recibe una **copia del dato** almacenada en la pila de memoria. Esto garantiza que la variable original no se modifique de forma accidental, aportando mayor seguridad al programa [21].

🔹 **Paso por referencia**  
Se implementa mediante **punteros**, enviando la **dirección de memoria** de la variable. Esto permite que la función modifique directamente el valor original, siendo una opción más eficiente cuando se trabaja con grandes volúmenes de datos o estructuras complejas [18].

---

## 📊 Tabla Comparativa: Paso por Valor vs Paso por Referencia en C

| Característica | 🔹 Paso por Valor | 🔹 Paso por Referencia |
|:--------------|:-----------------|:----------------------|
| ¿Qué se envía a la función? | Una **copia del dato** | La **dirección de memoria** del dato |
| ¿Se modifica la variable original? | ❌ No | ✅ Sí |
| Uso de punteros | ❌ No | ✅ Sí |
| Seguridad de los datos | 🔒 Alta | ⚠️ Media |
| Eficiencia con datos grandes | ❌ Menor | ✅ Mayor |
| Aplicación común | Cálculos simples | Manipulación directa de datos |

---

## 💻 Ejemplos Prácticos en Lenguaje C

### 🔢 Ejemplo 1: Paso por Valor

La función recibe un número y muestra su doble.
En este caso, la función recibe una **copia** de la variable, por lo que el valor original no cambia.

<img width="483" height="466" alt="image" src="https://github.com/user-attachments/assets/c816ab3d-f323-4d37-bf1e-59bfb91ead44" />

**📌 Resultado:**
El valor original de x no se modifica, sigue siendo 4, ya que solo se modificó la copia.

<img width="220" height="58" alt="image" src="https://github.com/user-attachments/assets/67fe69b7-efcc-490c-9f62-89470fceeafd" />

### 🔢 Ejemplo 2: Paso por Referencia 
Aquí se envía la dirección de memoria, permitiendo modificar directamente la variable original.

<img width="712" height="460" alt="image" src="https://github.com/user-attachments/assets/06df5cd8-3a5f-45e9-bada-44900679e175" />

**📌 Resultado:**
El valor de numero ahora es 15, porque la función accedió directamente a la variable original.

<img width="317" height="50" alt="image" src="https://github.com/user-attachments/assets/168318ca-c7be-4447-925c-ac5bfb19e9a3" />

---

### ⚖️ Ventajas y Desventajas de la Modularidad

### ✅ Ventajas de la Modularidad

| 🔹 Aspecto | 📌 Descripción |
|-----------|---------------|
| 🔁 **Reutilización de código** | Los módulos diseñados de forma general pueden emplearse en distintos proyectos sin cambios significativos, optimizando el tiempo de desarrollo [17]. |
| 🛠️ **Facilidad de mantenimiento** | Al estar el código dividido en módulos, los errores se pueden localizar y corregir en un solo componente sin afectar al resto del programa [19]. |
| 👥 **Desarrollo paralelo** | Diferentes programadores pueden trabajar en módulos independientes de manera simultánea, reduciendo el tiempo total de desarrollo del software [20]. |

---

### ⚠️ Desventajas de la Modularidad

| 🔹 Aspecto | 📌 Descripción |
|-----------|---------------|
| ⏱️ **Sobrecarga de ejecución** | El uso frecuente de funciones y el paso de parámetros puede generar un pequeño retardo en comparación con un código completamente lineal [21]. |
| 🧩 **Mayor complejidad inicial** | Se requiere una planificación más detallada para definir correctamente las interfaces y la estructura de los módulos antes de comenzar la programación [17]. |

---
💡Desea regresar? [🔙](Unidad3.md)
