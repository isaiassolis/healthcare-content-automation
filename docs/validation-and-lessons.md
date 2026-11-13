# Operación, aprendizajes y evolución del sistema

## Estado de la solución

El sistema editorial diseñado con **tres flujos n8n** continúa **en funcionamiento**. Está orientado a ampliar su uso hacia **nuevos clientes y otras áreas**.

El proceso mantiene aprobación humana en la selección de temas, la revisión de notas y la validación de conceptos ilustrados; la publicación es manual.

## Los tres flujos

| Flujo | Resultado | Revisión humana |
| --- | --- | --- |
| **1. Investigación RSS** | Temas relevantes clasificados y organizados. | Selección de temas y observaciones. |
| **2. Redacción LLM** | Borradores, hashtags y revisiones iterativas. | Aprobación, rechazo o ajustes del texto. |
| **3. Concepto visual** | Propuesta ilustrada con apoyo de LLM y Pillow. | Aprobación, rechazo o ajustes visuales. |

## Aprendizajes de diseño

### La automatización debe permitir decisiones humanas

Separar el proceso en tres flujos hizo posible que el personal clínico tuviera control antes de que el contenido avanzara a la siguiente etapa.

### Las observaciones deben alimentar la revisión

Cuando el equipo solicita cambios, el sistema vuelve a preparar el material y avisa para su revisión. Esto facilita trabajar por iteraciones en lugar de depender de un único borrador.

### La homogeneidad visual requiere reglas

Usar **Pillow** junto con un concepto propuesto mediante **LLM** ayuda a mantener estructuras visuales constantes. El control programático reduce variaciones de formato, pero no garantiza por sí solo la exactitud factual de una ilustración.

### Publicar manualmente es una decisión de producto

El equipo médico decidió conservar bajo su control la programación y la publicación. Esa elección es parte del diseño actual, no una funcionalidad pendiente.

## Expansión a nuevos clientes y áreas

La evolución del sistema contempla:

- Personalizar fuentes RSS y criterios de relevancia por área.
- Definir responsables de selección y aprobación para cada cliente.
- Ajustar indicaciones editoriales, tono y formatos.
- Mantener plantillas gráficas coherentes con cada identidad.
- Incorporar seguimiento de revisiones y resultados conforme crezca la operación.

El sistema sigue activo; este documento no asigna cifras de rendimiento ni resultados comerciales que no se hayan medido.

## Privacidad

La documentación pública no incluye la identidad del cliente, materiales privados, credenciales ni información clínica personal.

[← Volver al proyecto](../README.md)
