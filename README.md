# Damian Fabricio Macancela

> **Ciberseguridad Técnica · Inteligencia Artificial Defensiva · Derecho Digital & Privacidad**  
> *Ecuador 🇪🇨 · [LinkedIn](https://www.linkedin.com/in/damian-fabricio-macancela-b0a24b3b5) · [damianmacancela@gmail.com](mailto:damianmacancela@gmail.com)*

---

### Enfoque Profesional

Desarrollo e investigación técnica en la intersección entre la **seguridad de sistemas e infraestructura**, la **automatización con IA** y la **legislación moderna de protección de datos**.

Mi trabajo aborda tres frentes complementarios:
1. **Seguridad Técnica & Threat Hunting:** Análisis de bajo nivel en Windows, evaluación de drivers de kernel (*BYOVD*), detección de vectores de persistencia y auditoría de identidades en la nube (*Microsoft Entra ID*).
2. **Inteligencia Artificial Aplicada:** Integración pragmática de modelos (*LLMs* locales y remotos, *NLP*) en flujos de detección y triaje en SOC, aplicando estrictos controles de seudonimización previa para blindar la privacidad.
3. **Derecho Digital & Cumplimiento Técnico:** Evaluación del riesgo y salvaguarda de evidencia conforme a marcos regulatorios modernos (**LOPDP**, **RGPD**, estándares **ISO/IEC 27001** e **ISO/IEC 29134**). Entender la tecnología permite auditarla; entender el derecho permite garantizar su legitimidad y cumplimiento.

---

### Ecosistema de Proyectos

#### 🛡️ Seguridad de Sistemas, Kernel & Threat Hunting

| Proyecto | Enfoque Técnico | Stack / Tecnologías |
| :--- | :--- | :--- |
| **[DriverTriage](https://github.com/DamianMacancela/DriverTriage)** | Triaje estático de drivers de kernel Windows para priorizar candidatos **BYOVD** desconocidos evaluando capacidad peligrosa, exposición y confianza con métricas y parser PE propio en C#. | `PowerShell` `C# (.NET)` `PE Parser` `CI/CD` |
| **[EntraHunt](https://github.com/DamianMacancela/EntraHunt)** | Módulo de threat hunting para Microsoft Entra ID. Detecta rociado de contraseñas (*Password Spray*), fatiga de MFA y reglas de bandeja de entrada sospechosas. | `PowerShell` `Graph API` `MITRE ATT&CK` |
| **[HuntKit](https://github.com/DamianMacancela/HuntKit)** | Toolkit de auditoría y análisis de mecanismos de persistencia en Windows (Tareas Programadas, Run Keys, WMI) evaluando derivas (*drifts*) frente a líneas base. | `PowerShell 7` `WMI / CIM` `Registry` `Pester` |
| **[pentest-lab-writeup](https://github.com/DamianMacancela/pentest-lab-writeup)** | Informe técnico de intrusión ética en entorno controlado bajo metodología **OWASP WSTG v4.2** (enumeración, explotación de SQLi y remediación mediante consultas preparadas). | `OWASP WSTG` `Burp Suite` `SQLi` `Hashcat` |

#### 🤖 Inteligencia Artificial & Seguridad Defensiva

| Proyecto | Enfoque Técnico | Privacidad & Arquitectura |
| :--- | :--- | :--- |
| **[EntraHunt (Triaje IA)](https://github.com/DamianMacancela/EntraHunt)** | Triaje automatizado de alertas de seguridad con Claude y Ollama. Aplica **enmascaramiento estricto por regex (PII)** antes de transmitir cualquier dato al modelo. | `Claude API` `Ollama` `Data Masking (PII)` `Zero-Leak` |
| **[ai-phishing-classifier](https://github.com/DamianMacancela/ai-phishing-classifier)** | Clasificador de correos maliciosos usando Machine Learning clásico (NLP) como capa complementaria a controles SPF/DKIM/DMARC. | `Python` `scikit-learn` `TF-IDF` `Naive Bayes` |

#### ⚖️ Derecho Digital, Privacidad & Criptografía

| Proyecto | Enfoque Técnico | Marco Normativo & Estándares |
| :--- | :--- | :--- |
| **[lopdp-eipd-toolkit](https://github.com/DamianMacancela/lopdp-eipd-toolkit)** | Kit de plantillas estructuradas en Markdown para Evaluaciones de Impacto en Protección de Datos personales (**EIPD/DPIA**), matrices de riesgo y mapeo de flujos de datos. | `LOPDP (Ecuador)` `RGPD / GDPR` `ISO/IEC 29134` `ISO 27001` |
| **[crypto-shield](https://github.com/DamianMacancela/crypto-shield)** | Utilidad CLI para cifrado y autenticación de archivos sensibles con derivación segura de claves, alineada a estándares de cifrado en reposo. | `Python` `AES-256-GCM` `PBKDF2-HMAC-SHA256` |

---

### Principios de Ingeniería

* **Evidencia sobre Suposición:** Código validado con pruebas automatizadas (Pester, CI/CD en GitHub Actions, análisis estático con PSScriptAnalyzer).
* **Privacidad por Diseño (Privacy by Design):** Ningún dato sensible o PII sale a un modelo de IA o servicio externo sin anonimización local previa comprobada.
* **Convergencia Técnica-Jurídica:** La ciberseguridad sin contexto normativo deja vacíos de responsabilidad; el derecho digital sin comprensión técnica profunda se queda en teoría.

---

<p align="center">
  <sub>Damian Fabricio Macancela · <a href="https://github.com/DamianMacancela">github.com/DamianMacancela</a></sub>
</p>
