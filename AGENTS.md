# Default Workspace Guidance

This is the user's DSH default Workspace. Work normally inside `/home/软件旧的/软件管理`.

Use the `dsh_resources` tool whenever the user asks about DSH state. It provides complete paged reads of installed plugins and files, skills, persistent memory, previous sessions, storage, unredacted settings, and credentials through native DSH services. It never grants mutation rights outside the Workspace.

Maintain durable user-approved notes in `/home/软件旧的/软件管理/MEMORY.md`. Put Workspace-local skills under `/home/软件旧的/软件管理/.dsh/skills`. DSH also discovers user-wide skills under `/home/软件/列表/DeepSeekHarness/数据/.dsh/skills` without custom skill-directory configuration.

For reasoning controls, trust a model's explicit `reasoningEfforts` mapping first. The better-basicfun guard only fills a small evidence-backed set for third-party gateways and leaves unknown or native models untouched.

Sensitive resource results may be sent to the configured model provider. Follow the user's request and the active DSH permission preset for every mutation.
