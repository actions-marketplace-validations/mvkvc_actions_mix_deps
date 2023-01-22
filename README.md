# actions_mix_deps

This action installs and caches dependencies for Elixir projects using `mix deps.get` for faster subsequent runs. The input arguments can be seen in the [action.yaml](action.yaml) file.

To include this action in your workflow, add the following line:

```yaml
- uses: actions_mix_deps@v1.0.1-alpha
  with:
    ...
```
