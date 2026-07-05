# AION Vibe-Trading Fork Sync

This repository is Jody's fork of `HKUDS/Vibe-Trading`.

## Remotes

- `origin`: `https://github.com/jodysachse72-arch/Vibe-Trading.git`
- `upstream`: `https://github.com/HKUDS/Vibe-Trading.git`

## Sync Procedure

From `C:\Users\Jody\Documents\AION-Capabilities\Vibe-Trading`:

```powershell
git fetch upstream
git switch main
git merge --ff-only upstream/main
git push origin main
```

If `--ff-only` fails, stop and review upstream changes before merging. Preserve the upstream `LICENSE` and `NOTICE` files.
