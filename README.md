# swiftbolt
Type Swift code and see the output in real time. Inspired by [Compiler Explorer](http://godbolt.org). Unfortunately Compiler Explorer only supports code execution for C++.

# Example

Type
```
$ cd path/to/swiftbolt
$ ./run
```
and then edit `Sources/swiftbolt/main.swift`. The output of `main.swift` is displayed and periodically refreshed.

![](example.gif)

# Other kinds of output

| Command  | Output                                          |
|----------|-------------------------------------------------|
| `./run`  | Execute program.                                |
| `./ast`  | Generate the abstract syntax tree.              |
| `./ir`   | Generate llvm ir.                               |
| `./oir`  | Generate optimized llvm ir.                     |
| `./sil`  | Generate Swift intermediate language.           |
| `./osil` | Generate optimized Swift intermediate language. |
