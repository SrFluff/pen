# Pen 🖊️

Simple Python build tool\
\
To start using Pen, run:
```
pen help
pen init
```

## Features

### Dependency resolution

Pen can automatically install and upgrade Python modules
through `pen install`.\
\
Pen can also list a project's dependencies with `pen dependencies`.

### Serving

Pen can serve an http server with `pen serve`.

### Building

Pen can build your project with `pen build`. You can also
have Pen test your files before building.

### Cleaning

Pen can remove caches and temporary files with `pen clean`.

### Testing

Pen can test files without building using the `pen build` command.\
Tests include syntax checking and linting. If the linter fails, pen will automatically fix it.\
*NOTE: Pen relies on ruff as its linter*

### Lockfiles

Pen can generate a `requirements.txt` file with `pen lock`. This also
forces packages into specific versions.
