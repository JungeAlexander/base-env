
```
poetry install --no-root
jupyter labextension install @pyviz/jupyterlab_pyviz
```

## JupyterLab settings

### Custom keyboard shortcuts

```
{
    "shortcuts": [
        {
            "command": "jupyterlab_code_formatter:format_all",
            "keys": [
                "Ctrl Shift F"
            ],
            "selector": "body"
        }
    ]
}
```
