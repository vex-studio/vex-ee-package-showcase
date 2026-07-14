# Vex EE Designer Showcase

**Live:** https://vex-studio.github.io/vex-ee-package-showcase/

HyperFrames ([heygen-com/hyperframes](https://github.com/heygen-com/hyperframes)) compositions for each vacuumed BovineLabs package — short motion cards so designers can see what each tool is for.

| Path | Purpose |
|------|---------|
| `index.html` | Hub catalog |
| `packages/<slug>/` | Designer page (copy + iframe) |
| `packages/<slug>/composition/` | HyperFrames project (`hyperframes preview`) |

```bash
tools/hyperframes-showcase.sh list
tools/hyperframes-showcase.sh lint
tools/hyperframes-showcase.sh preview timeline-physics
tools/hyperframes-showcase.sh serve-docs   # http://127.0.0.1:8765
```

Public mirror repo (Pages deploy): https://github.com/vex-studio/vex-ee-package-showcase
