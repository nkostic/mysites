## Monorepo for my sites and projects

This is attempt to organize better my projects and sites in a single monorepo.

Apps folder would contain apps and sites (sveltekit apps cms and mysite currently added)
Packages folder would contain libraries and design systems.

pnpm workspaces with turborepo used to manage monorepo. It is extremely fast because of the casing not only for devs but for the whole teams and is simple to configure (turborepo pipelines)

```sh
pnpm i
```

```sh
pnpm turbo run build  # build all apps
```
