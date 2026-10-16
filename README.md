# Damian Fabricio Macancela

> **Estudiante de Ciberseguridad (ITSA) & Derecho (UTPL) · Cuenca, Ecuador 🇪🇨**

<p align="left">
  <a href="https://www.linkedin.com/in/damian-fabricio-macancela-b0a24b3b5"><img src="https://img.shields.io/badge/LinkedIn-Damian_Fabricio_Macancela-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:damianmacancela@gmail.com"><img src="https://img.shields.io/badge/Email-damianmacancela%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/DamianMacancela"><img src="https://img.shields.io/badge/GitHub-DamianMacancela-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <img src="https://img.shields.io/badge/Ubicación-Ecuador_🇪🇨-00529B?style=for-the-badge" alt="Ecuador" />
</p>

<p align="left">
  <a href="https://github.com/DamianMacancela?tab=followers"><img src="https://img.shields.io/github/followers/DamianMacancela?label=Seguir%20en%20GitHub&style=social" alt="Follow GitHub" /></a>
  <a href="https://github.com/DamianMacancela/DriverTriage"><img src="https://img.shields.io/github/stars/DamianMacancela/DriverTriage?label=Star%20DriverTriage&style=social" alt="Star DriverTriage" /></a>
  <a href="https://github.com/DamianMacancela/ZeroTrust-Scanner-OpenSource"><img src="https://img.shields.io/github/stars/DamianMacancela/ZeroTrust-Scanner-OpenSource?label=Star%20ZeroTrust&style=social" alt="Star ZeroTrust" /></a>
  <a href="https://github.com/DamianMacancela/LOPDP-Compliance-Toolkit-Ecuador"><img src="https://img.shields.io/github/stars/DamianMacancela/LOPDP-Compliance-Toolkit-Ecuador?label=Star%20LOPDP%20Toolkit&style=social" alt="Star Toolkit" /></a>
  <a href="https://github.com/DamianMacancela/FinSecOps-EC"><img src="https://img.shields.io/github/stars/DamianMacancela/FinSecOps-EC?label=Star%20FinSecOps-EC&style=social" alt="Star FinSecOps" /></a>
</p>

> **Ciberseguridad Técnica & Threat Hunting · Arquitectura Zero Trust · Inteligencia Artificial Defensiva · Derecho Digital & Privacidad**  

---

### Enfoque Profesional

Investigación y desarrollo de ingeniería en la convergencia entre la **seguridad ofensiva/defensiva de sistemas**, arquitecturas **Zero Trust**, **automatización con IA** y la **legislación moderna de protección de datos personales**.

Mi práctica técnica se estructura en tres ejes fundamentales:
1. **Seguridad Técnica de Bajo Nivel & Threat Hunting:** Análisis de internals en Windows, evaluación heurística de drivers de kernel (*BYOVD*), detección de vectores de persistencia y auditoría de identidades en la nube (*Microsoft Entra ID*).
2. **Arquitectura Zero Trust & Sanitización de Datos:** Diseño e implementación de motores de desidentificación documental y privacidad por diseño (*Zero-Data*), eliminando el riesgo de fuga de información confidencial hacia terceros o modelos de IA.
3. **Derecho Digital & Cumplimiento Técnico:** Evaluación del riesgo y salvaguarda de evidencia conforme a marcos normativos rigurosos (**LOPDP**, **RGPD**, estándares **ISO/IEC 27001** e **ISO/IEC 29134**). *Entender la tecnología permite auditarla con rigor; entender el derecho permite garantizar su legitimidad y validez probatoria.*

---

### 🌟 Proyectos Principales (Top 3)

Los tres desarrollos nucleares que representan el núcleo de mi trabajo técnico y normativo:

| Proyecto | Ámbito & Problema que Resuelve | Características Técnicas & Cumplimiento | Repositorio |
| :--- | :--- | :--- | :--- |
| **[DriverTriage](https://github.com/DamianMacancela/DriverTriage)** | **Threat Hunting en Kernel & BYOVD**<br/>Triaje estático de drivers de kernel Windows para priorizar candidatos vulnerables desconocidos (**MITRE ATT&CK T1068**) antes de que existan en listas reactivas de bloqueo. | • Parser PE propio en C# compilado en memoria (`Private/PEParser.cs`)<br/>• Detección de secciones RWX (violación W^X), cadenas de memoria física y opcodes MSR<br/>• Mitigación de evasión por resolución dinámica (`MmGetSystemRoutineAddress`, `ZwLoadDriver`)<br/>• Evaluación y validación técnica con métricas formales (Recall@K, ablación por categoría) y generador de políticas WDAC en modo auditoría. | [**Ver DriverTriage →**](https://github.com/DamianMacancela/DriverTriage) |
| **[LOPDP Compliance Toolkit](https://github.com/DamianMacancela/LOPDP-Compliance-Toolkit-Ecuador)** | **Cumplimiento Técnico-Jurídico & Privacidad**<br/>Suite de herramientas y esquemas estandarizados para la gobernanza y aplicación real de la Ley Orgánica de Protección de Datos Personales (Ecuador) y RGPD. | • Esquemas JSON normalizados para recepción automatizada de Derechos ARCO<br/>• Plantillas estructuradas de Evaluaciones de Impacto (**EIPD / DPIA**)<br/>• Matrices de riesgo alineadas a estándares **ISO/IEC 29134** e **ISO/IEC 27001**<br/>• Blindaje legal bajo Código Ingenios (SENADI). | [**Ver Toolkit LOPDP →**](https://github.com/DamianMacancela/LOPDP-Compliance-Toolkit-Ecuador) |
| **[ZeroTrust Redact Engine](https://github.com/DamianMacancela/ZeroTrust-Scanner-OpenSource)** | **Arquitectura Zero Trust & Desidentificación PII**<br/>Motor de sanitización documental y censura criptográfica de PII sensible (cédulas, contratos, historiales clínicos) para banca, cooperativas y firmas jurídicas. | • Procesamiento 100% en cliente (WebAssembly Core) sin fuga de datos a la nube<br/>• Cumplimiento estricto del Art. 56 LOPDP y normativas GDPR de secreto profesional<br/>• Eliminación de vectores de exfiltración documental hacia herramientas web inseguras<br/>• Filosofía Zero-Data para entidades altamente reguladas. | [**Ver Zero Trust Engine →**](https://github.com/DamianMacancela/ZeroTrust-Scanner-OpenSource) |

---

### Ecosistema de Proyectos

#### 🛡️ Seguridad de Sistemas, Endpoint & Threat Hunting

| Proyecto | Enfoque Técnico | Stack / Tecnologías |
| :--- | :--- | :--- |
| **[FinSecOps-EC](https://github.com/DamianMacancela/FinSecOps-EC)** | Suite de SecOps bancario y GRC: Reglas WAF anti-credential stuffing, Hardening y Enmascaramiento Dinámico SQL (Art. 40 LOPDP), Reglas analíticas KQL en Microsoft Sentinel y Motor SOAR en Python con cadena de custodia SHA-256. | `Microsoft Sentinel` `KQL` `Python SOAR` `T-SQL DDM` `ModSecurity` `SEPS / LOPDP` |
| **[EntraHunt](https://github.com/DamianMacancela/EntraHunt)** | Módulo de threat hunting e investigación de incidentes para Microsoft Entra ID. Detecta rociado de contraseñas (*Password Spray*), fatiga de MFA, viajes imposibles y reglas de buzón sospechosas. | `PowerShell` `Microsoft Graph API` `MITRE ATT&CK` `CI/CD` |
| **[HuntKit](https://github.com/DamianMacancela/HuntKit)** | Toolkit de auditoría forense para detección de mecanismos de persistencia en Windows (Tareas Programadas, Run Keys, WMI Event Consumers) evaluando derivas (*drifts*) frente a líneas base. | `PowerShell 7` `WMI / CIM` `Registry` `Pester` |
| **[pentest-lab-writeup](https://github.com/DamianMacancela/pentest-lab-writeup)** | Informe técnico de intrusión ética en entorno controlado bajo metodología **OWASP WSTG v4.2** (fases de reconocimiento, explotación controlada de SQLi y remediación mediante consultas parametrizadas). | `OWASP WSTG` `Burp Suite` `SQLi` `Hashcat` |

#### 🤖 Inteligencia Artificial & Seguridad Defensiva

| Proyecto | Enfoque Técnico | Privacidad & Arquitectura |
| :--- | :--- | :--- |
| **[EntraHunt (Triaje IA)](https://github.com/DamianMacancela/EntraHunt)** | Triaje automatizado de eventos de seguridad con Claude y modelos locales en Ollama. Implementa **enmascaramiento estricto por regex (PII)** antes de transmitir cualquier dato al modelo. | `Claude API` `Ollama` `Data Masking (PII)` `Zero-Leak` |
| **[ai-phishing-classifier](https://github.com/DamianMacancela/ai-phishing-classifier)** | Clasificador de correos maliciosos mediante Machine Learning clásico (NLP) como capa complementaria a controles SPF/DKIM/DMARC. | `Python` `scikit-learn` `TF-IDF` `Naive Bayes` |

#### ⚖️ Plataformas Legal-Tech, Gobernanza & Criptografía

| Proyecto | Enfoque Técnico | Marco Normativo & Estándares |
| :--- | :--- | :--- |
| **[lopdp-compliance-saas](https://github.com/DamianMacancela/lopdp-compliance-saas)** | Plataforma SaaS e infraestructura self-hosted para gestión integral de cumplimiento LOPDP: Discovery Engine de PII, Registro de Actividades de Tratamiento (RAT), cronómetro ARSOP+ (15 días) y triaje de brechas (5 días). | `Next.js 14` `Supabase` `PostgreSQL` `n8n` `Docker` `LOPDP` |
| **[lopdp-eipd-toolkit](https://github.com/DamianMacancela/lopdp-eipd-toolkit)** | Kit de plantillas estructuradas en Markdown para Evaluaciones de Impacto en Protección de Datos personales (**EIPD/DPIA**), matrices de riesgo y mapeo de flujos de datos. | `LOPDP (Ecuador)` `RGPD / GDPR` `ISO/IEC 29134` `ISO 27001` |
| **[crypto-shield](https://github.com/DamianMacancela/crypto-shield)** | Utilidad CLI para cifrado y autenticación de archivos sensibles con derivación segura de claves, alineada a estándares de confidencialidad en reposo. | `Python` `AES-256-GCM` `PBKDF2-HMAC-SHA256` |

---

### 📚 Publicaciones & Divulgación Técnica

* **[Manual de Defensa Digital y Ciber-Soberanía](https://github.com/DamianMacancela/manual-defensa-digital-ecuador)**  
  Guía cívica y práctica orientada a la protección bancaria, privacidad del dato personal y ejercicio efectivo de los derechos ARSOP bajo la LOPDP en el contexto ecuatoriano.
* **[El Código de la Resiliencia](https://github.com/DamianMacancela/El-Codigo-De-La-Resiliencia)**  
  Publicación sobre la convergencia entre meritocracia técnica, derecho digital, ciberdefensa e innovación en la gestión pública.
* **[Derecho Digital en Latinoamérica](https://github.com/DamianMacancela/derecho-digital-latam)**  
  Recursos, análisis comparativo y doctrina sobre privacidad, evidencia digital y marcos normativos de ciberseguridad en la región.

---

### 📊 Métricas de Desarrollo en GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=DamianMacancela&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DamianMacancela&layout=compact&theme=dark&hide_border=true" alt="Top Languages" width="48%" />
</p>

---

### Principios de Ingeniería

* **Evidencia sobre Suposición:** Código validado con pruebas automatizadas (Pester, CI/CD en GitHub Actions, análisis estático con PSScriptAnalyzer).
* **Privacidad por Diseño (Privacy by Design):** Ningún dato sensible o PII sale a un modelo de IA o servicio externo sin anonimización local previa comprobada.
* **Convergencia Técnica-Jurídica:** La ciberseguridad sin contexto normativo deja vacíos de responsabilidad; el derecho digital sin comprensión técnica profunda se queda en teoría.

---

### 📬 Contacto & Conexión Profesional

Para consultas profesionales, colaboraciones en ciberseguridad defensiva, auditorías de cumplimiento LOPDP/RGPD o conferencias:

* ✉️ **Correo Electrónico Personal:** [damianmacancela@gmail.com](mailto:damianmacancela@gmail.com)
* 💼 **LinkedIn:** [linkedin.com/in/damian-fabricio-macancela-b0a24b3b5](https://www.linkedin.com/in/damian-fabricio-macancela-b0a24b3b5)
* 🌐 **GitHub:** [github.com/DamianMacancela](https://github.com/DamianMacancela)

---

<p align="center">
  <sub>Damian Fabricio Macancela · <a href="https://github.com/DamianMacancela">github.com/DamianMacancela</a> · Cuenca, Ecuador 🇪🇨</sub>
</p>
