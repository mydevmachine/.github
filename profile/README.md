<h1 align="center">devmachine</h1>

<p align="center">
  <strong>Code from anywhere.</strong><br>
  Any machine you own. An isolated workspace for every project. No lock-in. Free.
</p>

<p align="center">
  <a href="https://mydevmachine.sh/">Website</a> ·
  <a href="https://mydevmachine.sh/getting-started/">Getting started</a> ·
  <a href="https://mydevmachine.sh/guides/">Guides</a> ·
  <a href="https://mydevmachine.sh/packages/">Packages</a> ·
  <a href="https://mydevmachine.sh/app/">Mac app</a> ·
  <a href="https://mydevmachine.sh/changelog/">Changelog</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/mydevmachine/devmachine/main/.github/readme/161-machines-map-selected.webp" alt="The network map in the Devmachine app: the internet at the top, published sites linked down to five machines — laptop and a Lima VM on this Mac, main and staging at a VPS provider, homebox at home over the tailnet." width="100%">
</p>

devmachine turns a Debian or Ubuntu machine into your own coding machine, with
one workspace per project. A VPS you rent, an old laptop, or a virtual machine
on your Mac: devmachine sets it up and locks it down. Each project gets an
isolated workspace with its own tech stack, logins and AI subscription, and
Claude Code, Codex and your skills ready in each one.

```sh
curl -fsSL https://mydevmachine.sh/install.sh | sh   # or: brew install mydevmachine/tap/devmachine
devmachine setup                                     # connect your machine and lock it down
devmachine skills add                                # work with your machines from any LLM session
```

- **Open source.** The CLI and every package are open source, under MIT.
- **No lock-in.** Underneath it is plain Linux, SSH and git. Stop using
  devmachine and your machines still work.
- **Extensible via packages.** Add a tool with one package, or write your own.
- **Your machines, your data.** A VPS you rent, a computer you already have,
  or a virtual machine of your own.

## Repositories

| Repository | What it is |
| --- | --- |
| [devmachine](https://github.com/mydevmachine/devmachine) | The CLI, in Go. Start here. |
| [packages](https://github.com/mydevmachine/packages) | Ready-made packages: coding agents, Docker, Caddy, Tailscale, DNS and more. |
| [docs](https://github.com/mydevmachine/docs) | Source of [mydevmachine.sh](https://mydevmachine.sh/). |
| [homebrew-tap](https://github.com/mydevmachine/homebrew-tap) | `brew install mydevmachine/tap/devmachine` and `brew install --cask mydevmachine/tap/devmachine-app`. |
| [app-releases](https://github.com/mydevmachine/app-releases) | Signed and notarized builds of [Devmachine for Mac](https://mydevmachine.sh/app/). |

## Where to go next

- [Your first devmachine, explained](https://mydevmachine.sh/guides/your-first-devmachine/) — the first commands, done slowly.
- [Set up with a coding agent](https://mydevmachine.sh/agent-setup/) — hand one page to your agent and let it do the setup.
- [Guides](https://mydevmachine.sh/guides/) — Claude from your phone, sites with HTTPS, a sandbox per client, and more.
- [Commands](https://mydevmachine.sh/reference/commands/) — every command, its flags and its output.
