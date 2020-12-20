# brrr docker action

This action allows to use [brrr](https://github.com/nyrst/brrr) as a GitHub action.

## Inputs

### `command`

**Required** The command to use. Default `help`.

## Example usage

```yaml
uses: uses: nyrst/brrr-action@master
with:
  command: 'info exa'
```