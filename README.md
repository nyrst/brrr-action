# brrr docker action

This action allows to use [brrr](https://github.com/nyrst/brrr) as a GitHub action.

## Example usage

Add a step to you workflow:

```yaml
# Runs brrr action
- name: Run brrr
  uses: nyrst/brrr-action@main
  with:
    args: freezer generate
```

See [freezer's workflow](https://github.com/nyrst/freezer/blob/main/.github/workflows/main.yml) for a detailed example.
