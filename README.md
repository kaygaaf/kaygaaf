### hey, I'm Kay van Dijk

I tinker with automation, home setups, and small tools, and I send a patch when something I use is wrong.

Main thing right now is [tattlr](https://github.com/kaygaaf/tattlr). It reads the logs your coding agents leave behind and gives you a rap sheet of what they actually did. It can plant trap creds, and block bad calls live. Nothing leaves the machine.

```
brew install kaygaaf/tap/tattlr
# or
npm i -g tattlr
```

Latest release is [v0.3.0](https://github.com/kaygaaf/tattlr/releases/tag/v0.3.0). [tattlr-action](https://github.com/kaygaaf/tattlr-action) runs the same check in CI.

#### Patches elsewhere

Merged:

- [dandavison/delta#2334](https://github.com/dandavison/delta/pull/2334): emit the hunk record when the hunk header row is skipped
- [compose-spec/compose-go#992](https://github.com/compose-spec/compose-go/pull/992): pull out variables nested inside required-error messages
- [compose-spec/compose-go#997](https://github.com/compose-spec/compose-go/pull/997): keep resources used by pre_start hooks and jobs
- [awesome-gemini-cli#365](https://github.com/Piebald-AI/awesome-gemini-cli/pull/365) and [awesome-ai-security-tools#227](https://github.com/scadastrangelove/awesome-ai-security-tools/pull/227): tattlr got listed

In review:

- [jestjs/jest#16580](https://github.com/jestjs/jest/pull/16580): don't tell an npx jest run to update snapshots with `npm run npx`
- [yarnpkg/berry#7360](https://github.com/yarnpkg/berry/pull/7360): keep an ampersand inside a patch path
- [helix-editor/helix#16499](https://github.com/helix-editor/helix/pull/16499): don't freeze on Enter in a Rust file with a stack of attributes
- [anchore/syft#5639](https://github.com/anchore/syft/pull/5639): keep a Yarn production package installed through an npm alias
- [anchore/syft#5638](https://github.com/anchore/syft/pull/5638): keep a required Go module when exclude names another version
- [ollama/ollama#19912](https://github.com/ollama/ollama/pull/19912): don't treat arr[img-1] as an image placeholder
- [python-poetry/poetry#11284](https://github.com/python-poetry/poetry/pull/11284): keep a legacy lock extra empty when the requirement has no brackets
- [python-poetry/poetry#11283](https://github.com/python-poetry/poetry/pull/11283): keep a bracket in a path or URL when the extra is at the end
- [anchore/syft#5634](https://github.com/anchore/syft/pull/5634): keep installed dpkg packages marked for removal
- [anchore/grype#3949](https://github.com/anchore/grype/pull/3949): don't rewrite CPE fields that only contain the package name
- [npm/cli#10348](https://github.com/npm/cli/pull/10348): keep the commit on a git resolved URL in a yarn lock
- [mikefarah/yq#2967](https://github.com/mikefarah/yq/pull/2967): accept an RFC3339 datetime that uses a space instead of T
- [charmbracelet/x#1048](https://github.com/charmbracelet/x/pull/1048): don't let a cut-off UTF-8 rune hide an ESC
- [securego/gosec#1832](https://github.com/securego/gosec/pull/1832) and [#1833](https://github.com/securego/gosec/pull/1833): detect a few more token shapes
- [docker/buildx#4212](https://github.com/docker/buildx/pull/4212): imagetools and registry mirrors that include a path

#### Smaller tools

- [dotenv-guard](https://github.com/kaygaaf/dotenv-guard): pre-commit hook that stops `.env` files and obvious secrets from getting committed
- [compose-env](https://github.com/kaygaaf/compose-env): which `${VARS}` a compose file needs, without printing values
- [busy-port](https://github.com/kaygaaf/busy-port): what's sitting on port 8080?
- [ha-yaml-kit](https://github.com/kaygaaf/ha-yaml-kit): checks for Home Assistant automation YAML

If something here helps you out, coffee's always welcome:

**[Support on Ko-fi](https://ko-fi.com/kayorama)**

Site: [kayorama.nl](https://kayorama.nl)
