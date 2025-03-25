# Swark Helm

Helm Chart repository for Swark, the Swiss Architecture Knife.

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
