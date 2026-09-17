# Architecture and Delivery

## High-level application shape

The private application follows a server-rendered embedded SaaS architecture with authenticated application routes, database-backed workflows, platform API integration, billing/compliance support, and controlled AI-assisted review paths.

A simplified public view is:

```text
Embedded application shell
        |
        +--> authenticated server routes
        |
        +--> domain workflows
        |
        +--> database / ORM layer
        |
        +--> external platform APIs
        |
        +--> bounded AI-assisted review path
        |
        +--> validation / health / operational controls
```

## Delivery model

Development is organized around small reviewed branches and pull requests rather than direct uncontrolled production changes. Stable checkpoints are preserved, and production deployment is treated as a separate operational action from source-code merge.

Key delivery practices include:

- explicit production checkpoints
- controlled deployment rather than blind auto-deploy
- health verification after deployment
- staged capability activation
- source/runtime alignment checks
- conservative handling of higher-impact permissions

## Boundary discipline

The private application intentionally separates:

- client-visible code from server-only implementation
- read-only capabilities from mutating capabilities
- permission acquisition from action authorization
- product logic from infrastructure controls
- AI assistance from deterministic application behavior

These boundaries reduce accidental coupling and make higher-risk behavior easier to inspect and gate.
