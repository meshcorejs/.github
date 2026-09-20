# meshcore.js

**The bot framework for [MeshCore](https://github.com/meshcore-dev/MeshCore).**

Plug a LoRa radio into Node.js and write a bot the way you would with commands, events, jobs, permissions and roles.

```ts
import { CommandBuilder } from '@meshcorejs/client';

export default new CommandBuilder()
  .setName('hello')
  .setDescription('Say hello')
  .setHandler((ctx) => ctx.reply(`Hello ${ctx.author.name}!`));
```

- 📦 [meshcorejs/meshcore.js](https://github.com/meshcorejs/meshcore.js) — the framework, the transports, the plugins
- 📖 [Documentation](https://meshcorejs.github.io/meshcore.js) — guides and API reference
- 🚀 `pnpm add @meshcorejs/client`

Not affiliated with [MeshCore](https://github.com/meshcore-dev/MeshCore) project. MIT licensed.
