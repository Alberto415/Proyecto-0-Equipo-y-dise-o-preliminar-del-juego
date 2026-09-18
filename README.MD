# Defiende tu Jardin- Prototipo 0

Proyecto trimestral de diseño y desarrollo de videojuegos.

## Integrantes y Roles
* **Alberto Gonzalez Ruiz:** Lógica del tablero, cuadrícula, sistema de recursos (generación y gasto de puntos) y control de versiones (Git Flow).
* **Cintia Fernanda Reyes Hernández:** Lógica de los invasores (estados: avanzar, detectar obstáculo, comer), sistema de oleadas y pruebas de rendimiento/FPS.
* **Alberto Gonzalez Ruiz y Cintia Fernanda Reyes Hernández:** Implementación de las plantas/torretas (disparar, temporizadores de recarga), barra de vida de la base e interfaz de usuario.


## Entorno de Desarrollo
* **Motor:** Godot Engine 4.x (Renderizador Compatibility)
* **Lenguaje:** GDScript
* **Hardware de referencia:** Laptop con CPU multinúcleo básica, GPU integrada y 8 GB+ RAM bajo Windows/Linux.

## Organización del Repositorio y Flujo de Git
* **Estructura de ramas:**
  * `main`: Código estable y versiones entregables.
  * `develop`: Integración de características previas a entrega.
  * `feature/[numero de tarea]`: Ramas individuales para cada función.
* **Reglas de colaboración:**
  * Prohibido hacer push directo a `main`.
  * La incorporación de cambios se realiza mediante **Pull Request (PR)**.
  * Cada PR requiere la revisión y aprobación de al menos un compañero de equipo antes del merge.

## Estructura de Carpetas Prevista
* `/scenes/` - Escenas de Godot (.tscn) para tablero, agentes y UI.
* `/scripts/` - Lógica en GDScript (.gd).
* `/assets/` - Sprites, texturas y recursos de audio.
* `/docs/` - GDD, esquemas y notas técnicas.
