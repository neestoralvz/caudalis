# Caudalis

Este repositorio alberga la documentación de **Caudalis**, empresa enfocada en soluciones integrales para agua potable, tratamiento hídrico y consultoría en el sector.

## Estructura del Repositorio

```bash
empresa_nueva/
├── docs/
│   ├── index.md            # Página principal de la documentación
│   ├── eleccion_nombre.md  # Histórico del proceso de naming
│   ├── mision_vision.md    # Fundamentos e ideales
│   └── plan/               # Planes, iteraciones y fases
├── mkdocs.yml              # Configuración de MkDocs
└── venv/                   # Entorno virtual (opcional)
```

## Cómo ver la Documentación

1. **Instala** las dependencias necesarias (MkDocs y Material):
   ```bash
   pip install mkdocs mkdocs-material
   ```
2. **Levanta** el servidor local:
   ```bash
   mkdocs serve
   ```
   Luego, abre [http://127.0.0.1:8000](http://127.0.0.1:8000).

3. **Despliega** en GitHub Pages (opcional):
   ```bash
   mkdocs gh-deploy
   ```
   Así obtendrás un sitio web estático en `https://<TU_USUARIO>.github.io/empresa_nueva/` (o la URL que corresponda).

¡Gracias por tu interés en **Caudalis**! Para más información, revisa los archivos Markdown dentro de la carpeta `docs/`.
