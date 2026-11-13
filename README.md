<p align="center">
  <img src="./assets/banner.svg" alt="Pablo Criollo Escobar · Ingeniero de software × IA" width="100%"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=22D3EE&center=true&vCenter=true&width=760&lines=La+IA+escribe+r%C3%A1pido.+Yo+decido+qu%C3%A9+vale+la+pena+escribir.;Arquitectura+limpia+%2B+agentes+bajo+control.;Seguridad%2C+pruebas+y+vuelta+atr%C3%A1s+antes+de+cada+despliegue.;Sistemas+que+duran." alt="Frases"/></a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/TU-USUARIO"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:TU-CORREO"><img src="https://img.shields.io/badge/Correo-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Ecuador-%F0%9F%87%AA%F0%9F%87%A8-0f172a?style=for-the-badge"/>
  <img src="https://komarev.com/ghpvc/?username=PabloTwoElf&style=for-the-badge&color=7c3aed&label=VISITAS"/>
</p>

---

## 🧭 Cómo trabajo con IA (y dónde NO la dejo decidir)

No uso la IA para "hacer más código". La uso como un equipo rápido que yo dirijo. Cada cambio pasa por el mismo circuito:

```mermaid
flowchart LR
    A([Problema real]) --> B[👤 Yo: arquitectura<br/>y límites]
    B --> C[🤖 IA: propone código,<br/>pruebas y alternativas]
    C --> D{¿Pasa las<br/>compuertas?}
    D -- no --> C
    D -- sí --> E[👤 Yo: reviso<br/>y apruebo]
    E --> F[🚀 Despliegue por Git<br/>con respaldo]
    F --> G[(↩ Vuelta atrás<br/>en un comando)]

    classDef humano fill:#0e7490,stroke:#22d3ee,color:#fff
    classDef ia fill:#5b21b6,stroke:#a78bfa,color:#fff
    class B,E humano
    class C ia
```

| 🤖 Delego a la IA | 👤 Nunca lo delego |
|---|---|
| Borradores de código, pruebas y refactors | La **arquitectura** y las fronteras del dominio |
| Revisión estática (Semgrep) y búsqueda en documentación | **Seguridad**: autenticación, roles, secretos, cifrado |
| Pruebas de interfaz automatizadas con navegador | Qué se despliega y cuándo (**producción la lanzo yo**) |
| Tareas repetitivas con flujos y agentes | Aceptar un resultado sin entenderlo |

> **Regla de oro:** el código que no puedo explicar no entra, lo haya escrito yo o un modelo.

---

## 🛠️ Mi banco de trabajo con agentes

Configuro y estudio herramientas para que la IA trabaje con memoria, control y trazabilidad:

- **Claude Code** con servidores **MCP** (Semgrep, documentación en vivo, Playwright, pruebas automáticas) y atajos de un solo comando para Docker y despliegues.
- Repositorios de agentes y *skills* que estudio y adapto: [`agent-skill-creator`](https://github.com/PabloTwoElf/agent-skill-creatorClaudeSkill) · [`napkin`](https://github.com/PabloTwoElf/napkinClaudeSkill) (memoria de errores por repo) · [`token-optimizer`](https://github.com/PabloTwoElf/token-optimizerClaudeSkill) · [`humanizer`](https://github.com/PabloTwoElf/humanizerClaudeSkill) · [`strix`](https://github.com/PabloTwoElf/strixPablo) (pruebas de penetración con IA) · [`Mokagency-agents`](https://github.com/PabloTwoElf/Mokagency-agents)
- Automatización con **n8n** y voz con **Retell AI**.

---

## 🚀 Proyectos con decisiones que puedes leer

<table>
<tr>
<td width="50%" valign="top">

### 🚌 [CulturalTrip](https://github.com/PabloTwoElf/apiconsumidorac)
Compra de pasajes de bus con selección de asientos y pago.

- Asientos con **bloqueo temporal** que pasa a reserva solo tras cobrar
- Pago con **PayPal Sandbox** orquestado por la API
- **Hexagonal + MVC**, función serverless en Vercel
- Diagnóstico documentado de **6 causas** de un `404` en producción

![React](https://img.shields.io/badge/React-0b1020?logo=react&logoColor=61DAFB) ![Node](https://img.shields.io/badge/Node-0b1020?logo=nodedotjs&logoColor=5FA04E) ![Vercel](https://img.shields.io/badge/Vercel-0b1020?logo=vercel&logoColor=white)

</td>
<td width="50%" valign="top">

### 🔐 [SSO + Keycloak + 2FA](https://github.com/PabloTwoElf/SoftwareSegurokeyCloack)
Dos sistemas independientes con una sola identidad.

- **SSO** y roles centralizados con Keycloak
- Doble factor **TOTP**
- Canal de datos **cifrado entre sistemas**
- APIs en **.NET 8**, frontends React, todo en Docker

![.NET](https://img.shields.io/badge/.NET_8-0b1020?logo=dotnet&logoColor=512BD4) ![Keycloak](https://img.shields.io/badge/Keycloak-0b1020?logo=keycloak&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-0b1020?logo=docker&logoColor=2496ED)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ [ClickLoker + Auth](https://github.com/PabloTwoElf/DesarolloDelSoftwareSeguroAppApuestas)
Autenticación JWT reutilizable y seguimiento de clics.

- Repository Pattern, capa de servicios e inyección de dependencias
- **RLS en Supabase**, Redis, limitación de peticiones
- Levanta con `docker compose up --build`

![Supabase](https://img.shields.io/badge/Supabase-0b1020?logo=supabase&logoColor=3ECF8E) ![Redis](https://img.shields.io/badge/Redis-0b1020?logo=redis&logoColor=DC382D)

</td>
<td width="50%" valign="top">

### 📡 [MirrorView](https://github.com/PabloTwoElf/MirrorView)
Reflejo de pantallas entre dispositivos.

- **WebRTC** con servidor de señalización propio
- Frontend en GitHub Pages, señalización en Render

![WebRTC](https://img.shields.io/badge/WebRTC-0b1020?logo=webrtc&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-0b1020?logo=typescript&logoColor=3178C6)

</td>
</tr>
</table>

---

## 🧰 Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,cs,dotnet,python,java,react,ts,vite,postgres,supabase,mysql,mongodb,redis,docker,linux,git,github,githubactions,vercel&theme=dark" alt="Stack"/>
</p>

<p align="center"><sub>Arquitectura hexagonal · SOLID · Microservicios · Keycloak · JWT · n8n · Retell AI · LLMs y agentes</sub></p>

---

## 📊 En números

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=PabloTwoElf&show_icons=true&theme=tokyonight&hide_border=true&locale=es"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=PabloTwoElf&layout=compact&theme=tokyonight&hide_border=true&locale=es"/>
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=PabloTwoElf&theme=tokyonight&hide_border=true&locale=es"/>
</p>
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=PabloTwoElf&theme=tokyo-night&hide_border=true&area=true&custom_title=Actividad%20de%20contribuciones"/>
</p>

<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,24&height=110&section=footer"/></p>
