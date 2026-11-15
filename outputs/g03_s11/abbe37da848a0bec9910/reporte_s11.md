# Modelo de bloques de recursos ACADÉMICO

Corrida `abbe37da848a0bec9910`. G03 DS01/EXP03; 29,952 celdas.

Cu estimado: 1379 bloques a 75 m; 795 a 50 m. Densidad estimada: 14002. Tonelaje cuantificable: 232398862.292116 t en 14002 bloques. Con Cu y tonelaje: 1079 bloques, 17407233.877413 t.

## Trazabilidad

Ensayes originales → compósitos por longitud y contacto → IDW² por código preliminar. Mo y Au se reconstruyen desde ensayes; Cu se concilia con M01. Cada estimación conserva IDs, distancias, pesos y sondajes. Densidad usa desurvey M01 y mediciones íntegramente contenidas en un dominio. Residuales se preservan en QA. Volumen: recorte de TIN por huella y límites verticales; integración analítica de planos. Se conserva el estado topográfico M01B heredado por separado. Nulo no significa cero.

## Supuestos y límites

- Litología preliminar; continuidad entre sondajes no demostrada.
- Estimación en centro como proxy académico; soporte volumétrico no corregido.
- CRS/datum topográfico no documentados; compatibilidad local heredada como supuesto.
- Incertidumbre de estimación no cuantificada por IDW².

## Verificación

`s11_validation.json` contiene controles ejecutados. La comparación manual .60 % / 2.64 t/m³ es un microcaso PT-01, no un bloque G03. La tabla completa respalda los totales; el 3D reduce contexto si excede 6000 cajas.
