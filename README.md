# Preparación del entorno técnico para soluciones de IA

*Configurar un entorno técnico completo en la nube, integrando herramientas de control de versiones, contenedores, automatización CI/CD y bases de datos tiene como propósito aumentar la funcionalidad del entorno es decir, que este se pueda replicar*

## Stack Tecnológico

- VS Code

- Git

- GitHub

- Docker

- GitHub Actions

- Render

- PostgreSQL

- Python3

## Decisiones Tecnológicas
*Para este entorno de Gestión de Datos IA, se han seleccionado las siguientes herramientas basándose en criterios de eficiencia, trazabilidad y escalabilidad:*

1. **VS Code :** Se eligió como IDE principal debido a, que es un editor de código ligero, gratuito y de alto rendimiento, además de su integración natica con Git.

2. **Git :** Se utiliza Git debido a su sistema de control de versiones lo que permite llevar un control de cambios del proyecto.

3. **GitHub :** Se utiliza Git debido a que es una plataforma que permite alojar repositorios Git permitiendo colaboración en equipo e integrar herramientas CI/CD.

4. **Docker (Contenedorización):** Se eligió la imagen base python:```3.11-slim``` para garantizar un entorno ligero y reproducible. Esto asegura que el modelo de IA o la lógica de datos se ejecute sin conflictos de dependencias, independientemente de la infraestructura subyacente.

5. **GitHub Actions (CI/CD):** Se utiliza para automatizar los flujos de trabajo directamente desde el repositorio de GitHub. Permitiendo crear flujos de trabajo personalizados para compilar, probar y desplegar código automáticamente (CI/CD) cada vez que ocurre un evento, como subir código o crear un pull request.

6. **Render (Despliegue en la Nube):** Se seleccionó como plataforma de despliegue por su integración nativa con Docker y GitHub. Esto permite un flujo de entrega continua (CD) donde cada cambio validado se refleja automáticamente en la URL operativa.

7. **PostgreSQL:** Se utiliza como motor de base de datos relacional por su robustez en el manejo de volúmenes de datos estructurados, esenciales para el entrenamiento y auditoría de modelos de IA.
