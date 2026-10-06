<p align="center">
  <img src="assets/hero.svg" width="100%" alt="Kevin Chávez — sistemas, automatización y agentes de IA" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=30&duration=3200&pause=1200&color=4FE3C1&center=true&vCenter=true&width=900&height=60&lines=Del+proceso+real+al+sistema+en+producci%C3%B3n;Flujos+en+n8n+%C2%B7+agentes+LLM+%C2%B7+CRM;Si+se+repite%2C+se+automatiza" alt="Del proceso real al sistema en producción" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AUTOMATIZACI%C3%93N-0A0E13?style=for-the-badge&logo=n8n&logoColor=EA4B71" alt="Automatización" />
  <img src="https://img.shields.io/badge/AGENTES_IA-0A0E13?style=for-the-badge&logo=openai&logoColor=4FE3C1" alt="Agentes IA" />
  <img src="https://komarev.com/ghpvc/?username=TU_USUARIO&label=VISITAS&color=4FE3C1&style=for-the-badge" alt="Visitas" />
</p>

<p align="center"><img src="assets/divider.svg" width="100%" alt="" /></p>

<h2><img src="assets/prompt.svg" width="34" align="center" alt="" /> 01 — Quién soy</h2>

Trabajo en **Sistemas y Desarrollo en Avalúos ANEPSA**, donde convierto procesos operativos en sistemas: flujos orquestados, agentes de IA y paneles que la operación usa todos los días. Me encargo de todo el ciclo: entiendo el proceso con quien lo opera, lo diseño, lo construyo, lo audito con datos reales y lo dejo documentado.

```yaml
rol:        Sistemas y Desarrollo @ Avalúos ANEPSA
enfoque:    automatización · agentes de IA · integración de sistemas
formación:  tesina en proceso — agentes de IA y orquestación de procesos
ubicación:  México
```

<p align="center"><img src="assets/divider.svg" width="100%" alt="" /></p>

<h2><img src="assets/prompt.svg" width="34" align="center" alt="" /> 02 — Lo que sé hacer</h2>

| | |
|---|---|
| **⚙️ Orquestación de procesos**<br/>Workflows en n8n self-hosted que conectan WhatsApp, CRM, APIs internas y modelos de IA, con patrones asíncronos, validación y manejo de errores. | **🧠 Agentes de IA y LLMs**<br/>Clasificación de intención, extracción estructurada, RAG con Pinecone y optimización de costo con prompt caching y salidas con esquema. |
| **💬 CRM y mensajería**<br/>HubSpot + WhatsApp Business: búsqueda multicampo de contactos, clasificación por unidad de negocio y ruteo automático al asesor correcto. | **📊 Módulos y dashboards**<br/>Interfaces en React para seguimiento comercial y módulos del sistema interno, del mockup a producción. |
| **📐 Análisis de procesos**<br/>Traduzco reglas de negocio (costeo, viáticos, cotización) en lógica formal, fórmulas auditables y roadmaps de automatización. | **📄 Documentación técnica**<br/>Manuales, guías de migración y documentación de workflows en producción, incluso por ingeniería inversa. |

<p align="center"><img src="assets/divider.svg" width="100%" alt="" /></p>

<h2><img src="assets/prompt.svg" width="34" align="center" alt="" /> 03 — Proyectos</h2>

> 🟢 producción  ·  🟡 en desarrollo  ·  ⚪ análisis / diseño

| | Proyecto | Qué hace | Stack |
|:-:|---|---|---|
| 🟢 | **Asistente de WhatsApp con IA** | Atiende prospectos, responde FAQ con RAG, perfila el servicio y registra y asigna el lead en HubSpot. Fase 2 diseñada: multiagente con expediente persistente. | `n8n` `OpenAI` `Pinecone` `HubSpot` |
| 🟡 | **Cotizador de viáticos** | Itinerarios por tramos con cinco topologías de viaje, búsqueda de hospedaje con filtro geográfico y auditoría determinista que recalcula cada cotización. | `n8n` `Apify` `Distance Matrix` |
| 🟢 | **Módulo de Órdenes de Trabajo** | Del levantamiento de requerimientos y mockup funcional a la integración back/front y producción en el sistema interno. | `Internal Control` `Jira` |
| 🟢 | **Cotizadores Autos y Placas** | Extraen datos con IA, consultan HubSpot, estiman valor de mercado y generan la cotización en PDF vía API interna. | `n8n` `OpenAI` `SerpApi` |
| 🟡 | **Plataforma comercial** | Seguimiento de cotizaciones, Mesa de Control y vista de Dirección con filtros por vendedor e indicadores de cierre. | `React` `JSX` |
| ⚪ | **Motor de costeo industrial** | Análisis funcional de la memoria de cálculo: nueve etapas, tres métodos de costeo y roadmap de automatización. | `Excel` `Modelado` |

<sub>Proyectos internos de la empresa; el código no es público.</sub>

<details>
<summary><b>Ver el flujo del asistente de WhatsApp</b></summary>

```mermaid
flowchart LR
    A[WhatsApp] --> B[n8n]
    B --> C{LLM: intención}
    C -->|FAQ| D[RAG · Pinecone]
    C -->|servicio| E[Catálogo · Sheets]
    E --> F[HubSpot · asignar asesor]
    D --> G[Respuesta]
    F --> G
```
</details>

<p align="center"><img src="assets/divider.svg" width="100%" alt="" /></p>

<h2><img src="assets/prompt.svg" width="34" align="center" alt="" /> 04 — Stack</h2>

<p>
  <img src="https://img.shields.io/badge/n8n-0A0E13?style=for-the-badge&logo=n8n&logoColor=EA4B71" alt="n8n" />
  <img src="https://img.shields.io/badge/OpenAI-0A0E13?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/Pinecone-0A0E13?style=for-the-badge&logoColor=white" alt="Pinecone" />
  <img src="https://img.shields.io/badge/HubSpot-0A0E13?style=for-the-badge&logo=hubspot&logoColor=FF7A59" alt="HubSpot" />
  <img src="https://img.shields.io/badge/WhatsApp_Business-0A0E13?style=for-the-badge&logo=whatsapp&logoColor=25D366" alt="WhatsApp Business" />
  <img src="https://img.shields.io/badge/Google_Sheets-0A0E13?style=for-the-badge&logo=googlesheets&logoColor=34A853" alt="Google Sheets" />
  <img src="https://img.shields.io/badge/Apify-0A0E13?style=for-the-badge&logo=apify&logoColor=97D700" alt="Apify" />
  <img src="https://img.shields.io/badge/React-0A0E13?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Jira-0A0E13?style=for-the-badge&logo=jira&logoColor=2684FF" alt="Jira" />
</p>

<p align="center"><img src="assets/divider.svg" width="100%" alt="" /></p>

<h2><img src="assets/prompt.svg" width="34" align="center" alt="" /> 05 — Contacto</h2>

<p>
  <a href="mailto:TU_CORREO"><img src="https://img.shields.io/badge/Email-0A0E13?style=for-the-badge&logo=gmail&logoColor=4FE3C1" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/TU_PERFIL"><img src="https://img.shields.io/badge/LinkedIn-0A0E13?style=for-the-badge&logo=linkedin&logoColor=0A66C2" alt="LinkedIn" /></a>
</p>

<p align="center"><sub><code>¿Tienes un proceso que debería funcionar solo? Hablemos.</code></sub></p>
