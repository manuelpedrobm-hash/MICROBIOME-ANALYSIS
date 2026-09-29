# MICROBIOME-ANALYSIS

Análisis previo de los datos del nicho genital masculino y de la pareja (VB / ITS).
Esta fase es **solo análisis de datos**: no se diseña ninguna intervención ni se
trabaja sobre convocatorias. El diseño vendrá después, a partir de lo que salga aquí.

## Pregunta de partida

¿Qué propiedades del nicho peneano, medidas en los datos disponibles, se relacionan
con la persistencia y la reintroducción de bacterias asociadas a VB, y qué eslabones
de esa cadena causal no ha contrastado ningún estudio?

## Reglas de trabajo

1. **Niveles de certeza.** Toda afirmación lleva una etiqueta: `demostrado en los datos`,
   `sugerido`, `especulativo` o `no comprobado`. Ante la duda, se baja el nivel.
2. **Fuente.** Lo que viene de un paper se marca `por verificar` hasta tener la referencia
   exacta (tabla o figura). Lo que sale de nuestros datos se separa de lo que sale de la literatura.
3. **Hipótesis.** El "estado permisivo" es una hipótesis. Se nombra siempre así, y se indica
   qué la contradiría.
4. **Exploratorio frente a confirmatorio.** Una hipótesis generada con una cohorte no se
   confirma con esa misma cohorte. Cada hipótesis registra dónde se generó y dónde se contrastaría.
5. **Sin conclusiones cerradas sin aprobación.** Las fichas y conclusiones se proponen
   primero en la conversación y se commitean cuando Manuel las aprueba.
6. **Datos crudos.** No se suben al repo. Solo manifiestos y checksums en `data/`.
   Revisar las condiciones de uso de cada cohorte antes de redistribuir nada.

## Fases

| Fase | Contenido | Estado |
|------|-----------|--------|
| 0 | Auditoría de datos: qué se midió y qué es accesible | pendiente |
| 0b | Matriz de evidencia de los papers y auditoría de supuestos | en curso |
| 1 | Reproducir los CST peneanos publicados antes de criticarlos | pendiente |
| 2 | Huecos respecto a los CST | pendiente |
| 3 | Análisis por dataset (descriptivo) | pendiente |
| 4 | Cruce entre cohortes con variable preespecificada | pendiente |
| 5 | Informe | pendiente |

## Estructura

- `docs/evidence/`: una ficha por paper (ver `_template.md`)
- `docs/assumptions.md`: cadena causal y contraste de cada eslabón
- `docs/hypotheses.md`: hipótesis, exploratorias y confirmatorias
- `docs/dataset_audit.md`: tabla de la Fase 0
- `data/`: manifiestos y checksums (sin datos crudos)
- `analysis/`, `src/`: código, un directorio por fase
