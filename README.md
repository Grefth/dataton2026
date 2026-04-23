# Dataton Sonora — Educación

## Historia Central
> *"Sonora avanza, pero pierde estudiantes en el camino."*

El estado ha mejorado su escolaridad promedio de 8.2 a 10.4 años (2000–2020), pero hay fugas críticas en el pipeline educativo — desde preescolar hasta universidad — con brechas municipales profundas y un impacto directo en los ingresos laborales.

---

## Dashboards

### Dashboard 1 — "El Sonora que viene" (Contexto demográfico)
Muestra la presión demográfica sobre el sistema educativo como punto de entrada al problema.
- Gráfica de barras: nacimientos 2010–2024 con tendencia
- KPI: -36% nacimientos en 14 años
- Proyección: cuántos alumnos esperará el sistema en 2030

### Dashboard 2 — "El embudo roto" (Pipeline educativo)
Visualiza dónde se pierde cada generación de sonorenses en su trayectoria escolar.
- Funnel/Sankey: preescolar → primaria → secundaria → prepa → universidad
- Línea de tiempo: tasas de absorción y matriculación 1990–2024 por nivel
- Comparativo Sonora vs. media nacional en cada transición
- Impacto COVID visible como anotación en la línea de tiempo

### Dashboard 3 — "Los que se quedan atrás" (Desigualdad municipal)
Mapa de calor de los 72 municipios de Sonora — identifica zonas de intervención urgente.
- Mapa coroplético municipal (2015 vs. 2020)
- Ranking top 10 municipios con mayor brecha
- Overlay de becas: municipios con/sin cobertura vs. tasa de asistencia escolar

### Dashboard 4 — "El costo de no estudiar" (Retorno económico)
Conecta educación con ingreso laboral para justificar la inversión en retención.
- Pirámide: distribución de población ocupada por tramo salarial (≤1 SM hasta >5 SM)
- Correlación: grado promedio de escolaridad vs. % población con ingresos >3 SM
- Impacto de becas: indicadores laborales en cohortes con/sin acceso a becas
- Proyección: beneficio económico si Sonora sube eficiencia terminal de 63% → 80%

---

## Datos disponibles

| Archivo | Indicador | Período | Granularidad |
|---|---|---|---|
| `Natalidad_2010_2024.csv` | Nacimientos registrados por sexo | 2010–2024 | Anual / Estatal |
| `absorcionPrepa.CSV` | Tasa de absorción EMS (%) | 2000–2024 | Anual / Nacional + Estados |
| `absorcionPrimaria.CSV` | Absorción primaria → secundaria (%) | 1990–2024 | Anual / Nacional + Estados |
| `absorcionSecuendaria.CSV` | Tasa de absorción secundaria (%) | 2000–2024 | Anual / Nacional + Estados |
| `absorcionUniversidad2000-2025.csv` | Tasa de absorción universitaria (%) | 2000–2025 | Ciclos seleccionados |
| `matriculacion secundaria 12-14.CSV` | Matriculación neta secundaria 12–14 años (%) | 1990–2024 | Anual / Nacional + Estados |
| `matriculacionPrescolar3-5.CSV` | Matriculación neta preescolar 3–5 años (%) | 1990–2024 | Anual / Nacional + Estados |
| `matriculacionPrimaria6-11.CSV` | Matriculación neta primaria 6–11 años (%) | 1990–2024 | Anual / Nacional + Estados |
| `areaGeografica.csv` | Asistencia escolar 15–24 años por municipio | 2015, 2020 | Municipal / Sonora |
| `entidadFederativa.csv` | Eficiencia terminal EMS Sonora (%) | 2000–2021 | Anual / Estatal |
| `gradoPromedioEntre15+.csv` | Grado promedio de escolaridad 15+ años | 2000–2020 | Quinquenal / Estatal |
| `PoblaciónEconomicaActiva15+.csv` | Indicadores laborales por tramo salarial | 2005–2024 | Trimestral / Nacional + Estados |

---

## Propuestas de política

1. **Focalizar recursos** en municipios con peor asistencia escolar (identificados en Dashboard 3)
2. **Programas de retención en preparatoria** — eficiencia terminal estancada en 63–67%
3. **Ampliar absorción universitaria** aprovechando la caída demográfica como ventana de oportunidad