# Prompt Base: Análisis y Replicación de Proyecto

**Objetivo:** Analizar el repositorio proporcionado y generar informes detallados para poder replicar el proyecto con éxito, considerando que se tienen los permisos del autor.

**Repositorio Objetivo:**
[https://github.com/CodeIA-Academy/founders25-scraper](https://github.com/CodeIA-Academy/founders25-scraper)

**Contexto del Sistema de Agentes:**
Para llevar a cabo este análisis, se utilizará un equipo de agentes especializados coordinados por un Meta agente, siguiendo la estructura definida:
1.  **Meta agente**: Coordina el flujo, priorizando calidad y profesionalidad. Documenta decisiones clave.
2.  **Arquitecto**: Analiza la infraestructura actual del repositorio y define las tecnologías necesarias para la replicación.
3.  **Analista/Auditor**: Realiza un análisis profundo del código, documentación y dependencias. Emite informes en Markdown con tablas, gráficas, y genera imágenes mediante nanobanana 2.
4.  **Monitor de progreso**: Rastrea los avances del análisis e informa sobre los logros de cada agente.
5.  **Developer**: Evalúa la viabilidad técnica, entiende los patrones del código existente (DRY) y planifica la implementación limitando la creación de archivos a 1000 líneas.

**Instrucciones para la Ejecución:**

1.  **Fase 1: Reconocimiento (Analista/Auditor & Arquitecto)**
    *   Extraer la estructura completa del proyecto desde el repositorio.
    *   Identificar el stack tecnológico, dependencias clave y arquitectura general.
    *   *Entregable*: Informe inicial de arquitectura y dependencias (Markdown con tablas de tecnologías).

2.  **Fase 2: Análisis Profundo (Analista/Auditor)**
    *   Auditar el código fuente para comprender la lógica de negocio del scraper.
    *   Generar gráficas de flujo de datos arquitectónicos o dependencias, y usar nanobanana 2 para visualizarlas en el informe.
    *   *Entregable*: Informe de auditoría detallado con gráficas.

3.  **Fase 3: Plan de Replicación (Developer & Arquitecto)**
    *   Diseñar una hoja de ruta para reconstruir el proyecto paso a paso, asegurando la reutilización de componentes (DRY).
    *   Estructurar los futuros módulos para no exceder las 1000 líneas por archivo.
    *   *Entregable*: Plan de acción estructurado y diseño modular.

4.  **Fase 4: Consolidación y Cierre (Meta agente & Monitor de progreso)**
    *   Recopilar todos los informes y planes.
    *   Validar que se cumplen los requisitos de calidad.
    *   *Entregable*: Informe ejecutivo final con el plan maestro de replicación y el estado general del análisis.
