# runbot-hq

GitHub Actions for self-hosted macOS runners — powered by on-device Apple Intelligence and local AI models. No cloud APIs. No API keys. No per-run cost

> The actions are composable — you can mix and match them with any action from the official GitHub Actions Marketplace. For example, combine local-ai-cli-action with Slack or Google Analytics actions to build powerful automations that run at zero cost.

## Actions

| Action | Description | Author | Downloads |
|---|---|---|---|
| [afm-release-notes-action](https://github.com/runbot-hq/afm-release-notes-action) | Generate AI release notes using Apple Intelligence (on-device). Returns `release_title` and `release_body` — no release created. | [@eonist](https://github.com/eonist) | ![](https://img.shields.io/github/downloads/runbot-hq/afm-cli/total?label=&color=purple&logo=github) |
| [local-ai-code-review-action](https://github.com/runbot-hq/local-ai-code-review-action) | Review PR diffs using a local Ollama model (Qwen, CodeGeeX, etc.). No cloud API required. | [@eonist](https://github.com/eonist) | ![](https://img.shields.io/github/downloads/runbot-hq/local-ai-cli/total?label=&color=purple&logo=github) |
| [translation-framework-action](https://github.com/runbot-hq/translation-framework-action) | Translate `.xcstrings`, `.strings`, or Markdown files using on-device Apple Translation. | [@eonist](https://github.com/eonist) | ![](https://img.shields.io/github/downloads/runbot-hq/translate-cli/total?label=&color=purple&logo=github) |

> All actions **requires** a self-hosted macOS runner (Apple Silicon). Part of the [RunBot](https://github.com/runbot-hq/run-bot) ecosystem.
