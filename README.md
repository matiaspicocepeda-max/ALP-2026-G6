<!-- ═══════════════════════════ BANNER ═══════════════════════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:007ACC,50:C586C0,100:4EC9B0&height=220&section=header&text=Arreglos%20en%20Java&fontSize=52&fontColor=FFFFFF&fontAlignY=36&desc=ALP-2026-G6%20%E2%80%A2%20Semana%2015%20%E2%80%A2%20APE%206&descAlignY=58&descSize=18&animation=fadeIn" alt="banner" width="100%"/>
</p>

<p align="center">
  <a href="#-resumen-técnico">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3500&pause=900&color=4EC9B0&background=1E1E1E00&center=true&vCenter=true&width=720&lines=int%5B%5D+numeros+%3D+%7B14%2C+7%2C+25%2C+3%2C+18%2C+7%2C+30%7D%3B;for+(int+i+%3D+0%3B+i+%3C+numeros.length%3B+i%2B%2B)+%7B+...+%7D;double+promedio+%3D+(double)+suma+%2F+numeros.length%3B;Arrays.binarySearch(ordenado%2C+18)%3B+%2F%2F+3" alt="typing"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-OpenJDK-007ACC?style=flat-square&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/IDE-Apache%20NetBeans-1B6AC6?style=flat-square&logo=apachenetbeanside&logoColor=white" alt="NetBeans"/>
  <img src="https://img.shields.io/badge/GitHub-ALP--2026--G6-1E1E1E?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
  <img src="https://img.shields.io/badge/Ingenier%C3%ADa-de%20Software-C586C0?style=flat-square&logo=codeigniter&logoColor=white" alt="Ingeniería de Software"/>
  <img src="https://img.shields.io/badge/UTA-Universidad%20T%C3%A9cnica%20de%20Ambato-DCDCAA?style=flat-square&labelColor=1E1E1E" alt="UTA"/>
  <img src="https://img.shields.io/badge/Semana-15-4EC9B0?style=flat-square&labelColor=1E1E1E" alt="Semana 15"/>
</p>

---

<div align="center">

### 🏛️ Universidad Técnica de Ambato (UTA)
**Facultad de Ingeniería en Sistemas, Electrónica e Industrial · Carrera de Ingeniería de Software**

`Semana 15` · `Arreglos en Java (Día 1 y Día 2)` · `Inicio de la APE 6` · `Grupo 6`

</div>

```text
┌─ EXPLORER ─────────────────────────────────────────────────────────────┐
│  📁 ALP-2026-G6                     🟢 main   ☕ OpenJDK   🧩 NetBeans   │
│  ├── 📘 Día 1 · Miércoles 25/11/2026 · Índices · Recorrido · Promedio   │
│  └── 📗 Día 2 · Jueves 26/11/2026   · Búsqueda · Máx/Mín · Integrador   │
└────────────────────────────────────────────────────────────────────────┘
```

---

## 📑 Tabla de contenidos

| # | Sección | Descripción |
|:-:|---|---|
| 1 | [👥 Integrantes](#-integrantes--grupo-6) | Equipo y roles en las sesiones |
| 2 | [🎯 Objetivos](#-objetivos) | Qué se busca lograr en la Semana 15 |
| 3 | [🧠 Resumen técnico](#-resumen-técnico) | Temas del Día 1 y del Día 2 |
| 4 | [🗂️ Estructura del repositorio](#️-estructura-del-repositorio) | Árbol con enlaces a cada `README.md` |
| 5 | [⚙️ Compilación y ejecución](#️-guía-rápida-de-compilación-y-ejecución) | Cómo correr los `.java` |
| 6 | [🧪 Retos y lecciones](#-retos-propuestos-y-lecciones) | Práctica autónoma APE 6 |

---

## 👥 Integrantes · Grupo 6

| # | 👤 Integrante | 🎙️ Sesión | 🛠️ Rol / Bloque |
|:-:|---|:-:|---|
| 1 | **Matias Alejandro Pico Cepeda** | 📘 Día 1 | Expositor Día 1 (Integrantes 1–3): fundamentos, recorridos, suma y promedio |
| 2 | **Marlon Joel Pacha Lucas** | 📘 Día 1 | Expositor Día 1 (Integrantes 1–3): fundamentos, recorridos, suma y promedio |
| 3 | **Marlon Joel Yaguana Manzano** | 📘 Día 1 · 📗 Día 2 | Expositor Día 1 (Integrantes 1–3) · **Bloque 4 Día 2:** Evaluación interactiva en Quizizz (5+ min) |
| 4 | **Leyber Smith Peñafiel Solorzano** | 📗 Día 2 | **Integrante 4 · Bloque 1 y Cierre:** Repaso Día 1 y Búsqueda en Arreglos (25 min) |
| 5 | **Holger Steeve Ortiz Sanchez** | 📗 Día 2 | **Integrante 5 · Bloque 2:** Máximo, Mínimo y Arreglos Paralelos (22 min) |
| 6 | **Joseph Andres Castro Sanchez** | 📗 Día 2 | **Integrante 6 · Bloque 3:** Ejercicio Integrador y `java.util.Arrays` (28 min) |

> [!NOTE]
> El Día 1 fue expuesto por los **Integrantes 1, 2 y 3** (Apertura y Parte 1 → Integrante 1 · Parte 2 → Integrante 2 · Parte 3 y Cierre → Integrante 3), según la agenda de las diapositivas.

---

## 🎯 Objetivos

<table>
<tr>
<td width="50%" valign="top">

### 📘 Día 1 — Fundamentos
- Comprender qué es un **arreglo** y por qué reemplaza a *N* variables sueltas.
- Declarar, crear e inicializar arreglos y conocer sus **valores por defecto**.
- Acceder a elementos mediante **índices** `0 … length - 1`.
- Recorrer arreglos con **`for`, `for-each` y `while`** (secuencial e inverso).
- Aplicar **acumuladores, contadores** y **casting `(double)`** para promedios exactos.

</td>
<td width="50%" valign="top">

### 📗 Día 2 — Algoritmos
- Implementar **búsqueda lineal** (con y sin `break`) y **búsqueda binaria**.
- Comparar `String` correctamente con **`.equals()` / `.equalsIgnoreCase()`**.
- Hallar **máximo y mínimo** con el patrón del *campeón provisional* y `posMax`.
- Usar **arreglos paralelos** (`dias[]` ↔ `temp[]`).
- Integrar todo en **`RegistroNotas.java`** y conocer **`java.util.Arrays`**.

</td>
</tr>
</table>

---

## 🧠 Resumen técnico

<details open>
<summary><b>📘 Día 1 · Miércoles 25/11/2026 · Sesión magistral (1 h 20 min)</b></summary>

<br/>

| ⏱️ Bloque | 📌 Tema | 👤 Responsable | ⌛ Tiempo |
|---|---|:-:|:-:|
| 🚀 Apertura | Motivación: *¿Cómo guardar las notas de 30 estudiantes?* | Marlon Yaguana | 5 min |
| 🧱 Parte 1 | ¿Qué es un arreglo? Declaración, creación e índices | Marlon Yaguana | 22 min |
| 🔁 Parte 2 | Recorrido secuencial e inverso (`for`, `for-each`, `while`) | Matias Pico | 25 min |
| ➕ Parte 3 | Suma, promedio y conteo condicional | Joel Pacha | 23 min |
| 🏁 Cierre | Síntesis, ejercicios propuestos y preguntas | Joel Pacha | 5 min |

**🔑 Conceptos clave**

| Característica | Descripción |
|---|---|
| 🔒 **Tamaño fijo** | La capacidad se define al instanciar y no cambia durante la ejecución. |
| 🧬 **Tipo homogéneo** | Todos los elementos son del mismo tipo (`int`, `double`, `String`…). |
| #️⃣ **Índices desde 0** | Primera casilla `arr[0]`, última `arr[arr.length - 1]`. |

<img src="https://img.shields.io/badge/%E2%97%8F%20%E2%97%8F%20%E2%97%8F-Fundamentos.java-1E1E1E?style=flat-square&labelColor=333333" alt="tab"/>

```java
// Forma 1: declarar y luego reservar memoria
int[] notas;
notas = new int[5];                       // 5 casillas iniciadas en 0

// Forma 2: declaración y creación en una línea
double[] precios = new double[3];         // 0.0, 0.0, 0.0

// Forma 3: inicialización directa
int[] edades = {18, 20, 19, 22};
String[] dias = {"Lunes", "Martes", "Miércoles"};
```

| Tipo de dato | Valor por defecto con `new` |
|---|---|
| `int`, `long` | `0` |
| `double`, `float` | `0.0` |
| `boolean` | `false` |
| `char` | `'\u0000'` |
| `String` / objetos | `null` |

<img src="https://img.shields.io/badge/%E2%97%8F%20%E2%97%8F%20%E2%97%8F-Recorridos.java-1E1E1E?style=flat-square&labelColor=333333" alt="tab"/>

```java
int[] notas = {15, 18, 12, 20, 9};

for (int i = 0; i < notas.length; i++) {          // for clásico (con índice)
    System.out.println("notas[" + i + "] = " + notas[i]);
}
for (int i = notas.length - 1; i >= 0; i--) {     // recorrido inverso
    System.out.print(notas[i] + " ");
}
for (int nota : notas) {                          // for-each (solo lectura)
    System.out.println("Nota: " + nota);
}
int i = 0;
while (i < notas.length) {                        // while
    System.out.println(notas[i++]);
}
```

| Criterio | `for` clásico | `for-each` |
|---|:-:|:-:|
| Acceso al índice | ✅ | ❌ |
| Modificar elementos | ✅ | ❌ (copia del valor) |
| Simplicidad visual | Media | Alta |
| Recorrer al revés | ✅ | ❌ |

<img src="https://img.shields.io/badge/%E2%97%8F%20%E2%97%8F%20%E2%97%8F-PromedioYConteo.java-1E1E1E?style=flat-square&labelColor=333333" alt="tab"/>

```java
int suma = 74, cantidad = 5;
double mal  = suma / cantidad;            // 14.0  ❌ división entera
double bien = (double) suma / cantidad;   // 14.8  ✅ casting explícito

int[] notas = {15, 18, 8, 20, 9, 12};
int aprobados = 0;
for (int nota : notas) {
    if (nota >= 11) aprobados++;          // contador condicional
}
System.out.println("Aprobados: " + aprobados);                       // 4
System.out.println("Desaprobados: " + (notas.length - aprobados));   // 2
```

</details>

<details open>
<summary><b>📗 Día 2 · Jueves 26/11/2026 · Inicio APE 6 (1 h 20 min)</b></summary>

<br/>

| ⏱️ Bloque | 📌 Tema | 👤 Responsable | ⌛ Tiempo |
|---|---|:-:|:-:|
| ⚡ Repaso | Índices, ciclos y casteo `(double)` | Leyber Peñafiel | 5 min |
| 🔍 Parte 4 | Búsqueda: lineal, `Scanner`, repetidos, `String` y binaria | Leyber Peñafiel | 20 min |
| 🏆 Parte 5 | Máximo y mínimo: campeón provisional, `posMax`, paralelos | Steeve Ortiz | 22 min |
| 🧩 Parte 6 | Ejercicio integrador `RegistroNotas.java` y `java.util.Arrays` | Joseph Castro | 28 min |
| 🎮 Cierre | Quiz oral, Quizizz y retos Guía APE 6 | Leyber, Joseph y Marlon Yaguana | 5 min |

```text
Arreglo base de las trazas del día (length = 7)
┌──────┬──────┬──────┬──────┬──────┬──────┬──────┐
│  14  │   7  │  25  │   3  │  18  │   7  │  30  │
└──────┴──────┴──────┴──────┴──────┴──────┴──────┘
   [0]    [1]    [2]    [3]    [4]    [5]    [6]
  primer repetido target       repetido  máximo
```

<img src="https://img.shields.io/badge/%E2%97%8F%20%E2%97%8F%20%E2%97%8F-BusquedaLineal.java-1E1E1E?style=flat-square&labelColor=333333" alt="tab"/>

```java
int[] numeros = {14, 7, 25, 3, 18, 7, 30};
int buscado = 25;
int posicion = -1;                         // -1 = "aún no encontrado"

for (int i = 0; i < numeros.length; i++) {
    if (numeros[i] == buscado) {
        posicion = i;
        break;                             // corte temprano
    }
}
System.out.println(posicion != -1
        ? "El " + buscado + " está en la posición " + posicion   // 2
        : "El " + buscado + " no está en el arreglo");
```

| Criterio | 🔎 Búsqueda lineal | ⚡ Búsqueda binaria |
|---|:-:|:-:|
| ¿Arreglo ordenado? | No necesario | **Obligatorio** |
| Dificultad de código | Muy fácil | Media |
| 1000 datos (peor caso) | 1000 comparaciones | ~10 comparaciones |

<img src="https://img.shields.io/badge/%E2%97%8F%20%E2%97%8F%20%E2%97%8F-Temperaturas.java-1E1E1E?style=flat-square&labelColor=333333" alt="tab"/>

```java
String[] dias = {"Lun", "Mar", "Mié", "Jue", "Vie", "Sáb", "Dom"};
double[] temp = {22.5, 24.0, 19.8, 27.3, 25.1, 21.0, 18.4};

int posMax = 0, posMin = 0;                // campeones provisionales (índices)
for (int i = 1; i < temp.length; i++) {
    if (temp[i] > temp[posMax]) posMax = i;
    if (temp[i] < temp[posMin]) posMin = i;
}
System.out.println("Día más caluroso: " + dias[posMax] + " (" + temp[posMax] + " °C)"); // Jue
System.out.println("Día más frío: "     + dias[posMin] + " (" + temp[posMin] + " °C)"); // Dom
```

<img src="https://img.shields.io/badge/%E2%97%8F%20%E2%97%8F%20%E2%97%8F-RegistroNotas.java-1E1E1E?style=flat-square&labelColor=333333" alt="tab"/>

```java
import java.util.Scanner;

public class RegistroNotas {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        // 1. Crear y llenar el arreglo
        System.out.print("¿Cuántos estudiantes? ");
        int n = sc.nextInt();
        double[] notas = new double[n];
        for (int i = 0; i < n; i++) {
            System.out.print("Nota del estudiante " + (i + 1) + ": ");
            notas[i] = sc.nextDouble();
        }

        // 2. Sumar, contar aprobados, máximo y mínimo en UN recorrido
        double suma = 0;
        int aprobados = 0, posMax = 0, posMin = 0;
        for (int i = 0; i < n; i++) {
            suma += notas[i];
            if (notas[i] >= 11) aprobados++;
            if (notas[i] > notas[posMax]) posMax = i;
            if (notas[i] < notas[posMin]) posMin = i;
        }
        double promedio = suma / n;

        // 3. Reporte
        System.out.println("\n===== RESULTADOS =====");
        System.out.println("Promedio: " + String.format("%.2f", promedio));
        System.out.println("Nota más alta: " + notas[posMax] + " (estudiante " + (posMax + 1) + ")");
        System.out.println("Nota más baja: " + notas[posMin] + " (estudiante " + (posMin + 1) + ")");
        System.out.println("Aprobados: " + aprobados);
        System.out.println("Desaprobados: " + (n - aprobados));

        // 4. Buscar una nota (búsqueda lineal con bandera)
        System.out.print("\n¿Qué nota desea buscar? ");
        double buscada = sc.nextDouble();
        boolean existe = false;
        for (double nota : notas) {
            if (nota == buscada) { existe = true; break; }
        }
        System.out.println(existe ? "Sí hay un estudiante con esa nota."
                                  : "Ningún estudiante tiene esa nota.");
    }
}
```

<details>
<summary>🖥️ <b>Salida en consola — Apache NetBeans</b></summary>

```bash
run:
¿Cuántos estudiantes? 5
Nota del estudiante 1: 15
Nota del estudiante 2: 8
Nota del estudiante 3: 18
Nota del estudiante 4: 11
Nota del estudiante 5: 9

===== RESULTADOS =====
Promedio: 12.20
Nota más alta: 18.0 (estudiante 3)
Nota más baja: 8.0 (estudiante 2)
Aprobados: 3
Desaprobados: 2

¿Qué nota desea buscar? 11
Sí hay un estudiante con esa nota.
BUILD SUCCESSFUL
```

</details>

**🧰 `java.util.Arrays` — métodos esenciales**

| Método | Uso | Ejemplo |
|---|---|---|
| `Arrays.toString(a)` | Mostrar legible | `[14, 7, 25, 3, 18]` |
| `Arrays.sort(a)` | Ordenar ascendente | `[3, 7, 14, 18, 25]` |
| `Arrays.fill(a, v)` | Rellenar | `[5, 5, 5, 5]` |
| `Arrays.copyOf(a, n)` | Copia **real** (no `b = a`) | arreglo independiente |
| `Arrays.equals(a, b)` | Comparar contenido | `true` |
| `Arrays.binarySearch(a, x)` | Búsqueda binaria (ordenado) | `3` |

</details>

<details>
<summary><b>🧭 Patrón universal: Recorrido + Variable auxiliar</b></summary>

<br/>

| # | Patrón | Variable auxiliar | Inicialización | Día |
|:-:|---|---|---|:-:|
| 1 | 🔁 Recorrido | índice `i` | `0` | 1 |
| 2 | ➕ Acumulador (suma) | `suma` | `0` | 1 |
| 3 | ➗ Promedio | `(double) suma / length` | — | 1 |
| 4 | 🔢 Contador | `cont++` si cumple `if` | `0` | 1 y 2 |
| 5 | 🔍 Búsqueda lineal | `pos` + `break` | `-1` | 2 |
| 6 | 🏆 Máximo / mínimo | campeón provisional | `arreglo[0]` o `pos = 0` | 2 |

</details>

<details>
<summary><b>⚠️ Errores frecuentes</b></summary>

<br/>

| ❌ Error | ✅ Corrección |
|---|---|
| Comparar `String` con `==` | Usar `.equals()` / `.equalsIgnoreCase()` |
| Imprimir "no encontrado" dentro del `for` | Decidir **fuera** del ciclo con `pos != -1` |
| Iniciar `posicion = 0` | Iniciar en `-1` (nunca es un índice válido) |
| Dejar `break` al contar repeticiones | Quitar el `break` para contar todas |
| Iniciar `maximo = 0` | Iniciar en `numeros[0]` (falla con negativos) |
| `System.out.println(arr)` → `[I@1b6d3586` | `Arrays.toString(arr)` |
| `int[] b = a;` como "copia" | `Arrays.copyOf(a, a.length)` |
| División entera `suma / n` | Casting `(double) suma / n` |

</details>

---

## 🗂️ Estructura del repositorio

<pre>
📦 <b>ALP-2026-G6</b>
├── 📄 <a href="./README.md">README.md</a> ................................. Documento principal (estás aquí)
├── 📁 <a href="./docs/README.md">docs/</a> ...................................... Documentación académica
│   ├── 📁 <a href="./docs/Clase-Dia_1/README.md">Clase-Dia_1/</a> ........................... 📘 Diapositivas Día 1 (PDF)
│   ├── 📁 <a href="./docs/Clase-Dia_2/README.md">Clase-Dia_2/</a> ........................... 📗 Diapositivas Día 2 (PPTX)
│   ├── 📁 <a href="./docs/LECCIONES/README.md">LECCIONES/</a> ............................. 📝 Lecciones / evaluaciones
│   ├── 📝 conclusiones.md
│   ├── 📝 investigacion.md
│   └── 📝 preguntas.md
├── 📁 <a href="./src/README.md">src/</a> ....................................... ☕ Código fuente Java
├── 📁 <a href="./prototipos/README.md">prototipos/</a> ................................ 🧪 Bocetos y versiones preliminares
├── 📁 <a href="./resultados/README.md">resultados/</a> ................................ 📊 Salidas de consola y reportes
└── 📁 <a href="./Evidencias/README.md">Evidencias/</a> ................................ 📸 Capturas y evidencias de trabajo
</pre>

| 📁 Carpeta | 🎯 Propósito | 🔗 README |
|---|---|:-:|
| `docs/` | Material teórico, diapositivas y lecciones | [Abrir](./docs/README.md) |
| `docs/Clase-Dia_1/` | Presentación *Arreglos en Java – Día 1* | [Abrir](./docs/Clase-Dia_1/README.md) |
| `docs/Clase-Dia_2/` | Presentación *Arreglos en Java – Día 2* | [Abrir](./docs/Clase-Dia_2/README.md) |
| `docs/LECCIONES/` | Enlaces a las lecciones (Google Forms) | [Abrir](./docs/LECCIONES/README.md) |
| `src/` | Programas `.java` de las sesiones | [Abrir](./src/README.md) |
| `prototipos/` | Prototipos y pruebas de concepto | [Abrir](./prototipos/README.md) |
| `resultados/` | Resultados de ejecución | [Abrir](./resultados/README.md) |
| `Evidencias/` | Evidencias del trabajo grupal | [Abrir](./Evidencias/README.md) |

---

## ⚙️ Guía rápida de compilación y ejecución

<img src="https://img.shields.io/badge/%E2%97%8F%20%E2%97%8F%20%E2%97%8F-TERMINAL%20%E2%80%94%20bash-1E1E1E?style=flat-square&labelColor=333333" alt="terminal"/>

```bash
# 1️⃣  Clonar el repositorio
git clone https://github.com/matiaspicocepeda-max/ALP-2026-G6.git
cd ALP-2026-G6

# 2️⃣  Verificar la instalación de OpenJDK
java -version
javac -version

# 3️⃣  Compilar todos los programas de src/ en la carpeta out/
javac -encoding UTF-8 -d out src/*.java

# 4️⃣  Ejecutar un programa (nombre de la clase, sin .java)
java -cp out RegistroNotas
java -cp out BusquedaLineal
```

<details>
<summary>🧩 <b>Ejecutar en Apache NetBeans</b></summary>

```text
1. File ▸ New Project ▸ Java with Ant/Maven ▸ Java Application
2. Copiar los archivos .java de src/ al paquete del proyecto
3. Clic derecho sobre la clase ▸ Run File   (atajo: Shift + F6)
4. Ver la salida en la ventana Output ▸ "run:" … "BUILD SUCCESSFUL"
```

</details>

<details>
<summary>🪟 <b>Windows (PowerShell)</b></summary>

```bash
javac -encoding UTF-8 -d out (Get-ChildItem src\*.java).FullName
java -cp out RegistroNotas
```

</details>

---

## 🧪 Retos propuestos y lecciones

<details>
<summary><b>📘 Práctica autónoma — Día 1</b></summary>

1. Crear un arreglo de **6 temperaturas** y calcular suma y promedio.
2. Imprimir los elementos de un arreglo en **orden inverso**.
3. Contar cuántos valores son **mayores que 10**.

</details>

<details>
<summary><b>📗 Retos Guía APE 6 — Día 2</b></summary>

| Reto | Enunciado | 💡 Pista |
|---|---|---|
| 1️⃣ Promedio y filtro | Pedir 8 números y contar cuántos superan el promedio | Dos recorridos |
| 2️⃣ Buscador de nombres | Buscar un `String` en un arreglo de 5 nombres | `pos = -1` + `equalsIgnoreCase` + `break` |
| 3️⃣ Doble campeón | Hallar el **segundo** número mayor | `mayor` y `segundoMayor` o `Arrays.sort()` sobre copia |
| 4️⃣ Invertir in-place | Invertir sin arreglo auxiliar | Recorrer hasta `length / 2` con `aux` |

</details>

📝 **Lecciones:** ver [docs/LECCIONES](./docs/LECCIONES/README.md).

---

<p align="center">
  <img src="https://img.shields.io/badge/Hecho%20con-%E2%98%95%20Java%20%2B%20%F0%9F%92%99%20NetBeans-007ACC?style=flat-square&labelColor=1E1E1E" alt="footer"/>
  <img src="https://img.shields.io/badge/Grupo-6-C586C0?style=flat-square&labelColor=1E1E1E" alt="grupo"/>
  <img src="https://img.shields.io/badge/Siguiente-ArrayList%20(G7)%20%C2%B7%20LinkedList%20(G8)-4EC9B0?style=flat-square&labelColor=1E1E1E" alt="next"/>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4EC9B0,50:C586C0,100:007ACC&height=120&section=footer" alt="footer" width="100%"/>
</p>
