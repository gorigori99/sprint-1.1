# 🛒 Store 1 - Evaluación y Limpieza de Datos de Usuarios/as

## 🎯 Objetivos del Proyecto

- Garantizar la **integridad y consistencia** de los datos de usuarios/as.
- Identificar y corregir errores comunes como:
  - Tipos de datos incorrectos.
  - Formato inconsistente de nombres y categorías.
  - Valores faltantes o no convertibles.
- Automatizar procesos de **validación de datos**.
- Calcular **métricas clave de gasto** por usuario/a.
- Identificar **patrones** y **segmentar usuarios/as** según edad y comportamiento de compra.

---

## 🧰 Herramientas y Tecnologías

- **Lenguaje:** Python

### Conceptos clave

- Manejo de cadenas: `.strip()`, `.split()`, `.replace()`
- Conversión de tipos: `int()`, `try-except`
- List comprehension y `map()`
- Control de flujo: `if`, `while`, `for`
- Estructuras de datos: **listas anidadas**
- Funciones agregadas: `sum()`, `max()`, `min()`

---

## 🧪 Ejercicios y Soluciones Implementadas

| Ejercicio | Tema                        | Descripción                                         |
|-----------|-----------------------------|-----------------------------------------------------|
| 1         | Limpieza de `user_name`     | Eliminación de espacios y reemplazo de guiones bajos |
| 2         | Separación nombre/apellido  | Uso de `.split()`                                   |
| 3-4       | Validación de edad          | Conversión segura a `int` con manejo de errores     |
| 5         | Estandarización de texto    | Conversión de categorías favoritas a minúsculas     |
| 6         | Métricas de gasto           | Cálculo de total, máximo y mínimo gasto             |
| 7         | Simulación de compras       | Uso de `while` con `randint()`                      |
| 8         | Formateo de datos           | Creación de `f-string` para salida formateada       |
| 9         | Ingresos totales            | Suma total de gastos por usuario/a                  |
| 10        | Filtros por edad            | Usuarios/as menores de 30 años                      |
| 11        | Filtros combinados          | Edad < 30 **y** gasto > $1000                       |
| 12        | Filtro por categoría        | Usuarios/as que compraron ropa                      |

---

## 📈 Ejemplo de salida (Ejercicio 12)

```text
kate morgan ,  24  
samantha smith ,  29  
maria garcia ,  33  
lisa wilson ,  35  
james lee ,  28
📝 Conclusión
Este proyecto muestra cómo pequeños errores en la recopilación de datos pueden afectar el análisis, y cómo aplicar buenas prácticas de limpieza y validación puede marcar la diferencia.

Las habilidades desarrolladas aquí sientan las bases para tareas más complejas como:

Modelado de datos

Segmentación de clientes

Visualización de insights para la toma de decisiones


.
