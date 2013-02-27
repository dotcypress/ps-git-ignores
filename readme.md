# GitIgnore generator for PowerShell

Module for creating .gitignore files via GitHub template

## Installation

### Manual

Download [GitIgnores.psm1](https://raw.github.com/dotCypress/ps-git-ignores/master/AddDefaultIgnoreFiles.psm1) and run `Import-Module GitIgnores.psm1`
<!--
### PSGet

1. Install [psget](http://psget.net/)
2. Run `Install-Module ps-git-ignores`
 -->

## Commands

### Get-GitIgnore

Displays list of supported templates.

#### Usage

```bash
Get-GitIgnore [[-Template] <String>]
```

#### Examples

```bash
Get-GitIgnore
```

```bash
Get-GitIgnore Ocaml
```

### Add-GitIgnore

Adds requested .gitignore to current directory.

#### Usage

```bash
Add-GitIgnore [-Template] <String>
```

#### Examples

```bash
Add-GitIgnore CSharp
```

## Integration

[PowerTab](http://powertab.codeplex.com/) intergation is included.

![GitIgnore generator with PowerTab](https://raw.github.com/dotCypress/ps-git-ignores/master/docs/PowerTab.PNG)

## License

[BSD license](http://opensource.org/licenses/bsd-license.php)