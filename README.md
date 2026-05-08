# Hello Composite Action

My first composite action that greets a person, generates a random number, and runs a goodbye script.

## Inputs

### `name`

**Required** The name of the person to greet. Default: `"World"`.

## Outputs

### `random-number`

A random number generated during the action execution.

## What this action does

1. Prints a greeting message with the provided name
2. Generates a random number and outputs it
3. Sets up the GitHub Actions path
4. Runs a goodbye script

## Example usage

```yaml
uses: josecueva/my-first-composite-action@v1.0
with:
  name: 'Meeeeeee'
```
