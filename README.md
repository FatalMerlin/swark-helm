[![Static Badge](https://img.shields.io/badge/K%26M_Educational_Week-2025_March-blue)](https://k-m.info)
[![Static Badge](https://img.shields.io/badge/K%26M_Weiterbildungswoche-2025_M%C3%A4rz-blue)](https://k-m.info)

# Swark Helm

Helm Chart repository for Swark, the [Swiss Architecture Knife](https://github.com/swiss-architecture-knife).

## Testing

From the repository root, run the following:

### Install

```bash
# optionally, set your kube context: `kubectl config use-context <context>`
helm upgrade --install swark charts/swark -n swark --create-namespace -f test/values.yaml
```

### Uninstall

```bash
helm uninstall swark -n swark
```
