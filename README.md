# Empresa Nueva

Bienvenido al repositorio de **Empresa Nueva**, donde se gestiona toda la documentación y planes de desarrollo de nuestros proyectos relacionados con la mejora y optimización de sistemas de agua potable.

## Estructura del Repositorio

```bash
empresa_nueva/
├─ docs/
│  ├─ index.md
│  ├─ eleccion_nombre.md
│  ├─ mision_vision.md
│  └─ plan/
├─ mkdocs.yml
└─ venv/
```

- **docs/**: Contiene todos los archivos de documentación en formato Markdown (`.md`), incluyendo el `index.md` (página principal).  
- **mkdocs.yml**: Archivo de configuración para MkDocs con tema Material.  
- **venv/**: Entorno virtual de Python para manejar dependencias.

## Cómo usar esta documentación

1. **Instala las dependencias** (MkDocs y MkDocs Material):
   ```bash
   pip install mkdocs mkdocs-material
   ```

2. **Inicia el servidor local** de MkDocs:
   ```bash
   mkdocs serve
   ```
   Luego, abre el navegador en [http://127.0.0.1:8000](http://127.0.0.1:8000) para explorar la documentación.

3. **Despliega la documentación** (opcional):
   ```bash
   mkdocs build
   ```
   Esto generará una carpeta `site/` con los archivos HTML listos para ser publicados en el servidor de tu preferencia.

## Contacto

Si deseas aportar sugerencias, mejoras o cualquier duda, puedes [crear un *issue*](#) en este repositorio.  
¡Gracias por visitar nuestro proyecto y contribuir a su crecimiento!