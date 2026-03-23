# LLMOps Project

## Comandos básicos de UV

`uv` es un gestor de paquetes y proyectos Python extremadamente rápido.

### 1. **uv sync**
Sincroniza las dependencias del proyecto basándose en el archivo `pyproject.toml` o `requirements.txt`.
```bash
uv sync
```

### 2. **uv add**
Agrega una nueva dependencia al proyecto.
```bash
uv add <nombre-paquete>
uv add requests  # Ejemplo
```

### 3. **uv remove**
Elimina una dependencia del proyecto.
```bash
uv remove <nombre-paquete>
uv remove requests  # Ejemplo
```

### 4. **uv lock**
Genera o actualiza el archivo de bloqueo (`uv.lock`) con las versiones exactas de las dependencias.
```bash
uv lock
```

### 5. **uv pip install**
Instala paquetes de forma similar a `pip`.
```bash
uv pip install <nombre-paquete>
```

### 6. **uv run**
Ejecuta un script o comando dentro del ambiente del proyecto.
```bash
uv run python script.py
uv run pytest
```
