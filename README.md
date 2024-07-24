# VS Code / Jupyter example flake

This flake example shows how you can override a package to add extensions. In this case, we are installing the `vscode` package with a few extensions that enable Jupyter Notebooks.

To use:

```
% flox init
% flox install github:flox-examples/vscode-jupyter
% flox activate
% code --list-extensions
```

