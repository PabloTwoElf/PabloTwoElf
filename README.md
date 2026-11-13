<h1 align="center">Pablo Criollo</h1>
<p align="center"><b>Ingeniero de software · Backend y arquitectura de sistemas · Integraciones con IA</b><br/>
Ecuador 🇪🇨 · Construyo sistemas que siguen funcionando cuando la red, el presupuesto o el plan fallan.</p>

<p align="center">
  <a href="https://www.linkedin.com/in/TU-USUARIO"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:TU-CORREO"><img src="https://img.shields.io/badge/Correo-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Correo"/></a>
  <img src="https://komarev.com/ghpvc/?username=PabloTwoElf&style=flat-square&color=blue" alt="Visitas"/>
</p>

---

## Problemas que me gusta resolver

La mayoría de perfiles listan tecnologías. Prefiero contarte qué pasa cuando las cosas se rompen y cómo diseño para eso.

| Situación real | Lo que construí | Decisión de diseño clave |
|---|---|---|
| Un evento masivo en un lugar sin cobertura: la validación de entradas no puede depender de internet.
| Compradores eligiendo el mismo asiento al mismo tiempo en una venta de pasajes. | **CulturalTrip**, reservas de bus con selección de asientos y QR dinámicos. | Reservas con expiración y bloqueo pesimista en base de datos; el QR cambia para que una captura de pantalla no sirva dos veces. |
| Creadores, suscriptores y administradores con permisos que se cruzan. | **FinderAllFans**, plataforma de suscripciones con recomendaciones y autorización multi-rol. | Reglas de autorización centralizadas en el dominio, no repartidas por los controladores. |
| Una institución que necesita atender llamadas y mensajes sin un equipo 24/7. | Agentes de voz y flujos con **Retell AI** y **n8n** integrados con LLMs. | El agente nunca decide solo: cada acción pasa por un flujo auditable con reglas explícitas. |

> Los tres primeros repositorios están en desarrollo privado. Si te interesa ver el código o la arquitectura, escríbeme.

---

## Cómo trabajo

- **Arquitectura hexagonal y SOLID** no como dogma, sino para que el dominio no dependa del framework de turno.
- **Todo en Docker desde el primer día.** Si no levanta con un comando, no está listo.
- **Despliegues reproducibles:** el servidor solo recibe código desde Git, con respaldo de base de datos antes y una forma de volver atrás después.
- **IA con límites claros.** Integro LLMs y agentes donde aportan, con validación, trazabilidad y un humano que puede intervenir.
- **Documento las decisiones**, no solo el código. El próximo que lea el repo merece saber el porqué.

---

## Herramientas

**Backend:** Node.js · .NET / C# · Python
**Datos:** PostgreSQL · Supabase · MySQL
**Infraestructura:** Docker y Docker Compose · Linux · Git/GitHub · CI/CD
**Automatización e IA:** n8n · Retell AI · integración de LLMs y agentes
**Arquitectura:** Hexagonal · SOLID · Microservicios · Diseño orientado al dominio

---

## Ahora mismo

- 🔭 Llevando GetOut a producción en eventos reales.
- 🧠 Profundizando en agentes de IA con control de herramientas y memoria persistente.
- 🤝 Abierto a colaborar en proyectos de backend, infraestructura o IA aplicada en Latinoamérica.

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=PabloTwoElf&show_icons=true&theme=tokyonight&hide_border=true&locale=es" alt="Estadísticas de GitHub" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=PabloTwoElf&layout=compact&theme=tokyonight&hide_border=true&locale=es" alt="Lenguajes más usados" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=PabloTwoElf&theme=tokyonight&hide_border=true&locale=es" alt="Racha de contribuciones" height="165"/>
</p>

<p align="center"><i>"Un sistema robusto no es el que nunca falla, sino el que falla de forma predecible y se recupera solo."</i></p>
