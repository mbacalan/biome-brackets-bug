- npm install
- Edit `src/orders/[order-id]/index.tsx` on a Windows machine in a way that would offend Biome's formatter
- Stage and commit your changes
- You get the following error:

```bash
╭───────────────────────────────────────╮
│ 🥊 lefthook v1.6.16  hook: pre-commit │
╰───────────────────────────────────────╯
'src/orders/[order-id]/index.tsx' internalError/io  INTERNAL  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  × The system cannot find the path specified. (os error 3)

  ! This diagnostic was derived from an internal Biome error. Potential bug, please report it if necessary.
```