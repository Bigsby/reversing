# 01 - First Reversing

A simple C program.

## make commands
Make targets display running:
```
make help
```

## r2 Commands
Commands to run when in r2 prompt that looks something like this:
```
[0x00001050]>
```

### help
To view r2 help run:
```
?
```

### interesting commands
Show all file information (imports, exports, sections ...)
```
ia
```

Analyse all functions and name then
```
aaa
```

List functions
```
afl
```

Search and go to where 'main' function is
```
s main
```

Disassemble opcodes
```
pd
```

Pseudo disassemble output in C-like syntax, when in the function position (see s)
```
pdc
```

