# wpk-bucket

Manifests for [wpk](https://github.com/OrkWard/winpkgs): wpk itself, and
packages whose Scoop manifests use install scripts that wpk does not run.

Manifests use the Scoop format restricted as described in winpkgs'
`DESIGN.md`: no `pre_install`, `post_install`, `installer`, `uninstaller`,
`psmodule` or `env_add_path`.

| Package | Differs from Scoop's |
|---|---|
| `7zip` | No context menu `.reg` files; no arm64 build, which arm64 Windows replaces with the x64 one. |
