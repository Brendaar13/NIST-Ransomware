# 🛡️ Ransomware Response Plan - NIST Framework

Este repositorio contiene un **Plan de Respuesta ante Incidentes** detallado para un escenario de ataque por Ransomware en una infraestructura corporativa, estructurado bajo el marco de trabajo **NIST (National Institute of Standards and Technology)**.

## 📝 Resumen del Caso
El informe analiza un compromiso de seguridad iniciado mediante **phishing**, que resultó en el cifrado de activos críticos (servidores de archivos, bases de datos y backups). Se proponen medidas estratégicas para la identificación, contención, recuperación y mejora continua del sistema.

## 🚀 Fases del Plan (NIST Cybersecurity Framework)

### 1. Identificación
- Mapeo de activos críticos afectados.
- Análisis de la causa raíz: Falta de segmentación de red y ausencia de monitoreo.

### 2. Protección y Detección
- Implementación de controles técnicos: **MFA**, segmentación de redes y políticas de mínimo privilegio.
- Estrategias de monitoreo mediante **SIEM, EDR e IPS** para la detección temprana de anomalías en el sistema de archivos.

### 3. Respuesta y Erradicación
- Protocolo de activación del **Equipo de Respuesta a Incidentes (ERI)**.
- Medidas de contención: Aislamiento lógico de endpoints y bloqueo de IoCs.

### 4. Recuperación y Mejora
- Estrategias de restauración de backups (Regla 3-2-1).
- Análisis de "Lecciones Aprendidas" para el fortalecimiento de la postura de seguridad post-incidente.

## 🛠️ Conceptos y Tecnologías Clave
- **Metodología:** NIST SP 800-61.
- **Seguridad en Red:** Segmentación, Firewalls, Sandboxing.
- **Monitoreo:** Detección de comportamientos maliciosos y anomalías de cifrado.
- **Cumplimiento:** Consideraciones de transparencia y regulaciones (GDPR).

## 📄 Documentación
- [Descargar Reporte Completo (PDF)](./NIST_TechoCo.pdf)
