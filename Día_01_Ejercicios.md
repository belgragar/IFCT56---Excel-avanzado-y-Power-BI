---

## 14. Ejercicios de dificultad creciente

1. **Básico:** Asigna el nombre `Tipo_IVA` a la celda `E1` (que contiene el valor `0,21`) y calcula el IVA del importe ubicado en `B2` usando ese nombre dentro de la fórmula.
2. **Intermedio:** Aplica un formato personalizado a la columna de teléfonos de forma que los números de 9 dígitos se muestren automáticamente formateados con el estilo `(###) ##-##-##`.
3. **Avanzado:** Configura una regla de formato condicional mediante fórmulas en el rango `A2:E20` para destacar de color amarillo suave las filas cuya fecha de vencimiento sea anterior a la fecha actual (`=HOY()`).

---

## 15. Práctica guiada paso a paso

### Objetivo: Crear un listado con avisos automáticos de impago

1. Diseña una hoja con las siguientes columnas: `Cliente`, `Factura`, `Importe`, `Estado`.
2. Asigna el nombre `Listado_Facturas` al rango que contiene la columna de importes.
3. Selecciona las celdas del `Importe` y aplica el formato personalizado:
`#.##0,00 "€";[Rojo]-#.##0,00 "€";"-"`
4. Selecciona toda la tabla (rango `A2:D15`).
5. Ve a **Formato Condicional** > **Nueva Regla** > **Utilice una fórmula...**
6. Escribe la fórmula:
`=$D2="Pendiente"`
7. Elige un color de relleno rojo claro en el botón **Formato...** y haz clic en **Aceptar**.

---

## 16. Reto profesional

Trabajas en el departamento de Recursos Humanos de una empresa de servicios. Te entregan una hoja con 300 empleados. Debes aplicar un formato condicional a cada fila completa para que:

1. Si los días de vacaciones pendientes son superiores a 15, la fila se muestre en verde suave.
2. Si el empleado tiene contrato de tipo "Temporal" y su antigüedad es superior a 2 años, la fila se muestre en naranja suave como aviso de revisión contractual.

---

## 17. Proyecto integrador

**Mini-proyecto: Plantilla de Control de Presupuesto Mensual**
Crea una plantilla interactiva que incluya:

* Nombres de rangos definidos para `Ingresos`, `Gastos_Fijos` y `Gastos_Variables`.
* Formatos personalizados para presentar códigos de proyecto con la estructura `PRJ-0000`.
* Reglas de formato condicional avanzadas que cambien la celda de balance a verde si el saldo es positivo, o a rojo con alerta si las desviaciones superan el 10% del presupuesto estimado.

---

## 18. Autoevaluación

### Respuesta corta

1. ¿Qué tecla rápida abre el panel de Formato de Celdas?
2. ¿Qué carácter se utiliza en las máscaras de formato personalizado para representar un dígito obligatorio?

### Desarrollo

1. Explica la diferencia entre cambiar el valor de una celda y aplicar un formato personalizado. Proporciona un ejemplo práctico donde esta diferencia sea relevante.

### Tipo test

1. ¿Cuál de los siguientes nombres es un nombre de rango VÁLIDO en Excel?
* a) `Ventas 2026`
* b) `12_Ventas`
* c) `Ventas_2026`
* d) `A1`


2. En la estructura de un formato personalizado de 4 secciones (`Sección1; Sección2; Sección3; Sección4`), ¿qué tipo de datos regula la segunda sección?
* a) Valores positivos.
* b) Valores negativos.
* c) Valores igual a cero.
* d) Textos.


3. Al crear una regla de formato condicional basada en fórmulas para colorear una FILA COMPLETA, ¿cómo debemos referenciar la celda evaluada?
* a) `A1` (referencia relativa)
* b) `$A$1` (referencia absoluta)
* c) `$A1` (fijando solo la columna)
* d) `A$1` (fijando solo la fila)



---

### Soluciones a las preguntas tipo test:

1. **c) Ventas_2026** (los nombres no pueden contener espacios, empezar con números ni coincidir con referencias de celdas).
2. **b) Valores negativos** (la secuencia oficial es: Positivos; Negativos; Ceros; Texto).
3. **c) $A1** (se fija la columna mediante `$` para evaluar la condición horizontalmente en toda la fila).
