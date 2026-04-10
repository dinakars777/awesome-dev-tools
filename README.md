# Awesome Dev Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome command-line and terminal-based developer tools

Modern development happens in the terminal. This list focuses on CLI/TUI tools that boost developer productivity - from Git helpers to build tools, from system monitors to API testers.

## Contents

- [Version Control](#version-control)
- [Build & Task Runners](#build--task-runners)
- [Code Quality](#code-quality)
- [API Development](#api-development)
- [Database Tools](#database-tools)
- [Container & Orchestration](#container--orchestration)
- [System & Performance](#system--performance)
- [File Management](#file-management)
- [Text Processing](#text-processing)
- [Network Tools](#network-tools)
- [Security & Secrets](#security--secrets)
- [Documentation](#documentation)
- [Productivity](#productivity)
- [Fun](#fun)
- [Related Lists](#related-lists)

## Version Control

- [git-time-machine](https://github.com/dinakars777/git-time-machine) - Visual git reflog browser to undo mistakes.
- [lazygit](https://github.com/jesseduffield/lazygit) - Simple terminal UI for git commands.
- [gitui](https://github.com/extrawurst/gitui) - Blazing fast terminal UI for git written in Rust.
- [tig](https://github.com/jonas/tig) - Text-mode interface for git.
- [gh](https://github.com/cli/cli) - GitHub CLI for managing issues, PRs, and repos.
- [delta](https://github.com/dandavison/delta) - Syntax-highlighting pager for git and diff output.
- [git-absorb](https://github.com/tummychow/git-absorb) - Automatically absorb staged changes into current branch.

## Build & Task Runners

- [just](https://github.com/casey/just) - Command runner with syntax inspired by make.
- [task](https://github.com/go-task/task) - Task runner and build tool written in Go.
- [make](https://www.gnu.org/software/make/) - Classic build automation tool.
- [earthly](https://github.com/earthly/earthly) - Build automation tool that executes in containers.
- [mage](https://github.com/magefile/mage) - Make-like build tool using Go.

## Code Quality

- [ruff](https://github.com/astral-sh/ruff) - Extremely fast Python linter written in Rust.
- [eslint](https://github.com/eslint/eslint) - Pluggable JavaScript linter.
- [shellcheck](https://github.com/koalaman/shellcheck) - Static analysis tool for shell scripts.
- [hadolint](https://github.com/hadolint/hadolint) - Dockerfile linter.
- [yamllint](https://github.com/adrienverge/yamllint) - Linter for YAML files.
- [prettier](https://github.com/prettier/prettier) - Opinionated code formatter.

## API Development

- [httpie](https://github.com/httpie/httpie) - Modern HTTP client with intuitive syntax.
- [curl](https://github.com/curl/curl) - Command-line tool for transferring data with URLs.
- [hurl](https://github.com/Orange-OpenSource/hurl) - Run and test HTTP requests with plain text.
- [grpcurl](https://github.com/fullstorydev/grpcurl) - Command-line tool for interacting with gRPC servers.
- [postman-cli](https://www.postman.com/downloads/) - Postman CLI for API testing.

## Database Tools

- [usql](https://github.com/xo/usql) - Universal command-line interface for SQL databases.
- [pgcli](https://github.com/dbcli/pgcli) - PostgreSQL CLI with auto-completion and syntax highlighting.
- [mycli](https://github.com/dbcli/mycli) - MySQL CLI with auto-completion and syntax highlighting.
- [litecli](https://github.com/dbcli/litecli) - SQLite CLI with auto-completion and syntax highlighting.
- [redis-cli](https://redis.io/docs/ui/cli/) - Redis command-line interface.

## Container & Orchestration

- [docker](https://github.com/docker/cli) - Docker CLI for container management.
- [lazydocker](https://github.com/jesseduffield/lazydocker) - Terminal UI for Docker and Docker Compose.
- [k9s](https://github.com/derailed/k9s) - Kubernetes CLI to manage clusters.
- [kubectl](https://github.com/kubernetes/kubectl) - Kubernetes command-line tool.
- [helm](https://github.com/helm/helm) - Kubernetes package manager.
- [dive](https://github.com/wagoodman/dive) - Tool for exploring Docker image layers.

## System & Performance

- [btop](https://github.com/aristocratos/btop) - Resource monitor with beautiful interface.
- [htop](https://github.com/htop-dev/htop) - Interactive process viewer.
- [bottom](https://github.com/ClementTsang/bottom) - Customizable cross-platform system monitor.
- [hyperfine](https://github.com/sharkdp/hyperfine) - Command-line benchmarking tool.
- [dust](https://github.com/bootandy/dust) - More intuitive version of du.
- [duf](https://github.com/muesli/duf) - Disk usage utility with better UX.

## File Management

- [fzf](https://github.com/junegunn/fzf) - Command-line fuzzy finder.
- [fd](https://github.com/sharkdp/fd) - Simple, fast alternative to find.
- [ripgrep](https://github.com/BurntSushi/ripgrep) - Recursively search directories for regex patterns.
- [bat](https://github.com/sharkdp/bat) - Cat clone with syntax highlighting.
- [exa](https://github.com/ogham/exa) - Modern replacement for ls.
- [zoxide](https://github.com/ajeetdsouza/zoxide) - Smarter cd command.

## Text Processing

- [jq](https://github.com/jqlang/jq) - Command-line JSON processor.
- [yq](https://github.com/mikefarah/yq) - YAML processor.
- [sd](https://github.com/chmln/sd) - Intuitive find and replace CLI.
- [miller](https://github.com/johnkerl/miller) - Like awk/sed/cut/join/sort for CSV/JSON/TSV.
- [gron](https://github.com/tomnomnom/gron) - Make JSON greppable.

## Network Tools

- [mtr](https://github.com/traviscross/mtr) - Network diagnostic tool combining ping and traceroute.
- [bandwhich](https://github.com/imsnif/bandwhich) - Terminal bandwidth utilization tool.
- [dog](https://github.com/ogham/dog) - Command-line DNS client.
- [gping](https://github.com/orf/gping) - Ping with a graph.
- [trippy](https://github.com/fujiapple852/trippy) - Network diagnostic tool.

## Security & Secrets

- [age](https://github.com/FiloSottile/age) - Simple, modern file encryption tool.
- [sops](https://github.com/getsops/sops) - Encrypted file editor for secrets.
- [pass](https://www.passwordstore.org/) - Standard Unix password manager.
- [vault](https://github.com/hashicorp/vault) - Tool for secrets management.
- [trivy](https://github.com/aquasecurity/trivy) - Security scanner for containers and code.

## Documentation

- [mdbook](https://github.com/rust-lang/mdBook) - Create books from Markdown files.
- [glow](https://github.com/charmbracelet/glow) - Render Markdown in the terminal.
- [tldr](https://github.com/tldr-pages/tldr) - Simplified man pages with practical examples.
- [cheat](https://github.com/cheat/cheat) - Create and view interactive cheatsheets.

## Productivity

- [tmux](https://github.com/tmux/tmux) - Terminal multiplexer.
- [zellij](https://github.com/zellij-org/zellij) - Terminal workspace with batteries included.
- [starship](https://github.com/starship/starship) - Minimal, fast shell prompt.
- [direnv](https://github.com/direnv/direnv) - Load environment variables based on directory.
- [asdf](https://github.com/asdf-vm/asdf) - Manage multiple runtime versions.

## Fun

- [moody](https://github.com/dinakars777/moody) - Your MacBook has feelings - hardware events trigger personality responses.
- [cmatrix](https://github.com/abishekvashok/cmatrix) - Matrix-style terminal screensaver.
- [cowsay](https://github.com/piuccio/cowsay) - Configurable talking cow.
- [lolcat](https://github.com/busyloop/lolcat) - Rainbow coloring for terminal output.
- [figlet](http://www.figlet.org/) - Create ASCII art text banners.

## Related Lists

- [awesome-tui](https://github.com/dinakars777/awesome-tui) - Curated list of TUI apps and frameworks.
- [awesome-cli-apps](https://github.com/agarrharr/awesome-cli-apps) - Command-line applications.
- [awesome-shell](https://github.com/alebcay/awesome-shell) - Command-line frameworks and tools.
- [terminals-are-sexy](https://github.com/k4m4/terminals-are-sexy) - Terminal frameworks and resources.

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
