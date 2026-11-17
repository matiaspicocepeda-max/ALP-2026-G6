<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1E1E,100:C586C0&height=120&section=header&text=%F0%9F%93%97%20Clase-Dia_2&fontSize=40&fontColor=4EC9B0&fontAlignY=55" alt="banner" width="100%"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-OpenJDK-007ACC?style=flat-square&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/IDE-Apache%20NetBeans-1B6AC6?style=flat-square&logo=apachenetbeanside&logoColor=white" alt="NetBeans"/>
  <img src="https://img.shields.io/badge/GitHub-ALP--2026--G6-1E1E1E?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
  <img src="https://img.shields.io/badge/Ingenier%C3%ADa-de%20Software-C586C0?style=flat-square" alt="IS"/>
  <img src="https://img.shields.io/badge/UTA-Jueves%2026%2F11%2F2026%20%C2%B7%20APE%206-DCDCAA?style=flat-square&labelColor=1E1E1E" alt="UTA"/>
</p>

```text
EXPLORER ▸ ALP-2026-G6 ▸ docs ▸ Clase-Dia_2/      📗 Búsqueda · Máximo · Mínimo · Integrador · 1 h 20 min
```

## 🎯 Propósito

Contiene la presentación **“Arreglos en Java – Día 2: Búsqueda, Máximo, Mínimo y Ejercicio Integrador”** (25 diapositivas), con la que se da inicio a la **APE 6**.

## 📄 Archivos

| 📄 Archivo | 🏷️ Formato | 📏 Contenido |
|---|:-:|---|
| [`Arreglos_Java_Dia2_Grupo6.pptx`](./Arreglos_Java_Dia2_Grupo6.pptx) | 📙 PPTX | 25 diapositivas de la sesión |
| `README.md` | 📝 MD | Este documento |

---

## ⏱️ Agenda y responsables

| Bloque | Tema | 👤 Responsable | Tiempo | Diapositivas |
|---|---|---|:-:|:-:|
| ⚡ 1 | Repaso del Día 1 + **Búsqueda** (lineal, Scanner, repetidos, `String`, binaria) | Leyber Peñafiel (Int. 4) | 25 min | 3–10 |
| 🏆 2 | **Máximo y mínimo**, `posMax`, arreglos paralelos | Steeve Ortiz (Int. 5) | 22 min | 11–16 |
| 🧩 3 | **Ejercicio integrador** `RegistroNotas.java` + `java.util.Arrays` | Joseph Castro (Int. 6) | 28 min | 17–22 |
| 🎮 4 | Mini-quiz, **Quizizz**, retos y conclusiones | Leyber, Joseph y Marlon Yaguana | 5+ min | 23–25 |

---

<details open>
<summary><b>🔍 Bloque 1 · Búsqueda en arreglos</b></summary>

<img src="https://img.shields.io/badge/%E2%97%8F%20%E2%97%8F%20%E2%97%8F-BuscarNumero.java-1E1E1E?style=flat-square&labelColor=333333" alt="tab"/>

```java
import java.util.Scanner;

public class BuscarNumero {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int[] numeros = {14, 7, 25, 3, 18, 7, 30};
        System.out.print("Ingrese el número a buscar: ");
        int buscado = sc.nextInt();
        int posicion = -1;
        for (int i = 0; i < numeros.length; i++) {
            if (numeros[i] == buscado) { posicion = i; break; }
        }
        if (posicion != -1) System.out.println("Encontrado en la posición " + posicion);
        else                System.out.println("El número no existe en el arreglo");
    }
}
```

| Caso | Técnica |
|---|---|
| 🔁 Valores repetidos | Sin `break`, con contador `veces++` |
| 🔤 Arreglo de `String` | `.equals()` / `.equalsIgnoreCase()` — nunca `==` |
| ⚡ Búsqueda binaria | `Arrays.binarySearch(ordenado, 18)` → requiere arreglo **ordenado** |

</details>

<details>
<summary><b>🏆 Bloque 2 · Máximo, mínimo y paralelos</b></summary>

```java
int maximo = numeros[0];                     // campeón provisional
for (int i = 1; i < numeros.length; i++) {   // el retador empieza en i = 1
    if (numeros[i] > maximo) maximo = numeros[i];
}
// Máximo: 30
```

```text
Traza:  14 👑 → 7 ✗ → 25 👑 → 3 ✗ → 18 ✗ → 7 ✗ → 30 🏆
```

> ⚠️ Nunca iniciar `maximo = 0`: con `{-4, -10, -1, -7}` imprimiría `0` en lugar de `-1`.

</details>

<details>
<summary><b>🧩 Bloque 3 · RegistroNotas.java y java.util.Arrays</b></summary>

| Fase | Temas aplicados (Día 1 + Día 2) | Variables clave |
|---|---|---|
| 1️⃣ Entrada | Tamaño dinámico, llenado con `Scanner`, `(i + 1)` | `n`, `notas[]`, `sc` |
| 2️⃣ Proceso | Acumulador, contador, máximo y mínimo con posición | `suma`, `aprobados`, `posMax`, `posMin` |
| 3️⃣ Salida | `String.format("%.2f")`, `n - aprobados` | `promedio` |
| 4️⃣ Consulta | Búsqueda lineal `for-each` + bandera + `break` | `buscada`, `existe` |

```java
int[] a = {1, 2, 3};
int[] b = a;                          // ❌ misma referencia (mismo "televisor")
int[] c = Arrays.copyOf(a, a.length); // ✅ copia independiente
```

</details>

<details>
<summary><b>🎮 Bloque 4 · Mini-quiz y retos APE 6</b></summary>

| ❓ Pregunta | ✅ Respuesta |
|---|---|
| Último índice de un arreglo de 8 elementos | `7` |
| ¿Por qué el ciclo de máximo empieza en `i = 1`? | El índice 0 ya es el campeón inicial |
| ¿Cómo comparar dos `String`? | `.equals()` / `.equalsIgnoreCase()` |
| ¿Qué devuelve la búsqueda si no existe? | `-1` |
| Requisito de la búsqueda binaria | Arreglo ordenado |

**Retos:** promedio y filtro · buscador de nombres · segundo mayor · invertir *in-place*.

</details>

---

<p align="center">
  <a href="../Clase-Dia_1/README.md"><img src="https://img.shields.io/badge/%E2%AC%85%EF%B8%8F%20Anterior-D%C3%ADa%201-DCDCAA?style=flat-square&labelColor=1E1E1E" alt="dia1"/></a>
  <a href="../README.md"><img src="https://img.shields.io/badge/%F0%9F%93%81-docs-007ACC?style=flat-square&labelColor=1E1E1E" alt="docs"/></a>
  <a href="../../README.md"><img src="https://img.shields.io/badge/%F0%9F%8F%A0-README%20principal-C586C0?style=flat-square&labelColor=1E1E1E" alt="home"/></a>
</p>
