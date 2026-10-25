<p align="center"><img src="./logo.svg" width="64" alt="aparté"></p>
<h3 align="center">aparté</h3>
<p align="center">AI chat components for the web — and small models that run in the chat.</p>
<p align="center">
  <a href="https://apartejs.dev">apartejs.dev</a> ·
  <a href="https://www.npmjs.com/org/aparte">npm</a> ·
  <a href="https://huggingface.co/apartejs">Hugging Face</a>
</p>

---

### The chat library

**[aparte](https://github.com/apartejs/aparte)** — AI chat and agent UI as Web Components,
with the runtime inside: streaming, tool calls a human approves, the agent loop.
React, Vue, Svelte, Angular or plain HTML. Zero third-party dependencies at the core.

`npm i @aparte/core@beta` · [Docs](https://apartejs.dev) · [Components](https://apartejs.dev/components/) · [Templates](https://apartejs.dev/templates/)

### Small models, in the chat

One small file each, on the device, no API call. The same model in every runtime.

| Model | What it does | Size | JS / Node | iOS · macOS | Android · JVM |
|---|---|---|---|---|---|
| **aparte-titler** | titles a conversation from its first message, 17 languages | 133 KB | [model](https://github.com/apartejs/aparte-titler-model) | [Swift](https://github.com/apartejs/aparte-titler-swift) | [Kotlin](https://github.com/apartejs/aparte-titler-kotlin) |
| **aparte-privacy** | finds personal data: names, addresses, emails, phone numbers | ~200 KB | [model](https://github.com/apartejs/aparte-privacy-model) | [Swift](https://github.com/apartejs/aparte-privacy-swift) | [Kotlin](https://github.com/apartejs/aparte-privacy-kotlin) |
| **aparte-secrets** | finds passwords, API keys, tokens, private keys | ~200 KB | [model](https://github.com/apartejs/aparte-secrets-model) | [Swift](https://github.com/apartejs/aparte-secrets-swift) | [Kotlin](https://github.com/apartejs/aparte-secrets-kotlin) |

Also: **[aparte-secrets-action](https://github.com/apartejs/aparte-secrets-action)** — the secrets
model as a GitHub Action, on the runner, no network.

### Built with aparté

**[monaparte](https://github.com/apartejs/monapartejs)** — a chat assistant whose model runs
entirely in the browser. [Try it →](https://mon.apartejs.dev)

---

<sub>pronounced <i>ah-par-té</i> — French <i>aparté</i>: a line spoken aside.</sub>
