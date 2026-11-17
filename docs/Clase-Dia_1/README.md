<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1E1E,100:007ACC&height=120&section=header&text=%F0%9F%93%98%20Clase-Dia_1&fontSize=40&fontColor=DCDCAA&fontAlignY=55" alt="banner" width="100%"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-OpenJDK-007ACC?style=flat-square&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/IDE-Apache%20NetBeans-1B6AC6?style=flat-square&logo=apachenetbeanside&logoColor=white" alt="NetBeans"/>
  <img src="https://img.shields.io/badge/GitHub-ALP--2026--G6-1E1E1E?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
  <img src="https://img.shields.io/badge/Ingenier%C3%ADa-de%20Software-C586C0?style=flat-square" alt="IS"/>
  <img src="https://img.shields.io/badge/UTA-Mi%C3%A9rcoles%2025%2F11%2F2026-DCDCAA?style=flat-square&labelColor=1E1E1E" alt="UTA"/>
</p>

```text
EXPLORER ▸ ALP-2026-G6 ▸ docs ▸ Clase-Dia_1/          📘 Sesión magistral · 1 h 20 min · Integrantes 1, 2 y 3
```

## 🎯 Propósito

Contiene la presentación **“Arreglos en Java – Día 1”**: fundamentos de estructuras indexadas, recorrido secuencial de datos y algoritmos de acumulación, promedio y conteo condicional.

## 📄 Archivos

| 📄 Archivo | 🏷️ Formato | 📏 Contenido |
|---|:-:|---|
| [`Arreglos en Java – Día 1.pdf`](<./Arreglos en Java – Día 1.pdf>) | 📕 PDF | 20 diapositivas de la sesión |
| `README.md` | 📝 MD | Este documento |

---

## ⏱️ Agenda de la sesión

| Bloque | Tema | Responsable | Tiempo |
|---|---|:-:|:-:|
| 🚀 Apertura | ¿Cómo guardar las notas de 30 estudiantes? | Integrante 1 | 5 min |
| 🧱 Parte 1 | ¿Qué es un arreglo? Declaración, creación e índices | Integrante 1 | 22 min |
| 🔁 Parte 2 | Recorrido secuencial e inverso (`for`, `for-each`, `while`) | Integrante 2 | 25 min |
| ➕ Parte 3 | Suma, promedio y conteo condicional | Integrante 3 | 23 min |
| 🏁 Cierre | Síntesis y ronda de preguntas | Integrante 3 | 5 min |

---

<details open>
<summary><b>🧱 Parte 1 · Fundamentos e índices</b></summary>

```java
int[] notas = {15, 18, 12, 20, 9};   // notas.length = 5
notas[0];                            // 15 → primer elemento
notas[3];                            // 20 → acceso directo
notas[notas.length - 1];             // 9  → último índice = 4
```

```text
 índice →    0      1      2      3      4
          ┌──────┬──────┬──────┬──────┬──────┐
 notas =  │  15  │  18  │  12  │  20  │   9  │
          └──────┴──────┴──────┴──────┴──────┘
```

| 🔒 Tamaño fijo | 🧬 Tipo homogéneo | #️⃣ Índices desde 0 |
|---|---|---|
| Se fija al instanciar | Mismo tipo para todos | De `0` a `length - 1` |

</details>

<details>
<summary><b>🔁 Parte 2 · Recorridos y llenado con Scanner</b></summary>

```java
import java.util.Scanner;

public class LlenarArreglo {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int[] notas = new int[4];
        for (int i = 0; i < notas.length; i++) {
            System.out.print("Ingrese la nota " + (i + 1) + ": ");
            notas[i] = sc.nextInt();
        }
        System.out.println("\nNotas ingresadas:");
        for (int nota : notas) {
            System.out.println(nota);
        }
    }
}
```

> 💡 Se imprime `i + 1` porque las personas cuentan desde 1, mientras Java guarda en el índice real `i` (desde 0).

</details>

<details>
<summary><b>➕ Parte 3 · Suma, promedio, casting y conteo</b></summary>

```java
int suma = 74, cantidad = 5;
double mal  = suma / cantidad;             // 14.0 ❌ trunca decimales
double bien = (double) suma / cantidad;    // 14.8 ✅

int[] numeros = {3, 8, 5, 10, 7, 4};
int sumaPares = 0;
for (int n : numeros) {
    if (n % 2 == 0) sumaPares += n;        // 8 + 10 + 4 = 22
}
```

</details>

<details>
<summary><b>📝 Práctica autónoma</b></summary>

1. Crear un arreglo de **6 temperaturas** y calcular suma y promedio.
2. Imprimir un arreglo en **orden inverso**.
3. Contar cuántos valores son **mayores que 10**.

</details>

---

<p align="center">
  <a href="../README.md"><img src="https://img.shields.io/badge/%E2%AC%85%EF%B8%8F%20Volver-docs-007ACC?style=flat-square&labelColor=1E1E1E" alt="docs"/></a>
  <a href="../Clase-Dia_2/README.md"><img src="https://img.shields.io/badge/Siguiente-D%C3%ADa%202%20%E2%9E%A1%EF%B8%8F-4EC9B0?style=flat-square&labelColor=1E1E1E" alt="dia2"/></a>
  <a href="../../README.md"><img src="https://img.shields.io/badge/%F0%9F%8F%A0-README%20principal-C586C0?style=flat-square&labelColor=1E1E1E" alt="home"/></a>
</p>
