# MeTTaIL GeTTing StartED

The purpose of this repository is to document my journey in getting
started with MeTTaIL.

## Starting Notes

My starting notes (taken during a call with Greg) are:

- MeTTaTron
- MeTTaIL: System F with context/hole (Plausible Fiction)
- Spatial Behavioral Types: MLab, claim
- Chess: coalition logic in the where clause

## F1r3node

MeTTaIL runs inside a
[f1r3node](https://github.com/F1R3FLY-io/f1r3node), thus it must be
installed first.

### Install f1r3node

Follow the instructions provided in the
[README.md](https://github.com/F1R3FLY-io/f1r3node/blob/rust/dev/README.md)
file of f1r3node.

## MeTTaTron

[MeTTaTron](https://github.com/F1R3FLY-io/MeTTa-Compiler) is a MeTTa
to MeTTaIL compiler.

### Install MeTTaTron

1. As of 2026/09/16 you need to check out the branch
   [feature/petta-semantics](https://github.com/F1R3FLY-io/MeTTa-Compiler/tree/feature/petta-semantics).
2. See
   [prerequisites](https://github.com/F1R3FLY-io/MeTTa-Compiler#prerequisites).
3. Then
   [compile](https://github.com/F1R3FLY-io/MeTTa-Compiler/blob/main/INSTALL.md#building-from-source).
   However you should use these branches instead for PathMap and MORK:
   ```
   git clone --branch feature/mettatron-fixes git@github.com:dylon/PathMap.git
   git clone --branch feature/arbitrary-space-value-types git@github.com:dylon/MORK.git
   git clone --branch master git@github.com:dylon/f1r3node-rust.git
   ```
