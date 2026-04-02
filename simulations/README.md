# Simulaciones - ShieldAir-Mars

Esta carpeta contiene los archivos de simulación para validar la producción de oxígeno, biomasa y calor en atmósfera marciana.

## Contenido planificado

- `cfd/airflow.cas` — simulación de flujo de CO₂ en la torre.
- `bioreactor/growth_model.py` — modelo de crecimiento de algas con luz LED.
- `thermal/heat_recovery.cas` — simulación de recuperación de calor.
- `cryogenic/liquefaction.cas` — simulación de licuefacción de O₂.
- `integration/mars_base.slx` — simulación integrada con Odiseo y Goliat-Son.

## Parámetros de simulación

- Atmósfera: 95% CO₂, 2.5% N₂, 1.5% Ar, temperatura media –60°C, presión 0.6 kPa.
- Agua: extraída de hielo subterráneo (pureza >90%).
- Energía: suministrada por reactor nuclear de Odiseo (10–15 kW por torre).
- Luz LED: espectro optimizado para Scenedesmus dimorphus y Chlorella.

## Estado

- Parámetros definidos.
- Modelos pendientes de implementación.
- Validación con datos de misiones previas (Mars Reconnaissance Orbiter, Phoenix) pendiente.
