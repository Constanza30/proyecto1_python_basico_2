# 📊 Proyecto 2: Limpieza, Transformación y Análisis de Datos de Clientes (Python)

## 🧩 Descripción del proyecto
Este proyecto forma parte del **Bootcamp de Análisis de Datos de TripleTen** y se enfoca en la **limpieza, estandarización y análisis de datos de clientes** de una empresa ficticia (*Store 1*).

El objetivo principal es transformar datos crudos e inconsistentes en información estructurada y confiable, aplicando **funciones, bucles, condicionales y buenas prácticas en Python**, simulando un flujo de trabajo real de análisis de datos.

---

## 🎯 Objetivos del proyecto
- Limpiar y estandarizar datos de clientes (nombres, edades y categorías).
- Diseñar **funciones reutilizables** para el procesamiento de datos.
- Garantizar consistencia en formatos y tipos de datos.
- Calcular métricas clave como ingresos totales.
- Filtrar clientes según reglas de negocio específicas.
- Extraer información relevante para la toma de decisiones.

---

## 🗂️ Estructura de los datos
Cada usuario está representado como una lista con la siguiente estructura:

1. `user_id`: Identificador único del cliente  
2. `user_name`: Nombre y apellido  
3. `user_age`: Edad del cliente  
4. `fav_categories`: Categorías de compra  
5. `total_spendings`: Gasto por categoría

---
## 🧼 Procesos de limpieza de datos

Se implementó una función principal llamada clean_user(), la cual:

- Convierte nombres a minúsculas.
- Elimina espacios innecesarios y guiones bajos.
- Separa nombre y apellido en sublistas.
- Convierte la edad a tipo entero.
- Normaliza las categorías de compra a minúsculas.
- Devuelve una lista limpia y estructurada.

Estos pasos se aplicaron a toda la base de usuarios, generando una nueva lista users_cleaned.

---

## 🔁 Transformaciones y lógica aplicada

Durante el proyecto se aplicaron:

- Bucles for para iterar sobre usuarios y categorías.

- Condicionales if y operadores lógicos para filtrar información.

- Funciones personalizadas para reutilizar lógica.

- Métodos integrados como:

  - strip(), replace(), split(), lower()

  - append(), sum()

Control de tipos de datos (int).

---

## 📈 Análisis realizados

- Cálculo del ingreso total de la empresa a partir del gasto de todos los clientes.

- Identificación de clientes menores de 30 años.

- Filtrado de clientes leales según gasto acumulado.

- Identificación de clientes que compraron en categorías específicas (ej. clothes, home).

- Creación de la función get_client_by_cat() para obtener clientes filtrados por categoría junto con su gasto total.

---

## 🛠️ Herramientas y tecnologías utilizadas

1. Python 3

2. Jupyter Notebook

3. Listas y listas anidadas

4. Funciones personalizadas

5. Bucles (for, while)

6. Condicionales

7. Lógica de negocio aplicada a datos

---

## ✅ Resultados clave

- Datos completamente limpios, estandarizados y listos para análisis.

- Funciones reutilizables para limpieza y filtrado de clientes.

- Obtención de métricas clave para el negocio.

- Simulación de un flujo real de trabajo de análisis de datos.

---

## 🚀 Aprendizajes y siguientes pasos

- Migrar la estructura de listas a diccionarios o DataFrames (Pandas).

- Automatizar procesos con funciones más robustas.

- Incorporar análisis exploratorio y visualizaciones.

- Escalar el análisis a volúmenes de datos mayores.
