# 🧩 Tema 2: Estructuras Repetitivas
-------

# 🧠 ¿Qué son las Estructuras Repetitivas?

Las **estructuras repetitivas** —también conocidas como *bucles* o *iteraciones*— permiten **ejecutar un bloque de instrucciones múltiples veces**, ya sea mientras una condición se cumpla o durante un número específico de repeticiones [12].

Son esenciales para automatizar tareas y evitar código redundante.  
Según plataformas educativas, estos bucles permiten **repetir acciones de forma controlada y eficiente** [12][13].

---

# 🚀 Tipos principales de estructuras repetitivas

| 🔢 Nº | 🔁 Estructura | 💡 Uso principal |
|:---:|:------------|:-----------------------------|
| 1️⃣ | **while** | Repeticiones indeterminadas según condición |
| 2️⃣ | **do…while** | Acciones que deben ejecutarse al menos una vez |
| 3️⃣ | **for** | Repeticiones controladas o con contador |

---

# 🔵 1. **Bucle `while`**

El ciclo **while** ejecuta instrucciones **mientras la condición sea verdadera** [12].  
La condición se evalúa **antes** del bloque, por lo que el ciclo puede no ejecutarse nunca [14].

### 📌 Útil cuando:
- No se conoce la cantidad de repeticiones  
- Se depende de la entrada del usuario  
- Se espera que la condición cambie durante el proceso  

### 📝 Características:
- Evalúa la condición **antes**  
- Ideal para procesos condicionales variables  

> El *while* es fundamental en iteraciones dependientes de condiciones dinámicas [12].

📝 **Sintaxis**

```c
while (condición) { 

instrucciones…

}
```

📚 **Diagrama de flujo**

<img width="217" height="335" alt="image" src="https://github.com/user-attachments/assets/d3bf848e-806e-4d7a-8a8f-0345bdc7fcd3" />

---

# 🔵 2. **Bucle `do…while`**

Este bucle garantiza que el código se ejecute **al menos una vez**, ya que la condición se evalúa **después** del bloque [12][13].

### 📌 Útil en:
- Menús interactivos  
- Solicitud obligatoria de datos  
- Procesos que requieren una ejecución inicial  

### 📝 Características:
- La condición se evalúa **al final**  
- Común en interfaces de usuario y validaciones  

> Muy utilizado cuando se requiere ejecución previa antes de verificar la condición [12][14].

📝 **Sintaxis**

```c
do {

instrucciones…

 } while (condición);

```

📚 **Diagrama de flujo**

<img width="228" height="337" alt="image" src="https://github.com/user-attachments/assets/7d35a4a2-0a99-402c-a065-ddf9b43ca943" />

---

# 🔵 3. **Bucle `for`**

El bucle **for** se usa cuando se conoce de antemano la cantidad de repeticiones [13].  
Permite declarar inicialización, condición e incremento en una sola línea [15].

### 📌 Útil para:
- Recorrer rangos numéricos  
- Recorrer arreglos o listas  
- Contar iteraciones exactas  

### 📝 Características:
- Sintaxis compacta y ordenada  
- Muy usado en algoritmos matemáticos  
- Control preciso del número de repeticiones  

> Su estructura clara lo vuelve uno de los más usados en programación [12][14][16].

📝 **Sintaxis**

```c
for (inicialización; condición; inc/dec) {

instrucciones...

 }

```

📚 **Diagrama de flujo**

<img width="188" height="338" alt="image" src="https://github.com/user-attachments/assets/134dbfdb-876b-4138-9d94-72d20112c8ba" />

---

# ⭐ Comparación general

| 🔁 Bucle | 🧩 Evalúa la condición | 📘 Uso recomendado |
|---------|------------------------|----------------------------|
| **while** | Antes | Repeticiones inciertas |
| **do…while** | Después | Menús, lecturas iniciales |
| **for** | Antes | Repeticiones conocidas |

-----

# Ejemplos

<details>
<summary>🔍 Ejemplo usando Do - While (🖱️da click )</summary>

--------

**Problema:** Dado un dos números enteros (numerador y denominador), el algoritmo se encarga de verificar que el denominador sea diferente de 0, y después procede a realizar la división.

**Código en Lenguaje (C):**

<img width="489" height="544" alt="image" src="https://github.com/user-attachments/assets/700d8bc1-c2eb-4e96-8c7f-6f6cddce0502" />

*Verificación de la ejecución*

<img width="302" height="89" alt="image" src="https://github.com/user-attachments/assets/11982fe3-2aa8-44d5-a9b2-a4da6fedaacb" />

<img width="297" height="181" alt="image" src="https://github.com/user-attachments/assets/52c6f1b0-7221-49ac-8947-6d523429f2c5" />

</details>


---

💡Desea regresar? [🔙](Unidad2.md)

