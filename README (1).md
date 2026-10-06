<p align="center">
  <img src="neon-hero.svg" width="100%" alt="Kevin Chávez — sistemas, automatización y agentes de IA" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&duration=2600&pause=900&color=FF2BD6&center=true&vCenter=true&multiline=false&width=900&height=56&lines=%3E+Full+stack+developer+%C2%B7+automatizaci%C3%B3n+%C2%B7+IA;%3E+Del+proceso+real+al+sistema+en+producci%C3%B3n;%3E+Flujos+en+n8n+%C2%B7+agentes+LLM+%C2%B7+CRM;%3E+Si+se+repite%2C+se+automatiza_" alt="Del proceso real al sistema en producción" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/FULL_STACK-B6FF3B?style=for-the-badge&logo=stackshare&logoColor=black" alt="Full stack" />
  <img src="https://img.shields.io/badge/AUTOMATIZACI%C3%93N-FF2BD6?style=for-the-badge&logo=n8n&logoColor=white" alt="Automatización" />
  <img src="https://img.shields.io/badge/AGENTES_IA-00F0FF?style=for-the-badge&logo=openai&logoColor=black" alt="Agentes IA" />
  <img src="https://komarev.com/ghpvc/?username=kevinchavez1622-source&label=VISITAS&color=8A5CFF&style=for-the-badge" alt="Visitas" />
</p>

<p align="center"><img src="neon-divider.svg" width="100%" alt="" /></p>

<img src="neon-s01.svg" width="100%" alt="01 — Quién soy" />

<p align="center">
  <img src="neon-terminal.svg" width="88%" alt="whoami: Kevin Uriel Chávez, Sistemas y Desarrollo en Avalúos ANEPSA" />
</p>

Soy **desarrollador full stack** en el área de **Sistemas y Desarrollo de Avalúos ANEPSA**. Construyo desde la interfaz que usa el equipo hasta la lógica de backend, las integraciones y los agentes de IA que trabajan detrás. Convierto procesos operativos en sistemas: flujos orquestados, agentes de IA y paneles que la operación usa todos los días. Me encargo de todo el ciclo: entiendo el proceso con quien lo opera, lo diseño, lo construyo, lo audito con datos reales y lo dejo documentado.

<img src="neon-s02.svg" width="100%" alt="02 — Lo que sé hacer" />

| | |
|---|---|
| **⚡ Orquestación de procesos**<br/>Workflows en n8n self-hosted que conectan WhatsApp, CRM, APIs internas y modelos de IA, con patrones asíncronos, validación y manejo de errores. | **🧠 Agentes de IA y LLMs**<br/>Clasificación de intención, extracción estructurada, RAG con Pinecone y optimización de costo con prompt caching y salidas con esquema. |
| **💬 CRM y mensajería**<br/>HubSpot + WhatsApp Business: búsqueda multicampo de contactos, clasificación por unidad de negocio y ruteo automático al asesor correcto. | **🧩 Desarrollo full stack**<br/>Frontend en React, backend en Node.js con MongoDB, APIs REST y contenedores con Docker: módulos completos del sistema interno, del levantamiento y el mockup a producción. |
| **📊 Dashboards y datos**<br/>Paneles de seguimiento comercial para Mesa de Control y Dirección, con filtros, indicadores de cierre y exportación. | **📐 Análisis de procesos**<br/>Traduzco reglas de negocio (costeo, viáticos, cotización) en lógica formal, fórmulas auditables y roadmaps de automatización. |
| **📄 Documentación técnica**<br/>Manuales, guías de migración y documentación de workflows en producción, incluso por ingeniería inversa. | |

<img src="neon-s03.svg" width="100%" alt="03 — Proyectos" />

> 🟢 producción  ·  🟡 en desarrollo  ·  🟣 análisis / diseño

| | Proyecto | Qué hace | Stack |
|:-:|---|---|---|
| 🟢 | **Asistente de WhatsApp con IA** | Atiende prospectos, responde FAQ con RAG, perfila el servicio y registra y asigna el lead en HubSpot. Fase 2 diseñada: multiagente con expediente persistente. | `n8n` `OpenAI` `Pinecone` `HubSpot` |
| 🟡 | **Cotizador de viáticos** | Itinerarios por tramos con cinco topologías de viaje, búsqueda de hospedaje con filtro geográfico y auditoría determinista que recalcula cada cotización. | `n8n` `Apify` `Distance Matrix` |
| 🟢 | **Módulo de Órdenes de Trabajo** | Del levantamiento de requerimientos y mockup funcional a la integración back/front y producción en el sistema interno. | `Internal Control` `Jira` |
| 🟢 | **Cotizadores Autos y Placas** | Extraen datos con IA, consultan HubSpot, estiman valor de mercado y generan la cotización en PDF vía API interna. | `n8n` `OpenAI` `SerpApi` |
| 🟡 | **Plataforma comercial** | Seguimiento de cotizaciones, Mesa de Control y vista de Dirección con filtros por vendedor e indicadores de cierre. | `React` `JSX` |
| 🟣 | **Motor de costeo industrial** | Análisis funcional de la memoria de cálculo: nueve etapas, tres métodos de costeo y roadmap de automatización. | `Excel` `Modelado` |

<sub>Proyectos internos de la empresa; el código no es público.</sub>

<details>
<summary><b>⚡ Ver el flujo del asistente de WhatsApp</b></summary>

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

<img src="neon-s04.svg" width="100%" alt="04 — Stack" />

<p align="center"><sub><code>frontend</code></sub><br/>
  <img src="https://img.shields.io/badge/React-00F0FF?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/JavaScript-B6FF3B?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/HTML5-FF2BD6?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-8A5CFF?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
</p>

<p align="center"><sub><code>backend, bases de datos y devops</code></sub><br/>
  <img src="https://img.shields.io/badge/REST_APIs-00F0FF?style=for-the-badge&logo=postman&logoColor=black" alt="REST APIs" />
  <img src="https://img.shields.io/badge/Webhooks-FF2BD6?style=for-the-badge&logoColor=white" alt="Webhooks" />
  <img src="https://img.shields.io/badge/Node.js-B6FF3B?style=for-the-badge&logo=nodedotjs&logoColor=black" alt="Node.js" />
  <img src="https://img.shields.io/badge/MongoDB-FF2BD6?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Docker-8A5CFF?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/nvm-B6FF3B?style=for-the-badge&logoColor=black" alt="nvm" />
</p>

<p align="center"><sub><code>automatización e ia</code></sub><br/>
  <img src="https://img.shields.io/badge/n8n-FF2BD6?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
  <img src="https://img.shields.io/badge/OpenAI-00F0FF?style=for-the-badge&logo=openai&logoColor=black" alt="OpenAI" />
  <img src="https://img.shields.io/badge/Pinecone-8A5CFF?style=for-the-badge&logoColor=white" alt="Pinecone" />
  <img src="https://img.shields.io/badge/RAG-B6FF3B?style=for-the-badge&logoColor=black" alt="RAG" />
</p>

<p align="center"><sub><code>crm y mensajería</code></sub><br/>
  <img src="https://img.shields.io/badge/HubSpot-FF2BD6?style=for-the-badge&logo=hubspot&logoColor=white" alt="HubSpot" />
  <img src="https://img.shields.io/badge/WhatsApp_Business-B6FF3B?style=for-the-badge&logo=whatsapp&logoColor=black" alt="WhatsApp Business" />
  <img src="https://img.shields.io/badge/Treble.ai-00F0FF?style=for-the-badge&logoColor=black" alt="Treble.ai" />
  <img src="https://img.shields.io/badge/WATI-8A5CFF?style=for-the-badge&logoColor=white" alt="WATI" />
  <img src="https://img.shields.io/badge/Slack-FF2BD6?style=for-the-badge&logo=slack&logoColor=white" alt="Slack" />
</p>

<p align="center"><sub><code>datos e integraciones</code></sub><br/>
  <img src="https://img.shields.io/badge/Google_Sheets-00F0FF?style=for-the-badge&logo=googlesheets&logoColor=black" alt="Google Sheets" />
  <img src="https://img.shields.io/badge/Excel-B6FF3B?style=for-the-badge&logoColor=black" alt="Excel" />
  <img src="https://img.shields.io/badge/Apify-8A5CFF?style=for-the-badge&logo=apify&logoColor=white" alt="Apify" />
  <img src="https://img.shields.io/badge/Google_Maps_API-FF2BD6?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Google Maps API" />
  <img src="https://img.shields.io/badge/SerpApi-00F0FF?style=for-the-badge&logoColor=black" alt="SerpApi" />
</p>

<p align="center"><sub><code>herramientas</code></sub><br/>
  <img src="https://img.shields.io/badge/Git-FF2BD6?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-8A5CFF?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/Jira-00F0FF?style=for-the-badge&logo=jira&logoColor=black" alt="Jira" />
</p>

<img src="neon-s05.svg" width="100%" alt="05 — Actividad" />

<p align="center">
  <img src="https://raw.githubusercontent.com/kevinchavez1622-source/kevinchavez1622-source/output/github-snake-dark.svg" width="100%" alt="Contribuciones en GitHub animadas" />
</p>

<img src="neon-s06.svg" width="100%" alt="06 — Contacto" />

<p align="center">
  <a href="mailto:TU_CORREO"><img src="https://img.shields.io/badge/EMAIL-FF2BD6?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/TU_PERFIL"><img src="https://img.shields.io/badge/LINKEDIN-00F0FF?style=for-the-badge&logo=linkedin&logoColor=black" alt="LinkedIn" /></a>
</p>

<p align="center"><img src="neon-divider.svg" width="100%" alt="" /></p>

<p align="center"><code>¿Tienes un proceso que debería funcionar solo? Hablemos.</code></p>
