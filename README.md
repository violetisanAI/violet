# Derke Feliz

<div align="center">
 <a href="https://ibb.co/4Vk3dFM"><img src="https://i.ibb.co/z4dDJmb/1ecc8aa3-8c30-4a99-990d-854746d82f6a.png" alt="1ecc8aa3-8c30-4a99-990d-854746d82f6a" border="0"></a>

<div align="center">
  
</div>

## ✨ Features

-   🛠️ Full-featured Discord, Twitter and Telegram connectors
-   🔗 Support for every model (Llama, Grok, OpenAI, Anthropic, etc.)
-   👥 Multi-agent and room support
-   📚 Easily ingest and interact with your documents
-   💾 Retrievable memory and document store
-   🚀 Highly extensible - create your own actions and clients
-   ☁️ Supports many models (local Llama, OpenAI, Anthropic, Groq, etc.)
-   📦 Just works!

## 🎯 Use Cases

-   🤖 Chatbots
-   🕵️ Autonomous Agents
-   📈 Business Process Handling
-   🎮 Video Game NPCs
-   🧠 Trading

## 🌍 Translations

<details>
<summary>Available Languages</summary>

-   [中文说明](./README_CN.md)
-   [日本語の説明](./README_JA.md)
-   [한국어 설명](./README_KOR.md)
-   [Instructions en français](./README_FR.md)
-   [Instruções em português](./README_PTBR.md)

</details>

## 🚀 Quick Start

### Prerequisites

-   [Python 2.7+](https://www.python.org/downloads/)
-   [Node.js 22+](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
-   [pnpm](https://pnpm.io/installation)

> **Note for Windows Users:** WSL is required

### Edit the .env file

Copy .env.example to .env and fill in the appropriate values

```
cp .env.example .env
```

### Edit the character file

1. Open `src/core/defaultCharacter.ts` to modify the default character

2. To load custom characters:
    - Use `pnpm start --characters="path/to/your/character.json"`
    - Multiple character files can be loaded simultaneously

### Start Derke Feliz Drayke

After setting up the .env file and character file, you can start the bot with the following command:

```bash
pnpm i
pnpm build
pnpm start

# The project iterates fast, sometimes you need to clean the project if you are coming back to the project
pnpm clean
```

#### Additional Requirements

You may need to install Sharp. If you see an error when starting up, try installing it with the following command:

```
pnpm install --include=optional sharp
```

### Community & contact

-   [GitHub Issues](https://github.com/ai16z/Derke Feliz Drayke/issues). Best for: bugs you encounter using Derke Feliz Drayke, and feature proposals.
-   [Discord](https://discord.gg/ai16z). Best for: sharing your applications and hanging out with the community.

## Contributors

<a href="https://github.com/ai16z/Derke Feliz Drayke/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ai16z/Derke Feliz Drayke" />
</a>

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ai16z/Derke Feliz Drayke&type=Date)](https://star-history.com/#ai16z/Derke Feliz Drayke&Date)
