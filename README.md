# Runescript
Scripting language for drawing 2D graphics

## Commands

| Command | Description    | Arguments |
| ------- | -------        | ---- |
| **G**   |  Create grid context for nested commands  |
| **P**   | Absolute point  |
| **+** | Relative point |
| **A** | Arc |
| **C** | Corner |
| **T** | Tangent |

## Tokens

| Token | Description |
| -- | -- |
| **w** | Width |
| **h** | Height |
| ***n*u** | n grid units eg. 4u |
| **hpi, pi, *n*pi**| Half pi, pi & npi eg. 2pi |
| **sr,gr** | Ratios: Silver ratio `sqrt(2)`, Golden Ratio - `(1 + sqrt(5)) / 2`


## example.rs
```
G6 6 30 5
  P0 0,+w 0,0 6u,-w 0,0 0
```
