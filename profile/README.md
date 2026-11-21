# wekyt

**Agent teams that build, maintain, and support software. Zero humans in the loop.**

Wekyt is two things in one place.

**1. The hub.** One command installs a small team of specialized agents, orchestrator, architect, dev, QA, security, that plan, build, test, and maintain software together, checking each other's work. No human in the loop. When every layer agrees, the merge happens on its own.

- **Lightweight:** a default team of 5 agents, plain Markdown files, no framework.
- **Zero friction:** one command, zero questions. The standard decides; you edit a file afterwards if you want.
- **Robust, maintainable, scalable, by the agents themselves:** brief, plan, architecture, build, QA, tests as a gate, layers verifying each other, automatic rollback, full audit of every decision.

Tools live in one shared store, apart from the agents. No agent owns a tool. Each agent finds the tool it needs by its description when the task calls for it, and each role has its own permissions. The QA agent, for example, cannot open a pull request even though the tool exists. Least privilege by role, not by trust.

Install it with one command:

```bash
curl -fsSL https://raw.githubusercontent.com/wekyt/hub/main/install.sh | bash
```

It installs the dev team into an `ai/` folder in your current project. No git clone, no npm.

**2. Shared skills and tools.** The same org holds the skills, prompts, and repos shared in the Píldora Tech videos. Those are separate repos you can browse, copy, or clone. They are not part of what the command installs.

## Status

Building now. The first public piece is the hub itself: skills, agent teams, and the one-command installer.

## En español

Wekyt son dos cosas en un solo lugar.

**1. El hub.** Un comando instala un equipo pequeño de agentes especializados, orquestador, arquitecto, dev, QA, seguridad, que planean, construyen, prueban y mantienen software juntos, verificándose entre sí. Ningún humano en el loop. Cuando todas las capas acuerdan, el merge pasa solo.

- **Liviano:** un equipo por defecto de 5 agentes, archivos Markdown, sin framework.
- **Cero fricción:** un comando, cero preguntas.
- **Robusto, mantenible y escalable, por los mismos agentes:** brief, plan, arquitectura, build, QA, tests como puerta, capas verificándose entre sí, rollback automático, auditoría completa.

Las herramientas viven en un almacén compartido, aparte de los agentes. Ningún agente es dueño de una herramienta. Cada agente busca la que necesita por su descripción cuando la tarea lo pide, y cada rol tiene sus propios permisos. El agente de QA, por ejemplo, no puede abrir un pull request aunque la herramienta exista. Mínimo privilegio por rol, no por confianza.

Instalalo con un comando:

```bash
curl -fsSL https://raw.githubusercontent.com/wekyt/hub/main/install.sh | bash
```

Instala el equipo dev en una carpeta `ai/` dentro de tu proyecto. Sin git clone, sin npm.

**2. Skills y herramientas compartidas.** La misma org guarda las skills, los prompts y los repos que se comparten en los videos de Píldora Tech. Son repos aparte que se pueden ver, copiar o clonar. No son parte de lo que instala el comando.

## Support

If wekyt helps you, you can support the project here: https://buymeacoffee.com/supportprojects

Si wekyt te sirve, podés apoyar el proyecto acá: https://buymeacoffee.com/supportprojects

## From

Built by the Píldora Tech crew: https://www.youtube.com/@PildoraTech
