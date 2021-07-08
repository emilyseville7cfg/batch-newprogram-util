# newprogram

## Description

Simple program generator for C# and PascalABC.NET.

## Requirements

Supported environments: Windows 10 and Wine 5.0.

Command line utils pre-installed:

- [sed](http://gnuwin32.sourceforge.net/packages/sed.htm)

## Syntax

```bat
newprogram [options]
```

## Options

- `-h`|`--help` - writes help and exits
- `-v`|`--version` - writes version and exits
- `-l`|`--language` - specifies language name [Available value set is: csharp, pascal.]
- `-p`|`--path` - specifies program path

## Error codes

- `0` - Success
- `2` - Unexpected language name. Valid language name set is: csharp, pascal.

## Examples

```bat
newprogram --help
```

```bat
newprogram --language csharp
```