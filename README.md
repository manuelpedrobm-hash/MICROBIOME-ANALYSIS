# MICROBIOME-ANALYSIS

Análisis previo de los datos del microbioma en el contexto de la **recurrencia de la
vaginosis bacteriana en la mujer**. Esta fase es **solo análisis de datos**: no se diseña
ninguna intervención ni se trabaja sobre convocatorias.

## Foco (29 sep 2026)

El desenlace que importa es la recurrencia en la mujer. El punto de partida son las
cohortes de Monash (grupo Bradshaw): los dos pilotos de tratamiento concurrente de la
pareja y el ensayo StepUp. El resto de estudios (Galiwango, Rakai, Park, Kisumu) quedan
archivados para una comparación posterior, no para empezar.

Matiz que conviene no perder: el **desenlace** es femenino, pero el **análisis** no puede
usar solo muestras de la mujer. Describir la recaída vaginal sin ningún dato de la
exposición o de la pareja reproduce lo que ya está publicado. Lo que no está resuelto es
qué parte de esa recaída viene de fuera, y eso exige el eje diádico.

## Pregunta de partida

Tras el tratamiento de la VB, ¿qué distingue a las mujeres que recaen de las que no, y
qué parte de esa diferencia se explica por lo que ocurre en la pareja?

## Reglas de trabajo

1. **Niveles de certeza.** Toda afirmación lleva etiqueta: `demostrado en los datos`,
   `sugerido`, `especulativo` o `no comprobado`. Ante la duda, se baja el nivel.
2. **Fuente.** Lo que viene de un paper se marca `por verificar` hasta tener la referencia
   exacta (tabla o figura). Lo de nuestros datos se separa de lo de la literatura.
3. **Hipótesis.** Se nombran como hipótesis, nunca como hallazgo, y se indica qué las contradiría.
4. **Exploratorio frente a confirmatorio.** Una hipótesis generada con una cohorte no se
   confirma con esa misma cohorte.
5. **Sin conclusiones cerradas sin aprobación.** Las fichas y conclusiones se proponen
   primero en la conversación.
6. **Datos crudos.** No se suben. Solo manifiestos y checksums en `data/`.

## Fases

| Fase | Contenido | Estado |
|------|-----------|--------|
| 0 | Auditoría de acceso: qué datos existen y cuáles se pueden descargar | en curso |
| 1 | Fichas de evidencia de las tres cohortes de Monash | pendiente |
| 2 | Reanálisis del piloto de 2018 (el único con datos públicos localizados) | bloqueado por Fase 0 |
| 3 | Dinámica de la recaída: qué precede a la recurrencia | pendiente |
| 4 | Comparación con el resto de cohortes | aparcado |
| 5 | Informe | pendiente |

## Hallazgo operativo de la Fase 0

Los datos individuales de StepUp **no son públicos**. El protocolo dice que no se
publicarán por su carácter sensible y que puede facilitarse información limitada a
petición al autor de correspondencia. Por tanto StepUp se puede leer, pero no reanalizar,
salvo acuerdo con Monash. Ver `docs/dataset_audit.md`.

## Estructura

- `docs/evidence/`: una ficha por paper (ver `_template.md`)
- `docs/assumptions.md`: cadena causal y contraste de cada eslabón
- `docs/hypotheses.md`: hipótesis, con cohorte de generación y de contraste
- `docs/dataset_audit.md`: qué existe y qué es accesible
- `data/`: manifiestos y checksums (sin datos crudos)
- `analysis/`, `src/`: código
