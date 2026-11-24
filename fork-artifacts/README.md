# Drizzle ORM compatibility build for effect-jobs

`drizzle-orm-1.0.0-rc.6-effect-jobs.1.tgz` is an unofficial dual ESM/CJS build of `drizzle-orm` for the optional effect-jobs integration. Its base is upstream `v1.0.0-rc.6`; the builder declaration fix is `3495923ee3552fa15c509562db8a781953ad28d4` and the versioned source is `22805d1605504b69159b096491f08f86f0af9336`. See [upstream issue #6728](https://github.com/drizzle-team/drizzle-orm/issues/6728).

The archive was built from the versioned source with the frozen pnpm lockfile, `pnpm --filter @drizzle-team/postgres build`, and `pnpm exec bun --bun run scripts/build.ts --dual` inside `drizzle-orm`, then `npm pack --ignore-scripts` inside `drizzle-orm/dist`.

SHA-256: `a3a5d2a504e61aa947760e0f716090c4037fbee8f6af2ddac209debc80ea25dc`.
