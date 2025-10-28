# 🖥️ Programación en Lenguajes de Alto Nivel

---

## 💻 Codificación
- Convertir un **algoritmo a código** no es solo traducir palabras; incluye:
  - Declaración de **variables y constantes**  
  - Inclusión de **librerías**  
- El código resultante se almacena en un **programa fuente**.  
  - En C, archivos con extensión `.c` → `nombre_archivo.c`  
- El **programa inicia siempre** desde la función `main()`.  
- Después, se **compila** para generar un programa ejecutable.

---

## 📚 Librerías o Bibliotecas
- Archivos que contienen **código reutilizable** para operaciones frecuentes.  
- Se incluyen en el programa con `#include <libreria.h>`  
- Librerías comunes en C:
  ```c
  #include <stdio.h>
  #include <stdlib.h>
  #include <string.h>
  #include <math.h>
  #include <time.h>
stdio.h es fundamental: contiene funciones y tipos para entrada y salida de datos.

---

## 🧮 Tipos de Datos Simples

Determinan la cantidad de memoria y el tipo de información que puede almacenar:

int → enteros

float → números con decimales

char → un solo carácter

string → cadena de caracteres

---

## 📊 Variables y Constantes

| Tipo | Qué es | Ejemplos | Declaración |
|:----|:------|:--------|:----------|
| **Variable** | Almacena valores que pueden cambiar durante la ejecución | int a = 5; float acumulador = 0; char opcion='S'; | Declaración: tipoDato nombre; |
| **Constante** | Almacena valores que no cambian	const float | IVA15 = 0.15; const char UNIVERSIDAD[] = "ESPOCH"; | Inicialización: tipoDato nombre = valor; |

---

## 🔄 Asignación

Se usa el signo = para asignar valores:

a = a + 5;
sueldo = 450;
estadoCivil = 'D';


### 📈Incremento y decremento📉:

**b++**;  // b = b + 1

**++b**;  // b = b + 1

**b--**;  // b = b - 1

**--b**;  // b = b - 1

---

## ⬅️ Entrada de Datos

Se realiza con **scanf()** en C:

;scanf("%i", &variable);

**%i** → formato que indica el tipo de dato

&variable → dirección de memoria donde se almacenará el dato

---

## ➡️ Salida de Datos

Se realiza con **printf()** en C:

printf("La suma es %i", suma);

"La suma es " → mensaje

**%i** → máscara de salida

suma → variable que se mostrará

---

<img width="410" height="253" alt="image" src="https://github.com/user-attachments/assets/06b80c6f-e3a8-4fc6-9030-9866ba374dcd" />

---

💡Desea regresar? [🔙](Tema1.md)
