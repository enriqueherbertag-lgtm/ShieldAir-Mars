# ShieldAir-Mars: Oxygen, biomass, and heat from the Martian atmosphere

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19357867.svg)](https://doi.org/10.5281/zenodo.19357867)
[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](LICENSE)
[![ES](https://img.shields.io/badge/Spanish-version-green.svg)](./README.md)

On Mars, the atmosphere is 95% carbon dioxide (CO₂). There is no oxygen to breathe, no liquid water on the surface, and no biomass to feed on. Any crewed mission needs to produce these resources locally.

ShieldAir-Mars was created to solve that problem.

## What it does

ShieldAir-Mars is a modular tower adapted from the terrestrial version (ShieldAir-Urban). On Mars, it converts atmospheric CO₂ into vital resources using nuclear energy, LED lighting, and water extracted from Martian ice.

Produces per tower:
- Oxygen (O₂): 0.8 tons/day for breathing and as oxidizer for Goliat-Son.
- Biomass (algae): 15 kg/day for food, bioplastics, and fertilizers.
- Heat: 60–80 kW thermal for heating and ice melting.

## How it works

1. Capture: compressors draw Martian air (95% CO₂).
2. Photosynthesis: algae (Scenedesmus dimorphus, Chlorella) convert CO₂ + water + LED light into oxygen and biomass.
3. Liquefaction: cryogenic cooling to produce liquid oxygen (LOX).
4. Biomass processing: drying, pressing, fermentation to obtain protein, lipids, and bioplastics.
5. Heat recovery: heat exchangers for heating and ice melting.

## Repository structure

- `/cad` — mechanical designs of the tower.
- `/docs` — technical and conceptual documentation.
- `/hardware` — electrical and mechanical schematics.
- `/software` — firmware and control software.
- `/simulations` — production simulation models.
- `/business` — financial analysis and business model.
- `/certifications` — certification plans for space equipment.

## Integration with Odiseo and Goliat-Son

- Odiseo: nuclear energy powers the towers; recovered heat is used in the base.
- Goliat-Son: replenishes its O₂ tanks with LOX produced by the towers.
- Martian base: O₂ for breathing, heat for habitats, biomass for food and plastics.

## Scalability

For the first Martian base (6 people), 2 ShieldAir towers are needed:
- Total production: 1.6 tons O₂/day.
- Biomass surplus: 30 kg/day.
- Heat: 120–160 kW thermal.

## Current status

- Concept adapted from terrestrial version.
- Technical specifications defined.
- Integration with Odiseo and Goliat-Son documented.
- CAD modeling of the tower (pending).
- Production simulation in Martian atmosphere (pending).

## Related projects

- ShieldAir-Urban — original terrestrial version.
- Odiseo — infrastructure spacecraft for colonizing Mars.
- Goliat-Son — autonomous lander.

## License

Copyright © 2026 Enrique Aguayo. All rights reserved.

This project is protected by copyright.

PERMITTED:
- Non-commercial use for educational or research purposes.
- Distribution without modification, as long as this license is maintained and credit is given to the author.

PROHIBITED without express written authorization:
- Commercial use (including, but not limited to: offering it as a service, SaaS, subscription, integration into revenue-generating products, or any use that generates direct or indirect economic benefit).
- Modification for production environments.
- Distribution of modified versions without authorization.

For commercial licenses, technical support, enterprise pilots, or inquiries:
Contact: eaguayo@migst.cl

Any use outside the permitted terms requires prior authorization from the author.

Commercial inquiries are welcome and will be answered within a maximum of 7 business days.

## Author

Enrique Aguayo H.
Mackiber Labs
Contact: eaguayo@migst.cl
ORCID: 0009-0004-4615-6825
GitHub: @enriqueherbertag-lgtm

Documentation assisted by Ana (DeepSeek), AI for research and technical optimization.
