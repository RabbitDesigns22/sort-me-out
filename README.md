# sort-me-out

**Your memory when you juggle too much.**

`sort-me-out` is an agent skill for Claude Code (and any agent that reads `SKILL.md` skills). Say "sort me out" or "what am I missing?" and the agent studies every source it can reach (notes, logs, memory, recent conversations, project files, live systems), checks what is really still open, hunts for what slipped through the cracks, and hands back one ordered list: urgent today, this week, waiting on someone, forgotten, and done since last time.

Say "sort me out" or "what did I forget?", and get one ordered list of everything pending.

## Install

With the [skills CLI](https://skills.sh):

```bash
npx skills add RabbitDesigns22/sort-me-out
```

Or manually: copy `skills/sort-me-out/` into `~/.claude/skills/` for all your projects, or into `.claude/skills/` for one project.

To make every session use it, add this line to your `CLAUDE.md`:

```
Before telling the user what is pending or what they forgot, load the sort-me-out skill.
```

## Works well with

- [`hands-on`](https://github.com/RabbitDesigns22/hands-on): the agent does every step it can and asks you only for what it cannot do.
- [`one-answer`](https://github.com/RabbitDesigns22/one-answer): one checked, final answer instead of plan, correction, plan.
- [`never-twice`](https://github.com/RabbitDesigns22/never-twice): a shared error log so the same mistake never happens twice.

## Español

**Ordéname.** Para los que tienen mil cosas y se les olvidan. Le dices "ordéname" o "¿qué me falta?" y el agente revisa todo lo que puede (notas, registros, memoria, chats recientes, archivos y sistemas en vivo), comprueba qué sigue pendiente de verdad, busca lo que se te pasó por alto y te da una sola lista ordenada: lo urgente de hoy, lo de la semana, lo que espera a otra persona, lo olvidado y lo que ya quedó hecho.

Instalar: `npx skills add RabbitDesigns22/sort-me-out`

## License

MIT. Made by [Rabbit Designs](https://github.com/RabbitDesigns22).
