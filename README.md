# moto-mcp

Part of [moto-platform](https://github.com/moto-platform), an SDV-style diagnostics, telemetry and rider-assistance platform for motorcycles (first vehicle: Honda CL250).

An **independent open-source** Model Context Protocol server (Python). Exposes vehicle telemetry to LLMs as **read-only** tools. Runs on the Raspi 5, on the same machine as `moto-linux-node`, but is a separate repo. Purpose: so other DIY vehicle/motorcycle projects can use it too, and it serves as an org showcase.

**Status:** skeleton, no code yet. The build system, tests and CI are added by `/repo-bootstrap moto-mcp` when work on this repo starts (setup order: `moto-vehicle-defs/docs/ARCHITECTURE.md` §9).

- Architecture and decisions: [moto-vehicle-defs/docs](https://github.com/moto-platform/moto-vehicle-defs/tree/main/docs) (`ARCHITECTURE.md`, `DECISIONS.md`)
- Signals, CAN IDs and DIDs come only from [moto-vehicle-defs](https://github.com/moto-platform/moto-vehicle-defs) (git submodule pinned to a tag)
- Scope rules for contributors and Claude Code: [`CLAUDE.md`](CLAUDE.md)

## License

MIT, see [LICENSE](LICENSE) (D-036).
