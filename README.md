# unicode4research
# Símbolos Unicode para decorar Scripts de Bioinformática!

Este documento describe los símbolos Unicode utilizados a lo largo de los scripts de este proyecto para denotar diferentes secciones, tareas o tipos de análisis. El objetivo es mejorar la legibilidad y la navegación rápida a través del código.

## 1. Inicio, Fin y Flujo del Script

| Símbolo | Unicode (Hex) | Descripción Sugerida                                  |
| :-----: | :-----------: | ----------------------------------------------------- |
|    🚀    |   `U+1F680`   | Inicio del script o sección principal                 |
|    🏁    |   `U+1F3C1`   | Fin del script o sección principal                    |
|    🛑    |   `U+1F6D1`   | Fin de análisis listos (sección completada)         |
|    ➡️    |   `U+27A1`    | Flujo del script, pasos secuenciales                  |
|    🔄    |   `U+1F504`   | Bucles, procesos iterativos, reinicios                |
|    ⏳    |   `U+23F3`    | Procesos largos o que consumen tiempo considerable    |

## 2. Configuración y Dependencias

| Símbolo | Unicode (Hex) | Descripción Sugerida                                  |
| :-----: | :-----------: | ----------------------------------------------------- |
|    ⚙️    |   `U+2699`    | Configuración inicial, parámetros, carga de funciones |
|    📦    |   `U+1F4E6`   | Carga de librerías o dependencias (R packages, etc.)  |
|    🏷️    |   `U+1F3F7`   | Definición de variables globales o constantes         |
|    🧱    |   `U+1F9F1`   | Definición de funciones personalizadas                |

## 3. Manejo de Datos (Entrada, Salida, Guardado)

| Símbolo | Unicode (Hex) | Descripción Sugerida                                  |
| :-----: | :-----------: | ----------------------------------------------------- |
|    📥    |   `U+1F4E5`   | Carga de datos crudos o archivos de entrada           |
|    📄    |   `U+1F4C4`   | Lectura de archivos de datos (e.g., CSV, TXT)         |
|    📑    |   `U+1F4D1`   | Lectura de archivos genómicos (e.g., FASTA, VCF)      |
|    💾    |   `U+1F4BE`   | Guardar imagen de sesión, objetos RData              |
|    📤    |   `U+1F4E4`   | Exportar resultados, tablas procesadas                |
|    📁    |   `U+1F4C1`   | Manejo de directorios y rutas (carpeta cerrada)      |
|    📂    |   `U+1F4C2`   | Manejo de directorios y rutas (carpeta abierta)     |

## 4. Limpieza y Preprocesamiento de Datos

| Símbolo | Unicode (Hex) | Descripción Sugerida                                  |
| :-----: | :-----------: | ----------------------------------------------------- |
|    🧹    |   `U+1F9F9`   | Limpieza general de datos                             |
|    ✂️    |   `U+2702`    | Recorte (trimming) de secuencias, filtrado de datos   |
|    🛠️    |   `U+1F6E0`   | Transformación de datos, formateo                     |
|    🧩    |   `U+1F9E9`   | Ingeniería de características, preparación de datos   |
|    🔗    |   `U+1F517`   | Unir, fusionar (merge/join) o combinar conjuntos de datos |

## 5. Análisis Exploratorio y Visualización General

| Símbolo | Unicode (Hex) | Descripción Sugerida                                  |
| :-----: | :-----------: | ----------------------------------------------------- |
|    📊    |   `U+1F4CA`   | Visualización de datos general, EDA                   |
|    📈    |   `U+1F4C8`   | Visualizar tendencias, incrementos                    |
|    📉    |   `U+1F4C9`   | Visualizar tendencias, decrementos                    |
|    🔍    |   `U+1F50E`   | Exploración detallada, inspección de datos (lupa der.)|
|    🔎    |   `U+1F50D`   | Exploración detallada, inspección de datos (lupa izq.)|
|    💡    |   `U+1F4A1`   | Hallazgos iniciales, ideas surgidas del EDA           |
|    📷    |   `U+1F4F7`   | Generación de figuras y gráficos                      |

## 6. Análisis Genómico Específico

### 6.1 Secuencias y Genomas

| Símbolo | Unicode (Hex) | Descripción Sugerida                                  |
| :-----: | :-----------: | ----------------------------------------------------- |
|    🧬    |   `U+1F9EC`   | ADN, ARN, genes, genómica en general                  |
|    📖    |   `U+1F4D6`   | Genoma de referencia, anotaciones                     |
|    🏠    |   `U+1F3E0`   | Genoma de referencia como base                        |
|    🧱    |   `U+1F9F1`   | Ensamblaje de genomas (assembly), construcción de contigs |

### 6.2 Variantes y Mutaciones

| Símbolo | Unicode (Hex) | Descripción Sugerida                                  |
| :-----: | :-----------: | ----------------------------------------------------- |
|    🔢    |   `U+1F522`   | SNPs, conteo de variantes                             |
|    ➕    |   `U+2795`    | Inserciones (InDels)                                  |
|    ➖    |   `U+2796`    | Deleciones (InDels)                                   |
|    🔬    |   `U+1F52C`   | Análisis detallado de variantes, validación           |

### 6.3 Selección y Adaptación

| Símbolo | Unicode (Hex) | Descripción Sugerida                                  |
| :-----: | :-----------: | ----------------------------------------------------- |
|    🎯    |   `U+1F3AF`   | Búsqueda de genes/regiones bajo selección, loci candidatos |
|    🌟    |   `U+1F31F`   | Regiones con señales fuertes de selección             |
|    🔥    |   `U+1F525`   | Hotspots de selección, adaptación rápida              |
|    📈    |   `U+1F4C8`   | Podría indicar selección positiva (contextual)        |
|   🧑‍🌾   | `U+1F9D1 U+200D U+1F33E` | Análisis relacionados con domesticación            |

### 6.4 Estructura Poblacional y Filogenia

| Símbolo | Unicode (Hex) | Descripción Sugerida                                  |
| :-----: | :-----------: | ----------------------------------------------------- |
|  🧑‍🤝‍🧑  | `U+1F9D1 U+200D U+1F91D U+200D U+1F9D1` | Estructura poblacional, análisis de poblaciones |
|    👥    |   `U+1F465`   | Mezcla (admixture), subpoblaciones                    |
|    🌳    |   `U+1F333`   | Árboles filogenéticos, dendrogramas, coalescencia     |
|    🕸️    |   `U+1F578`   | Redes de haplotipos, relaciones complejas             |
|    🔀    |   `U+1F500`   | Recombinación, análisis de ligamiento                 |

## 7. Análisis Ecológico

| Símbolo | Unicode (Hex) | Descripción Sugerida                                  |
| :-----: | :-----------: | ----------------------------------------------------- |
|    🌱    |   `U+1F331`   | Organismos vegetales, *Gracilaria*, crecimiento       |
|    🌿    |   `U+1F33F`   | Vegetación, comunidades                               |
|    🌊    |   `U+1F30A`   | Ecología acuática/marina, seascape genomics          |
|    💧    |   `U+1F4A7`   | Calidad del agua, condiciones hídricas                |
|    🌡️    |   `U+1F321`   | Temperatura, variables ambientales                    |
|    ☀️    |   `U+2600`    | Radiación solar, luz                                  |
|    🔗    |   `U+1F517`   | Interacciones ecológicas, redes (contextual)        |
|    ♻️    |   `U+267B`   | Ciclos de nutrientes                                  |
|    🏞️    |   `U+1F3DE`   | Análisis de paisajes, hábitats                        |

## 8. Análisis Geográfico / Espacial

| Símbolo | Unicode (Hex) | Descripción Sugerida                                  |
| :-----: | :-----------: | ----------------------------------------------------- |
|    🌍    |   `U+1F30D`   | Globo terráqueo mostrando Europa y África             |
|    🌎    |   `U+1F30E`   | Globo terráqueo mostrando las Américas                |
|    🌏    |   `U+1F30F`   | Globo terráqueo mostrando Asia y Australia            |
|    🌐    |   `U+1F310`   | Biogeografía, seascape genomics, conectividad         |
|    🗺️    |   `U+1F5FA`   | Creación de mapas, GIS, distribución espacial         |
|    📍    |   `U+1F4CD`   | Coordenadas, puntos de muestreo, mapeo                |
|    🧭    |   `U+1F9ED`   | Orientación, análisis de dispersión direccional       |
|    🛰️    |   `U+1F6F0`   | Datos de teledetección, variables espaciales          |
|    📏    |   `U+1F4CF`   | Mediciones espaciales, distancias                     |
|    📐    |   `U+1F4D0`   | Mediciones espaciales, áreas                          |

## 9. Modelado y Pruebas Estadísticas

| Símbolo | Unicode (Hex) | Descripción Sugerida                                  |
| :-----: | :-----------: | ----------------------------------------------------- |
|    🧠    |   `U+1F9E0`   | Construcción de modelos (estadísticos, ML)            |
|    🧪    |   `U+1F9EA`   | Pruebas de hipótesis, experimentos                    |
|    ⚖️    |   `U+2696`    | Comparación de modelos, resultados, pruebas           |
|    ✔️    |   `U+2714`    | Validación de modelos, tests significativos           |
|    ✅    |   `U+2705`    | Tests pasados, confirmaciones (alternativa a ✔️)     |

## 10. Bioinformática y Pipelines Computacionales

| Símbolo | Unicode (Hex) | Descripción Sugerida                                  |
| :-----: | :-----------: | ----------------------------------------------------- |
|    🖥️    |   `U+1F5A5`   | Scripts de cómputo intensivo, análisis en servidor    |
|    💻    |   `U+1F4BB`   | Análisis locales, scripts ejecutados en PC            |
|    🤖    |   `U+1F916`   | Procesos automatizados, pipelines                     |
|    📜    |   `U+1F4DC`   | Scripts, código fuente, archivos de log               |
|    ✒️    |   `U+2712`    | Escritura de código, desarrollo de scripts            |

## 11. Resultados, Conclusiones e Informes

| Símbolo | Unicode (Hex) | Descripción Sugerida                                  |
| :-----: | :-----------: | ----------------------------------------------------- |
|    📝    |   `U+1F4DD`   | Escritura de resúmenes, interpretación de resultados |
|    📌    |   `U+1F4CD`   | Destacar resultados clave, conclusiones importantes   |
|    🏆    |   `U+1F3C6`   | Resultados finales, hallazgos más significativos      |

## 12. Notas, Advertencias y Tareas Pendientes

| Símbolo | Unicode (Hex) | Descripción Sugerida                                  |
| :-----: | :-----------: | ----------------------------------------------------- |
|    💬    |   `U+1F4AC`   | Comentarios explicativos                              |
|    ℹ️    |   `U+2139`    | Notas informativas adicionales                        |
|    ⚠️    |   `U+26A0`    | Advertencias, posibles problemas, precauciones        |
|    ❌    |   `U+274C`    | Errores, fallos, puntos críticos                      |
|    ❗    |   `U+2757`    | Exclamación importante, error (alternativa a ❌)    |
|    ❓    |   `U+2753`    | Preguntas pendientes, áreas a investigar (negro)     |
|    ❔    |   `U+2754`    | Preguntas pendientes, áreas a investigar (blanco)    |
|   🛠️🚧   |`U+1F6A7 U+1F6A7`| Sección en construcción o incompleta (ejemplo con dos) |

## 13. Bases de Datos

| Símbolo | Unicode (Hex) | Descripción Sugerida                                  |
| :-----: | :-----------: | ----------------------------------------------------- |
|    🗄️    |   `U+1F5C4`   | Conexión o uso de bases de datos                      |
|    📚    |   `U+1F4DA`   | Referencia a grandes conjuntos de datos almacenados   |

---

**Nota:** La apariencia de estos símbolos puede variar ligeramente entre diferentes sistemas operativos y editores de texto. Se recomienda probarlos en el entorno de desarrollo para asegurar una visualización adecuada.
