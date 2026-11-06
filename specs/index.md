# Catálogo de specs

Registrar cada feature nueva como Propuesta (proposed), incluso después del MVP; después hacer discovery, definir resultado/aceptación/tareas y obtener aprobación del contrato concreto antes del código. Usar IDs estables, prioridades y dependencias. Las features lejanas pueden ser entradas sin carpeta o spec detallada; no crear archivos vacíos para completar el catálogo.

| ID | Resultado esperado | Prioridad | Dependencias | Spec | Estado actual |
|---|---|---|---|---|---|

Usar estados legibles y consistentes: Propuesta (proposed), Discovery, Especificada, Aprobada, En implementación, En verificación, Verificada o Bloqueada. Explicar un bloqueo con causa concreta. Verificada exige tareas comprobadas, todos los AC satisfechos con evidencia pertinente, artefactos visuales si aplica y revisión favorable de un agente distinto del implementador sobre el resultado vigente; no significa publicada. Tests/build exitosos no bastan. Una condición sin comprobar o la falta de revisor impiden declarar aceptación completa.

## Trabajo activo y siguiente acción

Producto: MVPIPP. Sin features ni MVP acordados. Trabajo activo: ninguno.

**Siguiente acción:** discovery desde la necesidad o PRD del usuario (guardarlo en `docs/prd.md` o enlazarlo desde `docs/project.md`) para proponer MVP, exclusiones y catálogo inicial.

## Publicación

Sin publicaciones de producto autorizadas.

Este archivo es la única fuente del estado global vigente. El detalle de tareas vive en cada tasks.md; la historia de comprobaciones en evidence.md. Al cambiar el estado, revisar que contexto, contrato y encabezados no repitan un pendiente obsoleto.
