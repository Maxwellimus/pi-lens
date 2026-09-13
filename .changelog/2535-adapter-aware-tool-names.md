---
section: Fixed
---

- **Resolve agent-facing advisory tool names for their delivery host (refs #2535)** — actionable-warning, code-quality, git-guard, disposition, and generated-skip advisories use the shared registry resolver; MCP output names `pilens_diagnostics` and `pilens_project_scan`, while pi output keeps `lens_diagnostics`. Pi-only tools are declared in `PI_ONLY_TOOL_REASONS`, and a known tool with no mapping on the requested host resolves to `undefined` instead of a dead name.
