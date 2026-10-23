# Verificación de entrega

Fecha: 23 de octubre de 2026. Banco 2026.10.23.2.

## Contenido

- 13 fuentes recuperadas: seis PDF de parciales, cuatro PDF de apuntes, dos HTML y «Copia de Resumen IoT».
- 137 apariciones de preguntas originales conciliadas con los seis parciales (10 por archivo) y ambos HTML (45 y 32).
- 47 originales o variantes tras unificar duplicados; 275 preguntas nuevas. Total: 322.
- 318 evaluables y cuatro originales ambiguas consultables sin puntaje.
- Ocho claves originales con corrección técnica y doble referencia visibles.
- Identificadores únicos, índices de respuesta válidos y ausencia de opciones vacías o duplicadas comprobados.

## Pruebas del navegador

Se ejecutaron pruebas con Chromium/Playwright sobre el HTML entregado, tanto mediante servidor local como archivo sin conexión. Los tamaños revisados fueron 320, 390, 768, 1024 y 1440 píxeles de ancho. Las pruebas de subruta simulan el montaje de GitHub Pages; no equivalen a un despliegue público realizado.

- Aprobado: Inicio y trece fuentes disponibles.
- Aprobado: Tanda de diez sin duplicados ni preguntas ambiguas.
- Aprobado: Coincidencia exacta, intento único y recuperación tras recargar.
- Aprobado: Error genera pendiente de refuerzo.
- Aprobado: Refuerzo prioriza errores.
- Aprobado: Dos aciertos en intentos distintos retiran el pendiente.
- Aprobado: Selección múltiple incompleta es incorrecta.
- Aprobado: Búsqueda, fuente, ficha y consulta sin puntaje.
- Aprobado: Estadísticas por los dieciséis temas.
- Aprobado: Tanda completa, resultado y revisión.
- Aprobado: Prioridad de preguntas no vistas.
- Aprobado: Render de todas las preguntas evaluables.
- Aprobado: Sin desborde horizontal en 320, 390, 768, 1024 y 1440 px.
- Aprobado: Prioridad no vistas aun concentradas en pocos temas.
- Aprobado: Tanda con menos de diez preguntas disponibles.
- Aprobado: Navegación por teclado con foco visible.
- Aprobado: Sin errores de JavaScript.
- Aprobado: Sin solicitudes externas de ejecución.
- Aprobado: Recuperación ante almacenamiento corrupto o no disponible.
- Aprobado: Archivo HTML local sin conexión.
- Aprobado: Carga bajo subruta equivalente a GitHub Pages.
- Aprobado: Selección completa de 43 originales evaluables sin duplicados.
- Aprobado: Sesión de 43 recuperada con respuesta confirmada tras recargar.
- Aprobado: Recorrido y resultado completo de las 43 preguntas.
- Aprobado: Selección completa desde filtros y búsqueda del banco.
- Aprobado: Selección completa de las 318 preguntas evaluables.
- Aprobado: Mapa acotado y selección completa sin desbordes en móvil y escritorio.
- Aprobado: Acción completa deshabilitada si no hay preguntas evaluables.

## Diseño

Se aplicó Impeccable 4.7.0. Su detector mecánico se ejecutó una vez y devolvió cero hallazgos. La revisión independiente de las ocho vistas pidió integrar una tipografía humanista para títulos. Se incorporó Source Sans 3, con licencia OFL y archivo de fuente embebido en el propio HTML. Se recapturaron las ocho vistas y las 21 pruebas volvieron a aprobarse. El pase de veredicto independiente cerró el hallazgo como resuelto y emitió disposición «ship».

La revisión visual cubrió inicio y sesión en escritorio y móvil, devolución de respuestas, banco, estadísticas y resultado. No es una certificación WCAG ni una prueba en todos los navegadores o dispositivos físicos. La aplicación usa controles nativos, etiquetas, foco visible y textos de estado que acompañan los colores.

## Dependencias y datos

El HTML incluye banco, estilos, lógica, fuente y figura SVG. Se comprobó que no solicita recursos externos para practicar. Los únicos enlaces externos son referencias que se abren por decisión del usuario. No se incluye ninguna credencial real ni referencia temporal de descarga.

Los intentos se guardan en localStorage. La indisponibilidad o corrupción del almacenamiento muestra un aviso y permite continuar en memoria; no recupera información ya perdida. La prueba de recuperación cubre los casos implementados, no toda posible alteración manual del almacenamiento.

No se creó un repositorio, no se subieron archivos y no se activó GitHub Pages. Las instrucciones de publicación están en README.md.


## Actualización: selección completa

La versión 2026.10.23.2 agrega «Practicá toda tu selección» y «Practicar coincidencias» desde el banco. Respeta filtros y búsqueda, incluye todas las evaluables sin limitar a diez y mantiene la compatibilidad con sesiones previas. Se verificó completar las 43 originales evaluables, recuperar una sesión larga tras recargar, practicar las 318 evaluables juntas y bloquear la acción cuando no hay coincidencias. El mapa largo usa desplazamiento con altura limitada en móvil y escritorio.

Las 21 pruebas originales y siete nuevas aprobaron: 28 comprobaciones en total. Se inspeccionaron capturas de la sección y de tandas largas en móvil y escritorio. El detector de diseño señaló cinco avisos documentales sobre tamaños tipográficos móviles que ya existían antes de este cambio; no se modificó la tipografía ni se reparó esa documentación como efecto de esta tarea. La revisión independiente «ship» citada arriba corresponde al diseño base; esta ampliación tuvo revisión funcional y visual local.
