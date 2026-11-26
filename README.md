# Carlos Ferrabone (`@broli`)

**IT Operations & Delivery Lead | Linux Systems & Rust Developer**

Started programming on a Commodore 64 in BASIC. Daily-driving Linux since Red Hat 7.0 and Fedora Core 1, with nearly two decades on Gentoo before settling on Arch/CachyOS. Former Freenode regular (`#fluxbox`, `#fedora-es`) and early contributor to Miro (Participatory Culture Foundation / Mozilla). Today I lead enterprise IT operations and build Linux desktop tooling, Wayland compositor patches, and Python automation.

### Upstream & Systems Work

- **[noctalia-dev/luciole](https://github.com/noctalia-dev/luciole)** — Contributor to the native Wayland file manager (C++ / Meson / GIO):
  - [PR #162](https://github.com/noctalia-dev/luciole/pull/162) *(Merged)*: Sync Save file chooser filename extensions with active format filters for XDG portal callers (+642/-44 across 9 files).
  - [PR #89](https://github.com/noctalia-dev/luciole/pull/89) *(Merged)*: Add configurable single-click location bar editing option.
  - [PR #91](https://github.com/noctalia-dev/luciole/pull/91) *(Merged, Co-Reviewed & Verified)*: Custom folder icon & symlink metadata resolution (`NOFOLLOW_SYMLINKS` edge-case catches).
- **[niri-wm/niri](https://github.com/niri-wm/niri)** — Contributor & active triager for the scrollable-tiling Wayland compositor (Rust / Smithay / GLES2):
  - [PR #4731](https://github.com/niri-wm/niri/pull/4731) *(Merged)*: Fix stuck modifier state in nested winit sessions on focus loss.
  - [PR #4719](https://github.com/niri-wm/niri/pull/4719) *(Merged)*: Add live-reloaded KDL option to hide host cursor in nested development sessions.
  - [PR #4851](https://github.com/niri-wm/niri/pull/4851) *(Open)*: Accessibility dwell clicker with GLES2 cursor ring shader, KDL config, and IPC mode actions (+2,080/-31 across 21 files).
  - [Multi-monitor & input physics](https://github.com/Atan-D-RP4/niri/pull/2): Per-monitor isolation, spring physics animations, and temporal key acceleration (fork collaboration).
- **[noctalia-dev/noctalia](https://github.com/noctalia-dev/noctalia)** — Contributor to the customizable Wayland desktop shell (C++):
  - [PR #5543](https://github.com/noctalia-dev/noctalia/pull/5543) *(Open)*: Configurable taskbar launch feedback animations (`bounce`, `pop`, `pulse`) with unit tests.
- **[GraphiteEditor/Graphite](https://github.com/GraphiteEditor/Graphite)** — Contributor to the node-based 2D graphics editor (Rust / WGPU):
  - [PR #4966](https://github.com/GraphiteEditor/Graphite/pull/4966) *(Open)*: Fix infinite `SurfaceOutdated` render loop on stale WGPU surfaces under Wayland/hybrid GPUs.
- **[niri-screenshot-daemon](https://github.com/broli/niri-screenshot-daemon)** — Event-driven multi-session screenshot watchdog bridging Niri IPC to Satty with D-Bus notifications & host clipboard copy.
- **Internal Tooling & Automation** — Building PySide6 desktop utilities, Playwright pipelines, and local LLM integrations that replaced 26+ hours/week of manual operations.
- **Enterprise IT Delivery** — 19 years leading infrastructure, incident response, and Agile delivery across regional operations.

### Selected Projects

| Project | Description | Stack |
| :--- | :--- | :--- |
| **[beholder-brother](https://github.com/broli/beholder-brother)** | Lightweight system telemetry daemon & read-only inline-SVG viewer for low-power Linux hosts | `Rust` `Linux Telemetry` `SVG` |
| **[niri-screenshot-daemon](https://github.com/broli/niri-screenshot-daemon)** | Event-driven multi-session screenshot watchdog for Niri | `Rust` `Wayland IPC` `Unix Sockets` |
| **[run-proton-tui](https://github.com/broli/run-proton-tui)** | Interactive TUI launcher for running games under Proton/Wine outside Steam | `Go` `Bubbletea` `Proton` |
| **[tachopulse](https://github.com/broli/tachopulse)** | Hardware telemetry widget for the Noctalia v5 desktop shell | `QML` `JavaScript` `Linux Sensors` |
| **[OllamaGUI](https://github.com/broli/OllamaGUI)** | Native desktop client for streaming chat with local Ollama models | `Python` `PySide6` `Async` |
| **[pkb-daily-logs](https://github.com/broli/pkb-daily-logs)** | Automated compliance reporting pipeline | `Python` `Playwright` |

### Links

- **Portfolio:** [portfolio.ferrabone.org](https://portfolio.ferrabone.org)
- **LinkedIn:** [linkedin.com/in/carlos-ferrabone](https://linkedin.com/in/carlos-ferrabone/)
- **Email:** [carlos.ferrabone@gmail.com](mailto:carlos.ferrabone@gmail.com)
