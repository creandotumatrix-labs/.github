<div align="center">

[![CreandoTuMatrix Labs](https://raw.githubusercontent.com/creandotumatrix-labs/.github/main/banner.svg)](https://github.com/creandotumatrix-labs)

</div>

# CreandoTuMatrix Labs

**Soluciones de IA agéntica para América Latina.**  
Agentic AI solutions for Latin America.

---

Construimos sistemas de IA autónomos, infraestructura cloud-native y automatización inteligente para empresas en LATAM.

---

## ¿Qué hacemos? / What We Do

- **Ingeniería agéntica** — Diseño e implementación de sistemas multi-agente con Claude Code y SPARC  
- **Infraestructura cloud** — AWS · GCP · Azure · Kubernetes · Terraform · GitOps, aplicado en despliegues de cliente (la infraestructura vive en proyectos privados, no en los repos públicos de este org)
- **Automatización DevSecOps** — CI/CD, secret scanning, compliance, observabilidad  
- **Coaching técnico** — Equipos de ingeniería que adoptan IA en su flujo de trabajo

---

### El stack Turbo-Flow

| Herramienta | Estrellas | Lenguaje | Propósito |
|---|---|---|---|
| [**turbo-flow**](https://github.com/marcuspat/turbo-flow) | ⭐ 168 | Shell / Python | Entorno agéntico de desarrollo completo — 215+ herramientas MCP, memoria entre sesiones (Beads), grafo de conocimiento del código (GitNexus), aislamiento por agente con git worktrees. Un solo comando lo despliega en DevPod, Codespaces o Rackspace Spot. Proyecto personal de [Marcus Patman](https://github.com/marcuspat), no de este org. |
| [**turbo-flow-wizard**](https://github.com/adventurewave-labs/turbo-flow-wizard) | ⭐ 5 | Shell | Asistente de configuración guiada para turbo-flow — generador interactivo de archivos `CLAUDE.md` específicos por proyecto. 12 tipos de aplicación, 7 metodologías, 19 conjuntos de funcionalidades. |

### En acción / In motion

| [<img src="https://raw.githubusercontent.com/creandotumatrix-labs/.github/main/profile/demos/turbo-flow-demo.gif" width="420" alt="turbo-flow ejecutando la instalación real codespace_setup.sh, luego un recorrido en vivo por tmux y el inicio de claude">](https://github.com/marcuspat/turbo-flow) | [<img src="https://raw.githubusercontent.com/creandotumatrix-labs/.github/main/profile/demos/turbo-flow-wizard-demo.gif" width="420" alt="turbo-flow-wizard generando un CLAUDE.pre en una sesion de preguntas en vivo">](https://github.com/adventurewave-labs/turbo-flow-wizard) |
|:---:|:---:|
| *turbo-flow — instalación real, workspace tmux real, inicio de claude* | *turbo-flow-wizard — generador interactivo de CLAUDE.md* |

## Proyectos / Projects

### Agentes comerciales de WhatsApp / WhatsApp business agents

Productos en despliegue con clientes.
*Commercial products in client deployment.*

| Producto | Propósito | Demo |
|---|---|---|
| [**asistente-pedidos**](https://github.com/creandotumatrix-labs/asistente-pedidos) | Agente de pedidos y reservaciones por WhatsApp, marca blanca (es-MX), sobre un runtime compartido de tool-use con Claude. | [▶ Ver demo](https://asistente-pedidos-production.up.railway.app/kitchen) |
| [**asistente-de-tienda**](https://github.com/creandotumatrix-labs/asistente-de-tienda) | Agente de soporte y ventas para retail y ecommerce por WhatsApp (es-MX), asentado sobre un catálogo real. | [▶ Ver demo](https://asistente-de-tienda-production.up.railway.app/) |
| [**asistente-comercial**](https://github.com/creandotumatrix-labs/asistente-comercial) | Calificador de prospectos por WhatsApp, agnóstico al vertical: califica → puntúa → agenda → enruta. | [▶ Ver demo](https://asistente-comercial-production.up.railway.app/) |
| [**cdmx-agent-demo**](https://github.com/creandotumatrix-labs/cdmx-agent-demo) | MVP de agente marca blanca para PyMEs de CDMX — calificación de prospectos inmobiliarios y pedidos de restaurante sobre un mismo runtime. | [▶ Ver demo](https://cdmx-agent-demo-production.up.railway.app/demo) |
| **loyalty-club-engine** | Club de lealtad multi-comercio por WhatsApp — agente Claude + herramientas determinísticas + Postgres. | *repositorio privado* |

**Acceso al código / Code access** — `asistente-pedidos`, `asistente-de-tienda`, `asistente-comercial` y `cdmx-agent-demo` son públicos; cada README trae su propio GIF de demo. `loyalty-club-engine` sigue privado — escríbenos para solicitar acceso.

*`asistente-pedidos`, `asistente-de-tienda`, `asistente-comercial` and `cdmx-agent-demo` are public — each README has its own demo GIF. `loyalty-club-engine` is still private; contact us for access.*

### En acción / In motion

| [<img src="https://raw.githubusercontent.com/creandotumatrix-labs/asistente-pedidos/main/asistente-pedidos-demo-v2.gif" width="420" alt="asistente-pedidos tomando un pedido de tacos por WhatsApp y actualizando el tablero de cocina en vivo">](https://github.com/creandotumatrix-labs/asistente-pedidos) | [<img src="https://raw.githubusercontent.com/creandotumatrix-labs/asistente-de-tienda/main/asistente-de-tienda-demo.gif" width="420" alt="asistente-de-tienda respondiendo preguntas de catalogo real y generando un link de pago">](https://github.com/creandotumatrix-labs/asistente-de-tienda) |
|:---:|:---:|
| *asistente-pedidos — pedido y reservación por WhatsApp, tablero de cocina en vivo* | *asistente-de-tienda — soporte y ventas grounded en catálogo real* |

| [<img src="https://raw.githubusercontent.com/creandotumatrix-labs/asistente-comercial/main/asistente-comercial-demo.gif" width="420" alt="asistente-comercial calificando un prospecto por WhatsApp y agendando una cita en Google Calendar">](https://github.com/creandotumatrix-labs/asistente-comercial) | [<img src="https://raw.githubusercontent.com/creandotumatrix-labs/cdmx-agent-demo/main/cdmx-agent-demo.gif" width="420" alt="cdmx-agent-demo mostrando el mismo motor cambiando de inmobiliaria a restaurante con un solo archivo de configuracion">](https://github.com/creandotumatrix-labs/cdmx-agent-demo) |
|:---:|:---:|
| *asistente-comercial — calificación, scoring y booking de leads por WhatsApp* | *cdmx-agent-demo — un motor, dos verticales, marca blanca por config* |

---

## Filosofía / Philosophy

> "Un solo ingeniero puede operar como un equipo completo."  
> "One engineer can operate like an entire team."

Nuestra metodología combina arquitectura de sistemas robusta con la velocidad que dan los agentes de IA modernos.

Our methodology combines robust systems architecture with the velocity that modern AI agents enable.

---

## Tecnología / Stack

Claude Code · Rust · Python · Shell

Stack de infraestructura usado en despliegues de cliente (no reflejado en los repos públicos de este org): Kubernetes · Terraform · ArgoCD · AWS · GCP · Azure

---

## Contacto / Contact

🌐 [creandotumatrix.com](https://creandotumatrix.com)  
💼 [LinkedIn](https://linkedin.com/in/marcuspatman) · 📺 [YouTube](https://youtube.com/@marcuspatmanagentics)  
✉️ Ingeniería agéntica para LATAM — contáctanos para proyectos y colaboraciones

---

Built by [Marcus Patman](https://github.com/marcuspat) — Principal Agentic Engineer  
Open-source tooling at [adventurewave-labs](https://github.com/adventurewave-labs) · LATAM AI at [creandotumatrix-labs](https://github.com/creandotumatrix-labs)
