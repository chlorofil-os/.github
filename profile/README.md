# ChloroFilOS

**Grow your workspace, one card at a time.**

ChloroFilOS is a framework for browser workspaces built from one tree of cards. Cards nest to any depth,
open into a full stage, and each one can host a live mini-app from its card type.

- **Zoom in, back out** — a card fills the stage; a breadcrumb takes you back.
- **Same verbs everywhere** — one toolbar on every card, at every level.
- **Cards are apps** — a card type supplies its views, actions and data.
- **People and agents, one registry** — every action is a command (MCP-shaped), audited and undoable.
- **Any shell** — framework-free TypeScript core; React and Web Components shells, Vue, Svelte, Solid and Lit adapters.

Packages: `@chlorofil-os/{core,react,elements,vue,svelte,solid,lit}` on GitHub Packages.

## Dev tools

| Repo | What it does |
| --- | --- |
| [seedpod](https://github.com/chlorofil-os/seedpod) | Your LXC machines, and the Docker inside them, in one tree. VS Code extension + MCP server. |
| [seedbed](https://github.com/chlorofil-os/seedbed) | Raise LXD dev machines from a template: copy-on-write clones per branch or task, DNS and ssh-config in step. |
| [sprout](https://github.com/chlorofil-os/sprout) | One Docker dev environment for Laravel, CakePHP, Next.js, Django and Go, driven by configuration. |
