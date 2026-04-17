# Contexto clínico — Roberto Lomelí
> Prompt de continuidad para nueva conversación

---

## Instrucciones para el asistente

Estoy trabajando en un proyecto para ayudar a médicos analizando historiales clínicos de pacientes sin diagnóstico definitivo. El objetivo es estructurar la información de forma clara para que cualquier médico pueda entender el caso rápidamente y no perder tiempo recabando el historial desde cero.

Ya tenemos un historial clínico completo estructurado en HTML (versión 1.1, abril 2026) para el paciente Roberto Lomelí. Continuamos actualizando ese documento conforme llegan nuevos estudios o consultas.

**Reglas de formato del documento:**
- No usar frases relativas como "hace 3 meses", "hace 12 meses", "hoy". Siempre reemplazar por la fecha concreta (ej. "enero 2026", "abril 2025").
- El archivo de salida es un HTML autocontenido, exportable, con diseño clínico limpio (fuente IBM Plex Sans/Mono, sin dependencias externas salvo Google Fonts).

---

## Datos del paciente

**Nombre:** Roberto Lomelí  
**Sexo:** Masculino  
**Fecha de nacimiento:** 18 de diciembre de 1967  
**Edad actual:** 58 años (57 al inicio de síntomas)  
**Ubicación:** Guadalajara, Jalisco, México  

---

## Resumen clínico

**Estatus:** Sin diagnóstico definitivo. Síntomas activos desde mayo 2025 (~11 meses).  
**Hipótesis principal no confirmada ni descartada:** Síndrome de silla turca vacía secundaria con hipopituitarismo parcial.  
**Problema central:** El aracnoidocele selar grado II (hipófisis comprimida al 50%) fue evaluado únicamente por neurocirugía en junio 2025 ("sin hallazgos importantes") y nunca fue estudiado con panel hipofisario completo. El endocrinólogo que lo vio en enero 2026 enfocó la consulta exclusivamente en la prediabetes.

---

## Síntomas actuales

- Mareos — desde mayo 2025, fluctuantes ("montaña rusa"), 11 meses de evolución
- Fatiga intensa — persistente, limitante
- Debilidad generalizada — sin dolor
- Hormigueos en cabeza — sin focalidad neurológica
- Piel seca
- Libido bajo — sin disfunción eréctil
- Pérdida de peso: −6 kg desde mayo 2025 (paciente deportista de alto rendimiento)
- Episodios hipoglucémicos repetidos — mayo a diciembre 2025, en paciente sin hipoglucemiantes

---

## Antecedentes relevantes

- Fumador activo desde los 23 años, 2 cajetillas/día (35 años de tabaquismo)
- Exalcohólico — cese aproximadamente 2024
- Úlcera gástrica resuelta quirúrgicamente
- Acidez crónica recurrente
- Estrés acumulado
- Deportista de alto rendimiento, ejercicio diario
- Dieta previa deficiente; dieta actual equilibrada, 2500 kcal/día
- Hidratación insuficiente: ~1 L/día

**Composición corporal (junio 2025):**  
Peso 70 kg · Grasa 12.8% (9.0 kg) · Músculo 45.2% (31.7 kg) · ICC 0.81 · Cintura 75 cm

---

## Medicamentos

| Medicamento | Período | Estado |
|---|---|---|
| Wegovy | Abril–junio 2025 (8 semanas) | Discontinuado |
| Metformina | Junio 2025 (10 días) | Discontinuado |
| Metformina | Febrero 2026 (13 días) | Discontinuado |
| Escitalopram | Julio 2025 | Discontinuado |
| Clonazepam | Julio 2025 – presente | **Activo** |
| Desvenlafaxina | Septiembre 2025 | Discontinuado |

> Nota: Clonazepam activo puede superponer síntomas (fatiga, mareos, debilidad) con el cuadro principal y confundir la evaluación clínica.

---

## Estudios de imagen

**RMN Cráneo Simple — 28 junio 2025**
1. Quiste aracnoideo retrocerebeloso izquierdo — 2.3 × 1.6 cm
2. **Aracnoidocele selar grado II** — hipófisis comprimida al 50% ← hallazgo clave no seguido endocrinológicamente
3. Asa vascular ángulo pontocerebeloso derecho — Chavda tipo 1, sobre complejo VII–VIII
- Evaluado por neurocirugía. Conclusión: "sin hallazgos importantes". Sin derivación a endocrinología.

**Tele de Tórax**
- Aortoesclerosis · Disminución de radiopacidad ósea · Osteoartrosis dorsal · Aorta elongada descendente · ICT 0.42

---

## Laboratorio — evolución de parámetros relevantes

| Parámetro | May 2025 | Feb 2026 | Abr 2026 | Referencia |
|---|---|---|---|---|
| Plaquetas | 215 | **119 ↓↓** | 144 ↓ | 163–337 k/µL |
| VCM | 93.8 ↑ | 94.6 ↑ | 93.2 | 79–92 fL |
| T3 Total | 0.93 | **0.63 ↓** | — | 0.80–2.00 ng/mL |
| T3 Libre | 2.77 | 2.41 ↓ | — | 2.00–4.40 pg/mL |
| TSH | 2.600 | 2.970 | — | 0.270–4.200 µUI/mL |
| Hierro sérico | 138.6 | 76.4 ↓ | — | 33–193 µg/dL |
| Albúmina | 4.44 | 3.84 ↓ | — | 3.97–4.94 g/dL |
| Ácido úrico | 5.8 | **7.8 ↑** | — | 3.4–7.0 mg/dL |
| HDL Colesterol | **29.8 ↓↓** | 68.4 ✓ | — | ≥55 mg/dL |
| Triglicéridos | **205.7 ↑↑** | 105 ✓ | — | <150 mg/dL |
| HbA1c | 6.0% | 6.2% | — | ≤5.7% |
| BUN | 18.0 | 19.1 | 23.4 ↑ | 6–20 mg/dL |
| AST (TGO) | 34.6 | 37.2 ↑* | — | 10–35 U/L |
| Glucosa | 111 ↑ | 107 ↑ | 92 ✓ | 74–106 mg/dL |

**Laboratorio hormonal — 29 mayo 2025:**

| Parámetro | Resultado | Referencia | Nota |
|---|---|---|---|
| TSH | 2.600 µUI/mL | 0.270–4.200 | Normal; TSH puede ser inapropiadamente normal en hipotiroidismo central |
| Cortisol sérico | 20.40 µg/dL | ~10–25 matutino | Normal matutino; no descarta insuficiencia suprarrenal central parcial. Requiere prueba de estimulación con ACTH |
| Insulina sérica | 3.58 µIU/mL ↓* | 2.60–24.90 | Límite inferior; descarta hiperinsulinismo como causa de hipoglucemias |

**Biometría hematológica febrero 2026 — hallazgo notable:**
- Plaquetas 119k con macroplaquetas moderadas en frotis. No se observaron cúmulos plaquetarios. Estudio verificado.

---

## Especialistas consultados

| Especialidad | Fecha | Resultado |
|---|---|---|
| Neurología | Abril 2025 | Sin seguimiento activo |
| Neurocirugía | Junio 2025 | RMN evaluada; "sin hallazgos importantes"; sin derivación |
| Psiquiatría | Julio–septiembre 2025 | Manejo sintomático |
| Endocrinología | Enero 2026 | Enfoque exclusivo en prediabetes; sin panel hipofisario |
| Hematología | Abril 2026 | Consulta por trombocitopenia — resultados pendientes |

---

## Estudios pendientes prioritarios

**Prioridad 1 — Endocrinología (panel hipofisario):**
- Cortisol basal 8 am ± prueba de estimulación con ACTH
- Testosterona total + libre · LH · FSH
- IGF-1 · GH basal
- Prolactina
- RMN hipofisaria con gadolinio

**Prioridad 1 — Hematología (trombocitopenia):**
- Frotis periférico completo
- ANA · anti-DNA · complemento C3/C4
- Ferritina · TIBC
- Considerar aspirado de médula ósea

**Prioridad 2:**
- Vitamina B12 y folato sérico
- Vitamina D
- Testosterona (si no incluida en panel hipofisario)

---

## Correlación clínica — por qué se sospecha hipopituitarismo parcial

1. **T3 total bajo (0.63) con TSH normal** — patrón de hipotiroidismo central, no primario
2. **Hipoglucemias repetidas sin hipoglucemiantes, con insulina en límite inferior** — mecanismo compatible con déficit de cortisol o GH bajo demanda metabólica
3. **Pérdida de 6 kg en deportista con 2500 kcal/día** — compatible con déficit de GH o hipocortisolismo crónico
4. **Libido bajo sin disfunción eréctil** — patrón de déficit gonadotrópico (testosterona no medida)
5. **Piel seca persistente** — déficit de GH o hipotiroidismo central
6. **Fatiga y debilidad con composición corporal óptima** — no explicable por desacondicionamiento
7. **Síntomas fluctuantes 11 meses** — compatible con insuficiencia hipofisaria parcial intermitente

---

## Archivo HTML del historial

El historial estructurado está en un archivo HTML (versión 1.1) que se actualiza con cada nueva información. Cuando el usuario comparta nuevos estudios o resultados de consultas, se debe:
1. Integrar los datos al documento HTML existente
2. Actualizar la sección de estudios pendientes según corresponda
3. Ajustar la hipótesis diagnóstica si los nuevos datos la refuerzan o modifican
4. Mantener la regla de fechas concretas (sin frases relativas)
