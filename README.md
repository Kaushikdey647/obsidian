# OBSIDIAN
## yes it does sound awesome!

## Key Components
- **Lexer**:
    - `bas.l`: The flex file that defines the tokens and the rules for the lexer.
    - `y.tab.h`: The header file generated by yacc that contains the tokens.

## How to use

### Requirements
- `flex`
- `yacc`
- `gcc`

### Build
```bash
make all
```

### Run
```bash
./src/bas <path-to-file>
```

## Clean
```bash
make clean
```
