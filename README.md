# Demo Compiler
A demo compiler written in ruby which generates JavaScript its not a fully fledged compiler it just process single expression

Resource: [https://www.destroyallsoftware.com/screencasts/catalog/a-compiler-from-scratch](https://www.destroyallsoftware.com/screencasts/catalog/a-compiler-from-scratch)
This tutorial is used to make this compiler/transpiler

This compiler works this way:

```mermaid
graph LR
A[Source Code] -- Transpile --> B((JS code))
A --> (Round Rect)
C --> D
```
It contains a `test.src` file where the only valid code is written
the code contains a function block exactly like this

```
def f (x,y)
  add(299, add(100, add(10, 5)))
end
```
and here you can add multiple add statement like this

```
def f (x,y)
  add(1222, add(299, add(100, add(10, 5))))
end
```

## How to run then 🤔

> Make sure you have ruby installed on your system ✌️

> `git clone https://github.com/nkroker/demo_compiler.git`

> `cd demo_compiler`

> `chmod +x compiler.rb`

> `ruby compiler.rb` or `./compiler.rb`


The main motive behind writing this compiler is just for learning purpose so that you can play along with it 😊
