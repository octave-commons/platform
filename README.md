<!-- READMEFLOW:BEGIN -->
# @promethean-os/platform



[TOC]


## Install

```bash
pnpm -w add -D @promethean-os/platform
```

## Quickstart

```ts
// usage example
```

## Commands

- `build`
- `clean`
- `typecheck`
- `test`
- `lint`
- `lisp`
- `coverage`
- `test:markdown`
- `format`

## License

GPL-3.0-only


### Package graph

```mermaid
flowchart LR
  _promethean_os_platform["@promethean-os/platform\n0.0.1"]
  _promethean_os_utils["@promethean-os/utils\n0.0.1"]
  _promethean_os_discord["@promethean-os/discord\n0.0.1"]
  _promethean_os_embedding["@promethean-os/embedding\n0.0.1"]
  _promethean_os_providers["@promethean-os/providers\n0.0.1"]
  _promethean_os_security["@promethean-os/security\n0.0.1"]
  _promethean_os_platform --> _promethean_os_utils
  _promethean_os_discord --> _promethean_os_platform
  _promethean_os_embedding --> _promethean_os_platform
  _promethean_os_providers --> _promethean_os_platform
  _promethean_os_security --> _promethean_os_platform
  classDef focal fill:#fdf6b2,stroke:#222,stroke-width:2px;
  class _promethean_os_platform focal;
```


<!-- READMEFLOW:END -->
