# brainfuck
A simple [Brainfuck](1) interpreter written in Python.

## setup
No deps. Just python >= 2.7.9 is required.

## usage

Run as a command line tool

```shell

$ echo "++++++++[>++++[>++>+++>+++>+<<<<-]>+>+>->>+[<]<-]>>.>---.+++++++..+++.>>.<-.<.+++.------.--------.>>+.>++." | python brainfuck.py

```

Read a Brainfuck file

```shell

$ python brainfuck.py helloworld.bf

```

Use in another module

```python

from brainfuck import interpret

interpret("++++++++[>++++[>++>+++>+++>+<<<<-]>+>+>->>+[<]<-]>>.>---.+++++++..+++.>>.<-.<.+++.------.--------.>>+.>++.")

```

[1]: http://www.muppetlabs.com/~breadbox/bf/


