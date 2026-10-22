# Project Charter — Sistema de Retención Temprana (SRT)

> Se inicia en el **Reto 00** (secciones 1–5) y se completa en el **Reto 01** (secciones 6–8).
> Nombres, roles y decisiones según el *contrato del sistema* del curso (§6.1, §9, §11).

<!-- Antes de escribir, lea la *Guía para completar el Project Charter* y el *Ejemplo de charter:
     priorización de inspecciones sanitarias* (se entregan con el Reto 00). Estos comentarios no se
     ven en GitHub; puede borrarlos cuando complete cada sección. -->

## 1. Identificación
<!-- Tabla con los seis supuestos de su variante (contrato §11): valor, unidad (miles de COP) y
     dónde vive cada uno en params.yaml. Los números deben coincidir con params.yaml (PS-4). -->
- Proyecto: SRT – Conecta Andina S.A.
- Variante (V1–V6) y segmento:
- Supuestos de la variante: `customer_value` · `contact_cost` · `retention_success_rate` · capacidad semanal (`business.weekly_capacity`) · política de equidad (`fairness.max_recall_gap_senior_citizen`) · semilla del extracto
- Equipo y roles principal / secundario (Líder/PO · Data Scientist/Steward · MLOps Engineer):
- Repositorio:

## 2. Problema de negocio y línea base
<!-- Qué decisión cambia y quién la toma · situación actual (tres reglas informales) · costo de no
     hacer nada con supuestos declarados · punto de equilibrio p* (fórmula en el Reto 00 §3.2) y qué
     restricción manda: la económica o la capacidad. p* no es el umbral de decisión. -->

## 3. ML Canvas (razonamiento de cada bloque)
<!-- Reto 00 §2.3. "Por qué está así": la restricción del negocio o del contrato que obliga al bloque,
     citando la sección (p. ej., "§5: la etiqueta llega a T + 30"). "Qué se rompería": una consecuencia
     concreta, nombrando el reto o artefacto donde aparecería. "Adaptación a la variante": qué cambia
     para su segmento (contrato §11) o "no cambia, porque…". -->
| Bloque | Canónico (resumen en una línea) | Por qué está así | Qué se rompería si fuera distinto | Adaptación a la variante |
|---|---|---|---|---|
| Propuesta de valor | | | | |
| Tarea de predicción | | | | |
| Decisiones | | | | |
| Haciendo predicciones | | | | |
| Recolección de datos | | | | |
| Fuentes de datos | | | | |
| Simulación de impacto | | | | |
| Construyendo modelos | | | | |
| Features | | | | |
| Monitoreo | | | | |

**Bloque peor justificado y por qué** ("todos están bien justificados" no cuenta):

## 4. KPIs
<!-- Un KPI por tipo. Cada línea base: número + fuente (p. ej., metrics.json del commit …) y
     "provisional" si depende del extracto. Métricas permitidas: contrato §7.3 y regla §12.6. -->
| Tipo | KPI | Línea base | Meta | Cómo se mide |
|---|---|---|---|---|
| Técnico | | | | |
| Negocio (estimado) | | | | |
| Operación | | | | |
| Gestión | | | | |

## 5. Alcance y nivel de madurez MLOps objetivo
<!-- Incluido / excluido · nivel en Google (0–2) y Microsoft (0–4) · los cinco factores aplicados a su
     variante · lo que queda manual a propósito, con responsable. -->

## 6. Roles, habilidades y RACI
(Las filas de umbral de decisión, umbrales del gate, brecha de equidad, rollback, cambio del contrato
de datos y envío de datos a un LLM externo tienen el **A** que fija el contrato §9.2.)

## 7. Backlog estimado, Definición de Terminado y cronograma

## 8. Riesgos principales
Los cinco riesgos de mayor exposición. El registro completo y vivo está en [`riesgos.md`](riesgos.md).
