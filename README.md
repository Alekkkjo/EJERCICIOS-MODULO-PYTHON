# Proyecto Módulo 3 - Funciones, Modularización y Manejo de Archivos

Estructura lista para subir a GitHub. Incluye:
- `src/` con los ejercicios (1-15) implementados como módulos.
- `data/` con archivos de ejemplo (.csv, .json, .txt).
- `tests/` con pruebas unitarias usando pytest.
- `pyproject.toml` configurado para usar `rich` y dev deps `pytest`, `ruff`.

Instrucciones:
1. Crear entorno con UV o `python -m venv .venv` y activar.
2. Instalar dependencias: `pip install -e .[dev]` o `pip install rich pytest ruff`.
3. Ejecutar pruebas: `pytest -q`
4. Ejecutar módulos desde `src/proyecto_mod3` o usar el paquete `python -m proyecto_mod3.ejercicio_XX`

Cada módulo contiene docstrings y type hints. ¡Listo para entregar!