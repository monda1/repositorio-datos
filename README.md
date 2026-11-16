# Repositorio-Estadística

Cuaderno público de investigaciones estadísticas: análisis reproducibles en **R** y **Python**, informes en **R Markdown/PDF**, apuntes metodológicos y resúmenes de lo aprendido. Todo con datos abiertos, código comentado y conclusiones claras. Es a la vez portafolio y diario de aprendizaje en estadística.

---

## Objetivo

Aplicar métodos estadísticos a datos públicos reales y documentar cada paso, desde la pregunta de investigación hasta las conclusiones, de forma que cualquiera pueda **reproducir y verificar** los resultados.

## Temas y métodos

- Estadística descriptiva y exploración de datos
- Probabilidad e inferencia estadística (estimación, contrastes de hipótesis, intervalos de confianza)
- Modelos de regresión lineal y generalizada
- Series temporales y números índice
- Muestreo y encuestas
- Análisis multivariante
- Visualización de datos y comunicación de resultados

## Fuentes de datos

Los datos proceden exclusivamente de fuentes públicas y abiertas:

| Fuente | Cobertura | Web |
|---|---|---|
| **INE** | España | https://www.ine.es |
| **datos.gob.es** | Catálogo nacional de datos abiertos | https://datos.gob.es |
| **Ayuntamiento de Madrid** | Municipio y distritos de Madrid | https://datos.madrid.es |
| **Eurostat** | Unión Europea | https://ec.europa.eu/eurostat |

Cada dataset se cita con su fuente, URL exacta, fecha de descarga y licencia, y se respetan las condiciones de reutilización de cada organismo.

## Metodología de cada investigación

1. **Pregunta de investigación:** qué se quiere responder y por qué.
2. **Datos:** fuente, periodo, cobertura y variables utilizadas.
3. **Preparación:** limpieza y transformación mediante código.
4. **Análisis:** métodos aplicados y justificación de su elección.
5. **Resultados:** tablas, gráficos e interpretación.
6. **Conclusiones y limitaciones:** qué se puede afirmar y qué no.

## Reproducibilidad

- Cada investigación tiene su propio `README.md` con la pregunta, los datos usados, el método y las conclusiones.
- Las dependencias se declaran con `renv` (R) o `requirements.txt` (Python).
- Las memorias se generan a partir del código con R Markdown, de modo que los resultados siempre coinciden con el análisis.

## Herramientas

R · R Markdown · Python · Jupyter / Google Colab · Git y GitHub

