# projectname

A basic let-go CLI application template.

## Development

Install dependencies with [mise](https://mise.jdx.dev/getting-started.html) (or manaully consulting the `.mise.toml` file):

```bash
mise trust && mise install
```

Run main application commands during development:
```bash
lgx --help
lgx run
lgx run -- help
lgx run -- greet
lgx test
lgx fmt
lgx nrepl
```

Buld a binary and use it:

```bash
lgx build
bin/projectname --help
bin/project --version
bin/project help greet
bin/project greet
```
