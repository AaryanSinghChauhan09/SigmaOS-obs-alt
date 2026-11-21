# SigmaOS-obs-alt

SigmaOS integration component for **GPU Screen Recorder**.

## Commands

```bash
sigmaos-obs-alt install   # install package + deploy defaults
sigmaos-obs-alt deploy    # copy config templates to $HOME
sigmaos-obs-alt status    # binary/package/config report
sigmaos-obs-alt reset     # remove deployed config
sigmaos-obs-alt open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
