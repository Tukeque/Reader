# Reader
A python library that has a Lexer and a Tuk Parser

# Usage
## Lexer
```
separators = ["+", "-", "/", "//", "*", "%", "^", "&", "|", "=", "==", ">=", "<=", "!=", ">", "<", "->", "{", "}", ",", "(", ")", ";", "[", "]", " "]
lexer = Lexer(
    separators, # separators
    [] # style (will be implemented later for syntax checking)
) # other settings are self explanatory in the constructor

tokens = lexer.lex(code) # takes a list of strings (remember to remove trailing new lines)
```

## Parser (ONLY for Tuk Syntax)
```
parser = Parser(tokens) # tokens from lexer
exprs = parser.parse()
```

# Contributing
Its simple, You dont
