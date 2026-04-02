# Software - ShieldAir-Mars

Esta carpeta contiene el firmware y el software de control para la torre ShieldAir-Mars.

## Contenido planificado

- `firmware/compresores_control.c` — control de compresores para captura de CO₂.
- `firmware/led_control.c` — control de iluminación LED (intensidad, ciclos).
- `firmware/temperature_monitor.c` — monitoreo de temperatura en el bioreactor.
- `firmware/pressure_monitor.c` — monitoreo de presión en el sistema de licuefacción.
- `simulation/mars_atmosphere.py` — simulación de producción en atmósfera marciana.
- `dashboard/telemetry.py` — panel de monitoreo remoto (similar a Wave-Cloud).

## Estado

- Lógica de control definida.
- Código pendiente de implementación.
- Simulaciones pendientes.

## Integración

- Los datos de telemetría pueden integrarse con la plataforma Wave-Cloud (usada en ShieldAir-Urban).
