# ISR401-GA-SUM-01-ANY

PE1 de la Unidad 1 de Ingeniería de Requerimientos (ISR-401), UTEQ.
Sistema del Proyecto Fin de Curso: gimnasio de la UTEQ.

Integrantes: Aldas Zambrano Alan Andrés, Naranjo Flores Anderson Jeampiere y Yépez Guagua Luis Antonio.

## Estructura

| Archivo | Contenido | Responsable |
|---|---|---|
| `main.tex` | Documento principal | Todos |
| `secciones/portada.tex` | Portada | Luis |
| `secciones/s0_pfc.tex` | Sección 0: roles, descripción, stakeholders y tipo de sistema (Paso 1) | Alan |
| `secciones/s2_1.tex`, `s2_2.tex` | Fundamento teórico 2.1 y 2.2 (Paso 3) | Anderson |
| `secciones/s2_3.tex` a `s2_6.tex` | Fundamento teórico 2.3 a 2.6 (Paso 3) | Luis |
| `secciones/s3_requisitos.tex` | Tabla de requisitos (Paso 4) | Alan |
| `secciones/s3_limite_vision.tex` | Límite del sistema y visión (Paso 5) | Anderson |
| `secciones/s3_contexto.tex` | Perspectivas de contexto y mapa conceptual (Paso 5) | Luis |
| `secciones/conclusiones.tex` | Conclusiones (Paso 6) | Todos |
| `secciones/anexos.tex` | Anexos A y B (Paso 2) | Anderson |
| `secciones/declaracion_ia.tex` | Declaración de uso de IA | Todos |
| `referencias.bib` | Referencias exportadas desde Zotero o Mendeley | Anderson |
| `figuras/` | Logo, mapa conceptual y capturas | Todos |

## Cómo generar el PDF

Con una distribución de LaTeX (MiKTeX o TeX Live), desde esta carpeta:

```
pdflatex main
bibtex main
pdflatex main
pdflatex main
```

En Overleaf basta con subir la carpeta y compilar `main.tex`.
