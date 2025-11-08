# Failed to infer the type of `.parent` for `pathlib.PurePath`/`pathlib.Path`/...

Failed to resolve the type of [`PurePath.parent`/`Path.parent`][path-parent] in [`pathlib`][pathlib], the type is inferred as `Unknown`.

[path-parent]: https://docs.python.org/3.13/library/pathlib.html#pathlib.PurePath.parent
[pathlib]: https://docs.python.org/3.13/library/pathlib.html

## Minimal Reproducible Example

1. A GitHub Repository is [here][gh], you can clone and open it with [Zed].
2. ty Playground is [here][play].

[gh]: https://github.com/ynty/ty-mwe/tree/report/pathlib-path-parent
[play]: https://play.ty.dev/fe521402-de34-454d-9d3e-5cdec121a06f

[Zed]: https://zed.dev

## ty Version

ty 0.0.1-alpha.25 (3abd4c968 2025-10-29)
