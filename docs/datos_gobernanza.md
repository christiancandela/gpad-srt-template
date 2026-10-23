# Datos y gobernanza (Reto 02)

<!-- Estructura que pide el Reto 02. Cada sección dice qué va y en qué bloque del reto se completa.
     Estos comentarios no se ven en GitHub; puede borrarlos al completar cada sección. -->

## 1. Ficha técnica recibida
<!-- Reto 02, bloque 1: copie la Ficha técnica del extracto CRM-RET tal como la recibió. No la corrija. -->

## 2. Perfil de calidad
<!-- Reto 02, bloque 2: cifras (filas afectadas y %), no adjetivos. En la versión lite, las cuatro
     primeras filas y, debajo, el resumen del contrato canónico sobre el extracto crudo. -->

| Dimensión | Regla revisada | Resultado (filas y %) | ¿Problema? |
|---|---|---|---|
| Completitud | | | |
| Validez (rangos y dominios) | | | |
| Unicidad | | | |
| Consistencia entre columnas | | | |
| Actualidad / periodo cubierto | | | |
| Plausibilidad del conjunto (tasa de `churn`) | | | |

## 3. Fuga de información
<!-- Reto 02, bloque 6 (lite: bloque 4): la columna, su cuantificación (tasa de churn según su valor)
     y la línea de tiempo corte → lote del lunes → campaña → registro → etiqueta a 30 días. -->

## 4. Contrato de datos

### 4.1 Contrato v1 según la documentación
<!-- Reto 02, bloque 3 (solo versión completa): una fila por columna de la ficha, escrita antes de
     mirar los datos, más una regla entre columnas, una del conjunto, SLA, dueño y versión. -->

| Columna | Tipo | Significado y unidad | Regla (dominio, rango, nulos) | Severidad propuesta |
|---|---|---|---|---|
| | | | | |

### 4.2 Resultado del v1 sobre el extracto
<!-- Reto 02, bloque 4: el resumen por regla de `scripts.validar_contrato v1`, sin corregir. -->

### 4.3 Negociación con el dueño del dato y tratamientos
<!-- Reto 02, bloque 5 (lite: bloque 3): una fila por defecto. Cada tratamiento aparece en
     reports/cleaning.json con el mismo conteo. -->

| Regla que falló | Filas afectadas | Hipótesis | Respuesta del dueño | Decisión | Severidad en v2 | Tratamiento |
|---|---|---|---|---|---|---|
| | | | | | | |

### 4.4 Contrato v2
<!-- Reto 02, bloque 5: resumen de las reglas bloqueantes (contracts/churn_contract.py: RC-1…RC-5,
     reglas propias y descarte máximo) y de las advertencias (contracts/crm_warnings.py). -->

## 5. Plan de gobernanza y privacidad
<!-- Reto 02, bloque 7 (lite: bloque 4, solo cinco elementos). Una a tres líneas por elemento, coherentes
     con lo implementado. Qué responde cada uno: tabla del bloque 7 del Reto 02. -->

| Elemento | Decisión |
|---|---|
| Dueño y custodio del dato | |
| Licencia y condiciones de uso | |
| Datos personales, sensibles y campo protegido | |
| Finalidad autorizada | |
| Minimización | |
| Seudonimización | |
| Política de acceso al remoto | |
| Retención | |
| Linaje | `dvc dag` |
