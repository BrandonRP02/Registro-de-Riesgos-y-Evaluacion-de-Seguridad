# Registro de Riesgos y Evaluación de Seguridad

## Resumen Ejecutivo

En este documento se detalla la **evaluación integral de riesgos** del entorno operativo actual del banco comercial. El propósito de este registro es proporcionar una clasificación estructurada de las vulnerabilidades que amenazan los fondos y datos institucionales, permitiendo al equipo de ciberseguridad **priorizar recursos de manera efectiva**.

---

## 1. Análisis del Entorno Operativo

El entorno operativo del banco presenta características específicas que moldean su perfil de riesgo:

- El banco está situado en una **zona costera** que históricamente presenta bajos índices de delincuencia.
-  La fuerza laboral consta de **100 empleados presenciales** y **20 empleados remotos**, ampliando la superficie de ataque.
-  La base de clientes está compuesta por **2.000 cuentas individuales** y **200 cuentas comerciales** que requieren protección de datos rigurosa.
- El cumplimiento normativo es estricto, exigiendo la **disponibilidad ininterrumpida de efectivo diario** para cumplir con los mandatos de la Reserva Federal.

---

## 2. Metodología de Evaluación de Riesgos

La puntuación global del riesgo (**Prioridad**) se calcula utilizando la fórmula estándar de la industria:

> **Prioridad = Probabilidad × Gravedad**

| Escala | Valor | Descripción |
|--------|:-----:|-------------|
| **Probabilidad** | 1 | Baja probabilidad o frecuencia poco común |
| | 2 | Probabilidad moderada |
| | 3 | Alta probabilidad o evento inminente/frecuente |
| **Gravedad** | 1 | Impacto menor |
| | 2 | Impacto moderado en las operaciones o finanzas |
| | 3 | Impacto catastrófico, violación regulatoria severa o interrupción total |

---

## 3. Matriz del Registro de Riesgos

| Activo | Riesgo(s) | Descripción | Probabilidad | Gravedad | Prioridad |
|--------|-----------|-------------|:------------:|:--------:|:---------:|
| Fondos / Información | Compromiso del correo electrónico empresarial | Un empleado es engañado para compartir información confidencial. | 3 | 3 | ** 9** |
|  Registros / Datos | Fuga de registros financieros | Un servidor de bases de datos con copias de seguridad es accesible públicamente. | 3 | 3 | **9** |
| Datos de Clientes | Base de datos de usuarios comprometida | Los datos de los clientes están mal encriptados. | 2 | 3 | ** 6** |
|  Fondos Físicos | Robo | La caja fuerte del banco se deja abierta. | 1 | 3 | ** 3** |
| Operaciones / Fondos | Interrupción de la cadena de suministro | Retrasos en las entregas debido a desastres naturales. | 1 | 3 | ** 3** |

> [!IMPORTANT]
> Los riesgos con prioridad **9** requieren atención inmediata y planes de mitigación prioritarios.

---

## 4. Notas y Justificación de Riesgos

### ¿Cómo son posibles los eventos de seguridad considerando los riesgos a los que se enfrentan los activos en su entorno operativo?

Los eventos de seguridad son viables principalmente por:

1. **Vulnerabilidad humana:** Los 120 empleados — especialmente aquellos en modalidad remota — son susceptibles a sofisticados ataques de **ingeniería social**.
2. **Negligencias técnicas:** Configuraciones críticas deficientes en servidores de acceso público exponen datos sensibles.
3. **Riesgo ambiental:** Aunque los índices de delincuencia local son bajos, la **ubicación costera** expone inevitablemente al banco a desastres naturales severos que pueden interrumpir la cadena de suministro, afectando la logística y amenazando el cumplimiento de las estrictas **normativas de liquidez de la Reserva Federal**.

---

> *Documento elaborado como parte de una evaluación de ciberseguridad institucional.*
