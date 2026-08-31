<div align="center">

[![CreandoTuMatrix Labs](https://raw.githubusercontent.com/creandotumatrix-labs/.github/main/banner.svg)](https://github.com/creandotumatrix-labs)

</div>

# CreandoTuMatrix Labs

**Soluciones de IA agéntica para América Latina.**  
Agentic AI solutions for Latin America.

🌐 **Sitio completo (ES/EN): [creandotumatrix.com](https://creandotumatrix.com)**

---

Ingeniería agéntica, infraestructura cloud-native y automatización inteligente para empresas en LATAM. Este repo reúne nuestras herramientas open-source y demos técnicos — para servicios, casos de uso y contacto, visita el sitio.

*Agentic engineering, cloud-native infrastructure, and intelligent automation for LATAM enterprises. This repo hosts our open-source tooling and technical demos — for services, use cases, and contact, visit the site.*

**No solo Día 1.** Construimos para Día 2: confiabilidad en producción, observabilidad y ROI medible — no solo levantar un agente y dejarlo ahí.

*Not just Day 1. We build for Day 2: production reliability, observability, and measurable ROI — not just standing up an agent and walking away.*

---

## Asistentes CTM

Suite de agentes por WhatsApp para LATAM, en desarrollo activo.
*WhatsApp agent suite for LATAM, in active development.*

| Producto | Propósito | Demo |
|---|---|---|
| [**asistente-pedidos**](https://github.com/creandotumatrix-labs/asistente-pedidos) | Agente de pedidos y reservaciones por WhatsApp, marca blanca (es-MX), sobre una arquitectura compartida de tool-use con Claude. | [▶ Ver demo](https://asistente-pedidos-production.up.railway.app/kitchen) |
| [**asistente-de-tienda**](https://github.com/creandotumatrix-labs/asistente-de-tienda) | Simulador CLI de soporte y ventas para retail y ecommerce (es-MX), asentado sobre un catálogo real — WhatsApp en fase 2. | [▶ Ver demo](https://asistente-de-tienda-production.up.railway.app/) |
| [**asistente-comercial**](https://github.com/creandotumatrix-labs/asistente-comercial) | Calificador de prospectos por WhatsApp, agnóstico al vertical: califica → puntúa → agenda → enruta. | [▶ Ver demo](https://asistente-comercial-production.up.railway.app/) |
| **loyalty-club-engine** | Club de lealtad multi-comercio por WhatsApp — agente Claude + herramientas determinísticas + Postgres. | *repositorio privado* |

**Acceso al código / Code access** — `asistente-pedidos`, `asistente-de-tienda` y `asistente-comercial` son públicos, forman la familia **Asistentes CTM**, y cada uno trae su propio LICENSE, README bilingüe y GIF de demo. `loyalty-club-engine` sigue privado — escríbenos para solicitar acceso.

*`asistente-pedidos`, `asistente-de-tienda` and `asistente-comercial` are public — together they're the **Asistentes CTM** family, each with its own LICENSE, bilingual README, and demo GIF. `loyalty-club-engine` is still private; contact us for access.*

### En acción / In motion

| [<img src="https://raw.githubusercontent.com/creandotumatrix-labs/asistente-pedidos/main/asistente-pedidos-demo-v2.gif" width="420" alt="asistente-pedidos tomando un pedido de tacos por WhatsApp y actualizando el tablero de cocina en vivo">](https://github.com/creandotumatrix-labs/asistente-pedidos) | [<img src="https://raw.githubusercontent.com/creandotumatrix-labs/asistente-de-tienda/main/asistente-de-tienda-demo.gif" width="420" alt="asistente-de-tienda respondiendo preguntas de catalogo real y generando un link de pago">](https://github.com/creandotumatrix-labs/asistente-de-tienda) |
|:---:|:---:|
| *asistente-pedidos — pedido y reservación por WhatsApp, tablero de cocina en vivo* | *asistente-de-tienda — soporte y ventas grounded en catálogo real* |

---

## El stack Turbo-Flow

| Herramienta | Estrellas | Lenguaje | Propósito |
|---|---|---|---|
| [**turbo-flow**](https://github.com/marcuspat/turbo-flow) | [![stars](https://img.shields.io/github/stars/marcuspat/turbo-flow?style=flat-square&label=%E2%AD%90)](https://github.com/marcuspat/turbo-flow/stargazers) | Shell / Python | Entorno agéntico de desarrollo completo — 215+ herramientas MCP, memoria entre sesiones (Beads), grafo de conocimiento del código (GitNexus), aislamiento por agente con git worktrees. Un solo comando lo despliega en DevPod, Codespaces o Rackspace Spot. Proyecto personal de [Marcus Patman](https://github.com/marcuspat), no de este org. |
| [**turbo-flow-wizard**](https://github.com/adventurewave-labs/turbo-flow-wizard) | [![stars](https://img.shields.io/github/stars/adventurewave-labs/turbo-flow-wizard?style=flat-square&label=%E2%AD%90)](https://github.com/adventurewave-labs/turbo-flow-wizard/stargazers) | Shell | Asistente de configuración guiada para turbo-flow — generador interactivo de archivos `CLAUDE.md` específicos por proyecto. 12 tipos de aplicación, 7 metodologías, 19 conjuntos de funcionalidades. |
| [**loopgen**](https://github.com/adventurewave-labs/loopgen-rs) | — | Rust | Bucles agénticos para Claude Code — wizard interactivo, configs TOML, exportación bash, protocolo LOOP_STATUS. Publicado en [crates.io/crates/loopgen](https://crates.io/crates/loopgen). |
| [**tf-verify.sh**](https://github.com/marcuspat/turbo-flow/blob/main/devpods/tf-verify.sh) | — | Shell | Framework de verificación y quality gates para turbo-flow — 50+ gates de verificación en 12 fases: dependencias, despliegue, artefactos, integridad de estado. Desarrollado y probado en combate durante compromisos reales con clientes. Incluido en turbo-flow `devpods/`. |

### En acción / In motion

| [<img src="https://raw.githubusercontent.com/creandotumatrix-labs/.github/main/profile/demos/turbo-flow-demo.gif" width="420" alt="turbo-flow ejecutando la instalación real codespace_setup.sh, luego un recorrido en vivo por tmux y el inicio de claude">](https://github.com/marcuspat/turbo-flow) | [<img src="https://raw.githubusercontent.com/creandotumatrix-labs/.github/main/profile/demos/turbo-flow-wizard-demo.gif" width="420" alt="turbo-flow-wizard generando un CLAUDE.pre en una sesion de preguntas en vivo">](https://github.com/adventurewave-labs/turbo-flow-wizard) |
|:---:|:---:|
| *turbo-flow — instalación real, workspace tmux real, inicio de claude* | *turbo-flow-wizard — generador interactivo de CLAUDE.md* |

---

> "Un solo ingeniero puede operar como un equipo completo." / "One engineer can operate like an entire team." — más sobre nuestra metodología en [creandotumatrix.com](https://creandotumatrix.com).

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