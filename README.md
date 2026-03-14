# MonoForge

A minimal, modern **TypeScript monorepo template** powered by Turbo.

## Stack

* TypeScript
* Turbo
* Biome

## Structure

```
apps/        # Applications
packages/    # Shared packages
```

## Getting Started

Install dependencies:

```
bun install
```

Run all development tasks:

```
bun dev
```

Build everything:

```
bun run build
```

## Scripts

```
bun dev                       # Run dev tasks
bun run build                 # Build all packages
bun run start                 # Build and start all packages
bun run format-and-lint       # Lint the repo
bun run format-and-lint:fix   # Lint and fix the repo
bun run check-types           # Type checking
```

## License

MIT
