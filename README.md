#Digital-Forensics-Reports (Investigación y Análisis de Incidentes)

## Descripción General

Repositorio dedicado a la documentación de proyectos de análisis forense digital y respuesta a incidentes. El objetivo es demostrar la aplicación de herramientas forenses estándar de la industria (Magnet Axiom) bajo un estricto cumplimiento de la metodología, desde la adquisición hasta la elaboración del informe pericial.

## Proyecto Destacado: Análisis de Infección por Malware (Caso de Estudio)

- **Escenario de Estudio:** Simulación de intrusión en un entorno Windows 7 (2011) a través de un archivo PDF malicioso.
- **Herramientas Clave:** Magnet Axiom Process/Examine, VirtualBox.
- **Metodología Aplicada:** Análisis de artefactos (Registro, Archivos de Programa, Eventos), Línea de Tiempo MFT, y trazado de conexiones de red.
- **IoCs Identificados (Indicadores de Compromiso):**
    - Archivo binario sospechoso: `winlogon.exe` (externo, modificado)
    - IP del servidor atacante: `186.73.132.237`
    - Archivo malicioso: `cv[1].pdf`

## Nota sobre la Confidencialidad y Evidencia
## Este informe es un Ejercicio Académico de Peritaje Cibernético, realizado exclusivamente con fines educativos y utilizando imágenes forenses simuladas. La información y las direcciones IP son indicadores de compromiso (IoCs) analizados en un entorno controlado.
