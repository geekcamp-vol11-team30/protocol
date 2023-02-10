## format
install clang-format (for mac user)
```console
$ brew install clang-format
```
then run
```console
$ find . -name "*.proto" | xargs clang-format -i
```

if you are using VSCode, you can install the extension [clang-format](https://marketplace.visualstudio.com/items?itemName=xaver.clang-format) and add the following configuration to your settings.json
```json
    "[proto3]": {
        "editor.defaultFormatter": "xaver.clang-format"
    },
```
