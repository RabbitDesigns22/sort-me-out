# sort-me-out

**Your memory when you juggle too much.**

`sort-me-out` is an agent skill for Claude Code (and any agent that reads `SKILL.md` skills). Say "sort me out" or "what am I missing?" and the agent studies every source it can reach (notes, logs, memory, recent conversations, project files, live systems), checks what is really still open, hunts for what slipped through the cracks, and hands back one ordered list: urgent today, this week, waiting on someone, forgotten, and done since last time.

Say "sort me out" or "what did I forget?", and get one ordered list of everything pending.

## See the difference

> **You:** Sort me out. What am I missing?

**Without the skill:** a wall of everything it can remember, unordered, half of it already done.

**With the skill:** one ordered list, checked against the real sources: urgent today, this week, waiting on someone else, forgotten, and done since last time.

**Skip it if** you already keep a task manager that is up to date.

**Status:** in daily use in the author's own setup. Plain instructions, no scripts, no network calls. MIT. Issues and suggestions welcome.

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

## More skills from the same setup

These come from one real workflow: a small agency run with 15+ Claude Code sessions in parallel. Each skill fixes one problem that kept happening there.

| Skill | What it fixes |
|---|---|
| [one-pass](https://github.com/RabbitDesigns22/one-pass) | get it right the first time; stop paying tokens for rework |
| [hora-exacta](https://github.com/RabbitDesigns22/hora-exacta) | real date and time in every message, so nothing lands on the wrong day |
| [hands-on](https://github.com/RabbitDesigns22/hands-on) | the agent does what it can and only asks you for codes, keys and payments |
| [easy-for-them](https://github.com/RabbitDesigns22/easy-for-them) | steps people actually follow: direct link, one action per line |
| [one-answer](https://github.com/RabbitDesigns22/one-answer) | one thought-through answer instead of plan, fix, new plan |
| [never-twice](https://github.com/RabbitDesigns22/never-twice) | a shared error log so no session repeats a known mistake |
| [report-now](https://github.com/RabbitDesigns22/report-now) | status checked live this minute, stamped with the time |
| [in-the-loop](https://github.com/RabbitDesigns22/in-the-loop) | a live board so parallel sessions know what the others changed |
| [study-first](https://github.com/RabbitDesigns22/study-first) | reads everything in full and answers point by point, no invented details |
| [session-watchdog](https://github.com/RabbitDesigns22/session-watchdog) | wakes the sessions that got stuck mid-task, leaves the rest alone |
| [skill-harvest](https://github.com/RabbitDesigns22/skill-harvest) | reads your sessions and finds the skills you are missing |
| [small-budget-ads](https://github.com/RabbitDesigns22/small-budget-ads) | Meta Ads rules for 1-5 USD a day ad sets |
| [whatsapp-closer](https://github.com/RabbitDesigns22/whatsapp-closer) | evidence-ranked rules for a WhatsApp sales assistant that closes |
| [whatsapp-number-onboarding](https://github.com/RabbitDesigns22/whatsapp-number-onboarding) | connect a number to the WhatsApp Cloud API in the safe order |
| [proposal-pdf](https://github.com/RabbitDesigns22/proposal-pdf) | short PDF proposals with every price checked against its source |

If one of them saved you a redo, a star helps other people find it.

## License

MIT. Made by [Rabbit Designs](https://github.com/RabbitDesigns22).
