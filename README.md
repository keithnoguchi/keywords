# Language Keywords and Basic Data Types

- [Keywords](#keywords)
- [Basic Data Types](#basic-data-types)
- [Operators](#operators)
- [Built-in Functions](#built-in-functions-operators)

## Keywords

| Keywords  | c | go | js | rs |
|:----------|:-:|:--:|:--:|:--:|
|as         |   |    |    |  x |
|async      |   |    |    |  x |
|auto       | x |    |    |    |
|await      |   |    |    |  x |
|break      | x |  x |  x |  x |
|case       | x |  x |  x |    |
|catch      |   |    |  x |    |
|chan       |   |  x |    |    |
|class      |   |    |  x |    |
|const      | x |  x |  x |  x |
|continue   | x |  x |  x |  x |
|crate      |   |    |    |  x |
|debugger   |   |    |  x |    |
|default    | x |  x |  x |    |
|delete     |   |    |  x |    |
|defer      |   |  x |    |    |
|do         | x |    |  x |    |
|dyn        |   |    |    |  x |
|else       | x |  x |  x |  x |
|enum       | x |  x |    |  x |
|export     |   |    |  x |    |
|extends    |   |    |  x |    |
|extern     | x |    |    |  x |
|fallthrough|   |  x |    |    |
|false      | x |  x |  x |  x |
|float      | x |    |    |    |
|finally    |   |    |  x |    |
|fn         |   |    |    |  x |
|for        | x |  x |  x |  x |
|func       |   |  x |    |    |
|function   |   |    |  x |    |
|go         |   |  x |    |    |
|goto       | x |  x |    |    |
|if         | x |  x |  x |  x |
|inline     | x |    |    |    |
|impl       |   |    |    |  x |
|implements |   |    |  x |    |
|import     |   |  x |  x |    |
|interface  |   |  x |  x |    |
|in         |   |    |  x |  x |
|instanceof |   |    |  x |    |
|let        |   |    |  x |  x |
|loop       |   |    |    |  x |
|new        |   |    |  x |    |
|map        |   |  x |    |    |
|match      |   |    |    |  x |
|mod        |   |    |    |  x |
|move       |   |    |    |  x |
|mut        |   |    |    |  x |
|package    |   |  x |  x |    |
|private    |   |    |  x |    |
|protected  |   |    |  x |    |
|pub        |   |    |    |  x |
|public     |   |    |  x |    |
|range      |   |  x |    |    |
|ref        |   |    |    |  x |
|return     | x |  x |  x |  x |
|select     |   |  x |    |    |
|self       |   |    |    |  x |
|static     | x |    |  x |  x |
|struct     | x |  x |    |  x |
|super      |   |    |  x |  x |
|switch     | x |  x |  x |    |
|this       |   |    |  x |    |
|throw      |   |    |  x |    |
|trait      |   |    |    |  x |
|true       | x |  x |  x |  x |
|try        |   |    |  x |    |
|type       |   |  x |    |  x |
|typeof     | x |    |  x |    |
|union      | x |    |    |  x |
|unsafe     |   |    |    |  x |
|use        |   |    |    |  x |
|var        |   |  x |  x |    |
|volatile   | x |    |    |    |
|where      |   |    |    |  x |
|while      | x |    |  x |  x |
|with       |   |    |  x |    |
|yield      |   |    |  x |    |

| Keywords  | c | go | js | rs |
|:---------:|--:|---:|---:|---:|
|total      | 25| 26 | 42 | 38 |

## Basic Data Types

| Types    | c | go | js | rs |
|:---------|:-:|:--:|:--:|:--:|
|bool      | x |  x |  x |  x |
|byte      |   |  x |    |    |
|char      | x |    |    |    |
|complex64 |   |  x |    |    |
|complex128|   |  x |    |    |
|double    | x |    |    |    |
|error     |   |  x |    |    |
|f32       |   |    |    |  x |
|f64       |   |    |    |  x |
|float     | x |    |    |    |
|float32   |   |  x |    |    |
|float64   |   |  x |    |    |
|i8        |   |    |    |  x |
|i16       |   |    |    |  x |
|i32       |   |    |    |  x |
|i64       |   |    |    |  x |
|i128      |   |    |    |  x |
|int       | x |  x |    |    |
|int8      |   |  x |    |    |
|int16     |   |  x |    |    |
|int32     |   |  x |    |    |
|int64     |   |  x |    |    |
|iota      |   |  x |    |    |
|isize     |   |    |    |  x |
|long      | x |    |    |    |
|nil       |   |  x |    |    |
|null      |   |    |  x |    |
|rune      |   |  x |    |    |
|short     | x |    |    |    |
|string    |   |  x |    |    |
|u8        |   |    |    |  x |
|u16       |   |    |    |  x |
|u32       |   |    |    |  x |
|u64       |   |    |    |  x |
|u128      |   |    |    |  x |
|uint      |   |  x |    |    |
|uint8     |   |  x |    |    |
|uint16    |   |  x |    |    |
|uint32    |   |  x |    |    |
|uint64    |   |  x |    |    |
|uintptr   |   |  x |    |    |
|usize     |   |    |    |  x |
|undefined |   |    |  x |    |
|unsigned  | x |    |    |    |
|void      | x |    |    |    |

|Types     | c | go | js | rs |
|:--------:|--:|---:|---:|---:|
|total     | 9 | 24 |  3 | 14 |

## Operators

|Operators| c | go | js | rs |
|:--------|:-:|:--:|:--:|:--:|
|`++`     | x |  x |  x |    |
|`--`     | x |  x |  x |    |
|`*`      | x |  x |  x |  x |
|`/`      | x |  x |  x |  x |
|`%`      | x |  x |  x |  x |
|`<<`     | x |  x |  x |  x |
|`>>`     | x |  x |  x |  x |
|`&`      | x |  x |  x |  x |
|`&^`     |   |  x |    |    |
|`+`      | x |  x |  x |  x |
|`-`      | x |  x |  x |  x |
|`\|`     | x |  x |  x |  x |
|`^`      | x |  x |  x |  x |
|`==`     | x |  x |  x |  x |
|`===`    |   |    |  x |    |
|`!=`     | x |  x |  x |  x |
|`!==`    |   |    |  x |    |
|`<`      | x |  x |  x |  x |
|`<=`     | x |  x |  x |  x |
|`>`      | x |  x |  x |  x |
|`>=`     | x |  x |  x |  x |
|`\|\|`   | x |  x |  x |  x |
|`&&`     | x |  x |  x |  x |

|Operators| c | go | js | rs |
|:-------:|--:|---:|---:|---:|
|total    | 20| 21 | 22 | 18 |

## Built-in Functions/Operators

|Functions| c | go | js | rs |
|:--------|:-:|:--:|:--:|:--:|
|append   |   |  x |    |    |
|cap      |   |  x |    |    |
|close    |   |  x |  x |    |
|complex  |   |  x |    |    |
|copy     |   |  x |    |    |
|delete   |   |  x |  x |    |
|imag     |   |  x |    |    |
|in       |   |    |  x |    |
|len      |   |  x |    |    |
|make     |   |  x |    |    |
|new      |   |  x |    |    |
|panic    |   |  x |    |    |
|real     |   |  x |    |    |
|recover  |   |  x |    |    |

|Functions| c | go | js | rs |
|:-------:|--:|---:|---:|---:|
|total    | - | 13 |  - |  - |
