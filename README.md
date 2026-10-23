# Preguntero IoT y ESP32

Abrí `index.html` en un navegador moderno para practicar. No necesita instalación, servidor, cuenta ni conexión para resolver preguntas. Los enlaces a Drive sí necesitan acceso a Internet y permiso sobre la fuente.

## Funciones

- Tandas de hasta diez preguntas, por tema/origen/fuente; prioridad a las no vistas.
+- Selección completa: todas las preguntas evaluables de los filtros en una sola tanda; también desde la búsqueda del banco. El origen «Parciales y HTML» permite practicar las 43 evaluables juntas.
- Corrección inmediata al confirmar y coincidencia exacta en selección múltiple.
- Refuerzo global de errores, con dos aciertos consecutivos para retirar un pendiente.
- Banco consultable, búsqueda sin distinguir tildes, explicaciones y referencias.
- Progreso y tanda guardados en el almacenamiento local del navegador.
- Cuatro originales ambiguas disponibles solo para consulta; discrepancias técnicas visibles.

El puntaje usa la solución técnica indicada en cada ficha. No pretende reproducir la escala de notas ni el crédito parcial de Moodle. El avance se guarda por navegador y origen: el archivo descargado y la web publicada tienen historiales separados. Si no se puede guardar, aparece un aviso y se puede continuar en memoria.

## Publicar en GitHub Pages

1. Creá un repositorio en tu cuenta o elegí uno existente.
2. Subí el contenido de esta carpeta a la raíz de la rama que vayas a publicar. No subas la carpeta `work/`, los PDF ni las referencias temporales de descarga.
3. En Settings → Pages, seleccioná Deploy from a branch y elegí la rama y la carpeta `/ (root)`.
4. Guardá y esperá a que termine el despliegue. GitHub mostrará la dirección publicada.

No hay dependencias remotas de ejecución ni rutas absolutas de recursos: el HTML funciona también bajo la subruta del repositorio. Para publicar solo la aplicación alcanza con `index.html`; los informes son documentación opcional. No se creó un repositorio ni se publicó nada desde esta entrega.

## Documentación

- `COBERTURA.md`: fuentes, conciliación, duplicados, discrepancias y límites.
- `cobertura.csv`: matriz de preguntas y conceptos con identificadores.
- `VERIFICACION.md`: pruebas realizadas y resultado.

## Actualizaciones

El banco está integrado como JSON en el elemento `question-data` de `index.html`. Mantener los identificadores de preguntas sin cambios conserva sus estadísticas. La versión del banco se indica en `version`; el formato del progreso usa `schema: 1` y la clave local `iot.preguntero.v1`. No cambiar el esquema sin incorporar una migración.

El material original se usa como referencia de estudio. Este proyecto no asigna una licencia sobre los apuntes o preguntas de sus autores.
