### hey, I'm Kay van Dijk

I tinker with automation, home setups, small tools, and whatever problem is annoying me that week.

Main thing right now is [tattlr](https://github.com/kaygaaf/tattlr). It reads the logs your AI coding agents leave behind and gives you a rap sheet of what they actually did. It can also plant trap creds to see if anything goes snooping, and block bad calls live.

```
brew install kaygaaf/tap/tattlr
# or
npm i -g tattlr
```

Latest is [v0.3.0](https://github.com/kaygaaf/tattlr/releases/tag/v0.3.0) (on GitHub and npm). It added rules for tearing down infra, poking cloud metadata endpoints, and container runs that grab the host. There's also [tattlr-action](https://github.com/kaygaaf/tattlr-action) if you want the same check in CI.

#### Smaller tools

- [dotenv-guard](https://github.com/kaygaaf/dotenv-guard): pre-commit hook that stops `.env` files and obvious secrets from getting committed
- [compose-env](https://github.com/kaygaaf/compose-env): tells you which `${VARS}` your compose file needs that aren't set, without printing values
- [busy-port](https://github.com/kaygaaf/busy-port): what's sitting on port 8080?
- [ha-yaml-kit](https://github.com/kaygaaf/ha-yaml-kit): templates and checks for Home Assistant automation YAML

#### Fixes that landed elsewhere

- [dandavison/delta#2334](https://github.com/dandavison/delta/pull/2334): emit the hunk record when the hunk header row is skipped
- [compose-spec/compose-go#992](https://github.com/compose-spec/compose-go/pull/992): pull out variables nested inside required-error messages
- [Piebald-AI/awesome-gemini-cli#365](https://github.com/Piebald-AI/awesome-gemini-cli/pull/365) and [awesome-ai-security-tools#227](https://github.com/scadastrangelove/awesome-ai-security-tools/pull/227): tattlr got listed

If something here helps you out, coffee's always welcome:

**[Support on Ko-fi](https://ko-fi.com/kayorama)**

Site: [kayorama.nl](https://kayorama.nl)
