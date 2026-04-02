# ShieldAir-Mars: Oxígeno, biomasa y calor desde la atmósfera marciana

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19357867.svg)](https://doi.org/10.5281/zenodo.19357867)
[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](LICENSE)
[![EN](https://img.shields.io/badge/English-version-blue.svg)](./README.en.md)

En Marte, la atmósfera es 95% dióxido de carbono (CO₂). No hay oxígeno para respirar, ni agua líquida en la superficie, ni biomasa para alimentarse. Cualquier misión tripulada necesita producir estos recursos localmente.

ShieldAir-Mars nace para resolver ese problema.

## Que hace

ShieldAir-Mars es una torre modular adaptada de la versión terrestre (ShieldAir-Urban). En Marte, convierte el CO₂ atmosférico en recursos vitales usando energía nuclear, luz LED y agua extraída del hielo marciano.

Produce por torre:
- Oxígeno (O₂): 0.8 toneladas/día para respiración y como oxidante para Goliat-Son.
- Biomasa (algas): 15 kg/día para alimento, bioplásticos y fertilizantes.
- Calor: 60–80 kW térmicos para calefacción y derretimiento de hielo.

## Como funciona

1. Captura: compresores aspiran aire marciano (95% CO₂).
2. Fotosíntesis: algas (Scenedesmus dimorphus, Chlorella) convierten CO₂ + agua + luz LED en oxígeno y biomasa.
3. Licuefacción: enfriamiento criogénico para producir oxígeno líquido (LOX).
4. Procesamiento de biomasa: secado, prensado, fermentación para obtener proteína, lípidos y bioplásticos.
5. Recuperación de calor: intercambiadores de calor para calefacción y derretimiento de hielo.

## Integración con Odiseo y Goliat-Son

- Odiseo: energía nuclear alimenta las torres; calor recuperado se usa en la base.
- Goliat-Son: reabastece sus tanques de O₂ con LOX producido por las torres.
- Base marciana: O₂ para respirar, calor para hábitats, biomasa para alimento y plásticos.

## Escalabilidad

Para la primera base marciana (6 personas), se requieren 2 torres ShieldAir operando continuamente:
- Producción total: 1.6 toneladas O₂/día.
- Excedente de biomasa: 30 kg/día.
- Calor: 120–160 kW térmicos.

## Estado actual

- Concepto adaptado de versión terrestre.
- Especificaciones técnicas definidas.
- Integración con Odiseo y Goliat-Son documentada.
- Modelado CAD de la torre (pendiente).
- Simulación de producción en atmósfera marciana (pendiente).

## Proyectos relacionados

- ShieldAir-Urban — versión terrestre original.
- Odiseo — nave de infraestructura para colonizar Marte.
- Goliat-Son — aterrizador autónomo.


## Estructura del repositorio

- `/cad` — diseños mecánicos de la torre.
- `/docs` — documentación técnica y conceptual.
- `/hardware` — esquemas eléctricos y mecánicos.
- `/software` — firmware y software de control.
- `/simulations` — modelos de simulación de producción.
- `/business` — análisis financiero y modelo de negocio.
- `/certifications` — planes de certificación para equipos espaciales.


## Licencia

Copyright © 2026 Enrique Aguayo. Todos los derechos reservados.

[Texto de licencia propietaria estándar...]

## Autor

Enrique Aguayo H.
Mackiber Labs
Contacto: eaguayo@migst.cl
ORCID: 0009-0004-4615-6825
GitHub: @enriqueherbertag-lgtm

Documentación asistida por Ana (DeepSeek), IA para investigación y optimización técnica.
