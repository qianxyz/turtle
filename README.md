# Turtle Graphics

## Language

### BNF

#### Program

```
<program> ::= <statement>*
```

#### Statements

```
<statement> ::= <procedure-definition>
              | <procedure-call>
              | if <test-expr> <block>
              | repeat <count-expr> <block>
<block> ::= [ <statement>* ]
```

#### Procedures

```
<procedure-definition> ::= to <identifier> <parameter>* <statement>* end
<procedure-call> ::= <identifier> <arg-expr>*
<parameter> ::= :<identifier>
```

#### Expressions

```
<expression> ::= <number>
               | <parameter>
               | <expression> <operator> <expression>
<operator> ::= + | - | * | / | < | > | =
```

### Built-in Procedures

- forward / fd / back / bk *distance*
- left / lt / right / rt *angle*
- clearscreen / cs
- penup / pu / pendown / pd

## References

- [Logo in Racket](https://docs.racket-lang.org/logo/index.html)
- [Logo Interpreter](https://www.calormen.com/jslogo/)
