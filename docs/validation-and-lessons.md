# Validaciones, limitaciones y aprendizajes

## Evidencia de trabajo técnico reportada

En el historial del piloto se reportaron:

- Pruebas de integración de n8n con un servicio local implementado con FastAPI.
- Uso de Python y Pillow en pruebas de generación o procesamiento de imágenes.
- Recuperación y filtrado de contenido de fuentes RSS.
- Uso de herramientas colaborativas para organizar materiales y apoyar la revisión.

**Alcance probatorio:** son actividades documentadas de desarrollo y prueba, no un informe independiente de QA. Aún no se adjuntan registros técnicos, capturas saneadas, benchmarks ni criterios de aceptación firmados.

## Limitaciones que deben comunicarse

| Área | Límite actual de la evidencia |
|---|---|
| Despliegue | No se acredita operación completa y sostenida en producción |
| LLM / RAG / agentes | No se documenta implementación productiva verificable |
| Seguridad | No se publican resultados de auditoría ni pruebas de penetración |
| Rendimiento | Sin métricas verificadas de latencia o volumen |
| Negocio | Sin valores medidos de ahorro de tiempo, costos o retorno |
| Publicación | La aprobación humana sigue siendo una condición explícita |

## Aprendizajes y decisiones de ingeniería

- Definir entradas, salidas y criterios de aceptación antes de ampliar la automatización.
- Separar el procesamiento informático de las decisiones editoriales sobre temas de salud.
- Validar conexiones individualmente antes de asumir que una cadena completa es confiable.
- Documentar procedencia de información y límites de contenido asistido por IA.
- Evitar que una descripción de portafolio confunda pruebas de integración con software productivo.

## Siguientes evidencias deseables

1. Diagrama del flujo **real** revisado frente a la implementación, sin detalles privados.
2. Capturas anonimizadas del entorno de pruebas, si existe autorización para publicarlas.
3. Matriz de pruebas y criterios de aceptación reproducibles usando datos ficticios.
4. Comparativa del tiempo manual frente al asistido, solo después de medirlo.
5. Precisar responsabilidades y alcance personal en el proyecto.

## Confidencialidad

Este caso es anónimo. No citar al cliente o exponer sus materiales, marcas, credenciales, nombres de personal, información sanitaria privada o archivos internos.
