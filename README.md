# deprecated

## see https://github.com/SocialGouv/dashlord

---

# socialgouv/dashlord-save-action

Save results from various URL scanners into a single folder for DashLord

## Usage

```yaml
jobs:
  scans:
    steps:
      - uses: "socialgouv/dashlord-save-action@master"
        with:
          url: ${{ matrix.url }}
```
