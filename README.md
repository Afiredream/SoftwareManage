# DSH Default Workspace

This directory is managed as the safe default Workspace by the `better-basicfun` plugin.

- Normal files in this directory are writable in DSH's `workspace-write` mode.
- `MEMORY.md` is persistent memory for sessions in this Workspace.
- Project-local skills belong in `.dsh/skills/<skill-name>/SKILL.md`.
- User-wide DSH skills belong in `/home/软件/列表/DeepSeekHarness/数据/.dsh/skills` and are discovered by DSH automatically.
- Use the read-only `dsh_resources` tool to inspect installed plugins and source files, complete skill bodies, memory, full session records, storage files, unredacted settings, and credentials.
- DSH settings, credentials, profiles, and raw state remain outside the Workspace write boundary.
- Third-party reasoning controls are capability-gated; native DSH model controls remain authoritative.

Security: this plugin intentionally makes sensitive DSH information readable by the model. Tool results may be sent to the configured model provider.

DSH home: `/home/软件/列表/DeepSeekHarness/数据/.dsh`
Default Workspace: `/home/软件旧的/软件管理`
