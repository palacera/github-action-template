# Hello World

Say hello to the world or someone in it.

## Usage

Example usage of saying hello to a person:

```yaml
- uses: palacera/github-action-template@latest
  id: greeting
  with:
    person-name: "Peter Parker"

- run: echo ${{ steps.greeting.outputs.hello-text }}
```

### Inputs

|     Input     | Description                    | Required |
|:-------------:|--------------------------------|:--------:|
| `person-name` | Name of person to say hello to |    no    |         

### Outputs

|    Output    | Description                |
|:------------:|----------------------------|
| `hello-text` | Text that displays hello.. |

## License

The scripts and documentation in this project are released under the [MIT License](LICENSE).

## Contributions

Contributions are welcome! See [Contributor's Guide](CONTRIBUTING.md)


