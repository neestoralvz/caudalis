# Caudalis

Este repositorio alberga la documentación de **Caudalis**, empresa enfocada en soluciones integrales para agua potable, tratamiento hídrico y consultoría en el sector. El objetivo principal de esta documentación es facilitar la **comunicación interna**, la **planeación de proyectos** y la **presentación** de la marca, incluyendo lineamientos de estilo y guías de implementación.

## Estructura del Repositorio

```bash
caudalis/
├── docs/
│   ├── index.md            # Página principal de la documentación
│   ├── eleccion_nombre.md  # Histórico del proceso de naming
│   ├── estilo.md           # Guía de estilo (colores, tipografía, recomendaciones de marca)
│   ├── mision_vision.md    # Fundamentos e ideales de la empresa
│   └── plan/
│       ├── plan_inicial.md
│       ├── iteracion_1.md
│       ├── iteracion_2.md
│       ├── iteracion_3.md
│       └── iteracion_4.md
├── mkdocs.yml              # Configuración de MkDocs (navegación, tema, plugins, etc.)
└── venv/                   # Entorno virtual (opcional, para dependencias Python)
```

1. **`docs/`**: Contiene los archivos fuente en Markdown (`.md`), organizados por secciones:
   - **index.md**: Página de inicio o presentación general.  
   - **eleccion_nombre.md**: Explica el proceso de naming.  
   - **estilo.md**: Recopila la paleta de colores y tipografías oficiales de Caudalis.  
   - **mision_vision.md**: Describe la filosofía y objetivos de la empresa.  
   - **plan/**: Subcarpeta para documentos sobre iteraciones y planes específicos.

2. **`mkdocs.yml`**: Archivo donde se define la estructura del sitio, los temas y las extensiones utilizadas por MkDocs.

3. **`venv/`** (opcional): Carpeta del entorno virtual de Python, donde se instalan localmente MkDocs y demás dependencias, sin afectar tu sistema global.

---

## Cómo ver la Documentación

1. **Instala** las dependencias necesarias:

   ```bash
   pip install mkdocs mkdocs-material
   ```

   > *Asegúrate de tener tu entorno virtual activado (`source venv/bin/activate` si usas venv) antes de instalar.*

2. **Levanta** el servidor local para vista previa:

   ```bash
   mkdocs serve
   ```
   Luego, abre [http://127.0.0.1:8000](http://127.0.0.1:8000) para revisar la documentación en tu navegador.

3. **Despliega** en GitHub Pages (opcional):

   ```bash
   mkdocs gh-deploy
   ```
   Esto construirá el sitio estático en la rama `gh-pages` y te permitirá acceder a tu documentación en la URL:
   ```
   https://<TU_USUARIO>.github.io/caudalis/
   ```
   *(Cambia `<TU_USUARIO>` por tu nombre de usuario en GitHub.)*

---

## Notas Finales

- La carpeta `site/` se genera automáticamente al compilar (`mkdocs build`) o desplegar (`mkdocs gh-deploy`), por lo que se recomienda **no versionarla** en Git (añádela a `.gitignore`).
- Consulta `estilo.md` para mantener la coherencia de marca en cuanto a colores, tipografías y lineamientos de diseño.  
- Cualquier modificación al contenido de `docs/` se reflejará automáticamente en la documentación al recargar el servidor local de MkDocs.

¡Gracias por tu interés en **Caudalis**! Para más información, revisa los archivos Markdown dentro de la carpeta `docs/` o contacta al equipo a través de este repositorio.  
