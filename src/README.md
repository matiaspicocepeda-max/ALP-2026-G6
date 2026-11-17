<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1E1E,100:007ACC&height=120&section=header&text=%E2%98%95%20src%2F&fontSize=40&fontColor=DCDCAA&fontAlignY=55" alt="banner" width="100%"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-OpenJDK-007ACC?style=flat-square&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/IDE-Apache%20NetBeans-1B6AC6?style=flat-square&logo=apachenetbeanside&logoColor=white" alt="NetBeans"/>
  <img src="https://img.shields.io/badge/GitHub-ALP--2026--G6-1E1E1E?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
  <img src="https://img.shields.io/badge/Ingenier%C3%ADa-de%20Software-C586C0?style=flat-square" alt="IS"/>
  <img src="https://img.shields.io/badge/UTA-Semana%2015-DCDCAA?style=flat-square&labelColor=1E1E1E" alt="UTA"/>
</p>

```text
EXPLORER ▸ ALP-2026-G6 ▸ src/                                      ☕ Código fuente Java
```

## 🎯 Propósito

Carpeta destinada al **código fuente `.java`** desarrollado y probado en **Apache NetBeans (OpenJDK)** durante las sesiones de Arreglos en Java.

## 📄 Archivos

| 📄 Archivo | 📌 Descripción | 🚦 Estado |
|---|---|:-:|
| `README.md` | Este documento | ✅ |

<details open>
<summary><b>🗺️ Programas previstos según las diapositivas</b></summary>

| ☕ Clase | 📘/📗 Sesión | 🧠 Tema |
|---|:-:|---|
| `LlenarArreglo.java` | Día 1 | Llenado con `Scanner` y recorrido `for-each` |
| `BusquedaLineal.java` | Día 2 | Búsqueda secuencial con `break` y `posicion = -1` |
| `BuscarNumero.java` | Día 2 | Búsqueda de un valor ingresado por el usuario |
| `Temperaturas.java` | Día 2 | Arreglos paralelos, `posMax` y `posMin` |
| `RegistroNotas.java` | Día 2 | Ejercicio integrador (suma, promedio, aprobados, máx/mín, búsqueda) |
| `HerramientasArrays.java` | Día 2 | `toString`, `sort`, `fill`, `copyOf`, `equals` |

</details>

## ⚙️ Compilar y ejecutar

<img src="https://img.shields.io/badge/%E2%97%8F%20%E2%97%8F%20%E2%97%8F-TERMINAL%20%E2%80%94%20bash-1E1E1E?style=flat-square&labelColor=333333" alt="terminal"/>

```bash
# desde la raíz del repositorio
javac -encoding UTF-8 -d out src/*.java
java -cp out RegistroNotas
```

<details>
<summary><b>📐 Convenciones de código</b></summary>

```java
// ✔ Una clase pública por archivo; el archivo se llama igual que la clase
// ✔ Nombres de variables coherentes con el Día 1: notas, suma, promedio
// ✔ Usar (double) al dividir enteros y Arrays.toString() para imprimir arreglos
public class NombreClase {
    public static void main(String[] args) { /* ... */ }
}
```

</details>

---

<p align="center">
  <a href="../README.md"><img src="https://img.shields.io/badge/%F0%9F%8F%A0-README%20principal-C586C0?style=flat-square&labelColor=1E1E1E" alt="home"/></a>
</p>
