# Instrumentation Amplifier Simulation

Proyecto de simulación de amplificador de instrumentación usando Proteus con regulador de voltaje LM340.

## Estructura del Proyecto

- `docs/` - Documentación y datasheets
  - `datasheets/` - Hojas de datos de componentes
    - `ad620.pdf` - Amplificador de instrumentación AD620
    - `lm340.pdf` - Regulador de voltaje LM340
    - `m95512-w.pdf` - EEPROM M95512-W
  - `osc_screenshot.pdf` - Captura de pantalla del osciloscopio
- `Proteus_files/` - Archivos de simulación de Proteus
  - `instrumentation_amplifier_sim.pdsprj` - Proyecto principal actual
  - `Project Backups/` - Respaldo del proyecto original
    - `instrumentation_amplifier_sim [20251027, 23-53-54].pdsprj` - Versión inicial

## Componentes

- **AD620**: Amplificador de instrumentación de precisión
- **LM340**: Regulador de voltaje fijo
- **M95512-W**: EEPROM de 512Kbit

## Uso

1. Abrir el archivo `instrumentation_amplifier_sim.pdsprj` en Proteus
2. Ejecutar la simulación
3. Revisar las mediciones en el osciloscopio

## Historial de Cambios

- **Último commit**: Agregado datasheet LM340 y nuevo archivo de proyecto de simulación
- **Proyecto inicial**: Creado el 27/10/2025
- **Versión actual**: Incluye regulador de voltaje para alimentación estable

## Notas

- Simulación de amplificador de instrumentación para aplicaciones de medición de precisión
- Incluye regulador de voltaje para mejorar la estabilidad de la alimentación
- Proyecto respaldado en carpeta `Project Backups/`
