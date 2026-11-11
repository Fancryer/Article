# Diff Details

Date : 2026-11-01 09:36:25

Directory d:\\marran

Total : 50 files,  1859 codes, 421 comments, 261 blanks, all 2541 lines

[Summary](results.md) / [Details](details.md) / [Diff Summary](diff.md) / Diff Details

## Files
| filename | language | code | comment | blank | total |
| :--- | :--- | ---: | ---: | ---: | ---: |
| [CHANGELOG.md](/CHANGELOG.md) | Markdown | 7 | 0 | 5 | 12 |
| [Marran.cabal](/Marran.cabal) | Cabal | 128 | 3 | 7 | 138 |
| [README.md](/README.md) | Markdown | 10 | 0 | 5 | 15 |
| [Setup.hs](/Setup.hs) | Haskell | 2 | 0 | 1 | 3 |
| [app/Main.hs](/app/Main.hs) | Haskell | 62 | 7 | 4 | 73 |
| [app/guess.marr](/app/guess.marr) | Mårran | 26 | 0 | 5 | 31 |
| [app/infer.marr](/app/infer.marr) | Mårran | 1 | 0 | 0 | 1 |
| [app/main.marr](/app/main.marr) | Mårran | 28 | 0 | 4 | 32 |
| [app/main\_ec.marr](/app/main_ec.marr) | Mårran | 1 | 0 | 0 | 1 |
| [app/main\_el.marr](/app/main_el.marr) | Mårran | 4 | 0 | 0 | 4 |
| [app/main\_ic.marr](/app/main_ic.marr) | Mårran | 2 | 0 | 0 | 2 |
| [app/marr/README.md](/app/marr/README.md) | Markdown | 15 | 0 | 3 | 18 |
| [app/marr/compare.marr](/app/marr/compare.marr) | Mårran | 1 | 7 | 0 | 8 |
| [app/marr/counter.marr](/app/marr/counter.marr) | Mårran | 1 | 8 | 0 | 9 |
| [app/marr/gene.marr](/app/marr/gene.marr) | Mårran | 4 | 0 | 0 | 4 |
| [app/marr/handle\_while.marr](/app/marr/handle_while.marr) | Mårran | 34 | 0 | 5 | 39 |
| [app/marr/imm\_make.marr](/app/marr/imm_make.marr) | Mårran | 1 | 8 | 0 | 9 |
| [app/marr/imm\_needs\_read.marr](/app/marr/imm_needs_read.marr) | Mårran | 1 | 10 | 0 | 11 |
| [app/marr/imm\_recursion.marr](/app/marr/imm_recursion.marr) | Mårran | 1 | 7 | 0 | 8 |
| [app/marr/imm\_snapshot.marr](/app/marr/imm_snapshot.marr) | Mårran | 1 | 6 | 0 | 7 |
| [app/marr/param\_reentrancy.marr](/app/marr/param_reentrancy.marr) | Mårran | 1 | 6 | 0 | 7 |
| [app/marr/random\_range.marr](/app/marr/random_range.marr) | Mårran | 1 | 4 | 0 | 5 |
| [app/marr/rebind\_shared.marr](/app/marr/rebind_shared.marr) | Mårran | 1 | 7 | 0 | 8 |
| [app/marr/row\_poly.marr](/app/marr/row_poly.marr) | Mårran | 1 | 10 | 0 | 11 |
| [app/marr/scoping.marr](/app/marr/scoping.marr) | Mårran | 1 | 9 | 0 | 10 |
| [app/marr/under.marr](/app/marr/under.marr) | Mårran | 1 | 19 | 0 | 20 |
| [app/modules.marr](/app/modules.marr) | Mårran | 11 | 35 | 2 | 48 |
| [app/std.marr](/app/std.marr) | Mårran | 26 | 148 | 1 | 175 |
| [dist-newstyle/cache/plan.json](/dist-newstyle/cache/plan.json) | JSON | 1 | 0 | 0 | 1 |
| [hie.yaml](/hie.yaml) | YAML | 2 | 0 | 0 | 2 |
| [package.yaml](/package.yaml) | YAML | 83 | 6 | 8 | 97 |
| [prover/marr/.github/workflows/lean\_action\_ci.yml](/prover/marr/.github/workflows/lean_action_ci.yml) | YAML | 11 | 0 | 4 | 15 |
| [prover/marr/Main.lean](/prover/marr/Main.lean) | lean4 | 3 | 0 | 2 | 5 |
| [prover/marr/Marr.lean](/prover/marr/Marr.lean) | lean4 | 1 | 2 | 1 | 4 |
| [prover/marr/Marr/Basic.lean](/prover/marr/Marr/Basic.lean) | lean4 | 1 | 0 | 1 | 2 |
| [prover/marr/README.md](/prover/marr/README.md) | Markdown | 1 | 0 | 0 | 1 |
| [prover/marr/lake-manifest.json](/prover/marr/lake-manifest.json) | JSON | 6 | 0 | 1 | 7 |
| [prover/marr/lakefile.toml](/prover/marr/lakefile.toml) | TOML | 8 | 0 | 3 | 11 |
| [src/Debug.hs](/src/Debug.hs) | Haskell | -3 | -55 | -3 | -61 |
| [src/Infer.hs](/src/Infer.hs) | Haskell | 172 | 45 | 43 | 260 |
| [src/Interpreter.hs](/src/Interpreter.hs) | Haskell | 191 | 37 | 15 | 243 |
| [src/Scope.hs](/src/Scope.hs) | Haskell | 18 | 3 | 3 | 24 |
| [src/TypedIR.hs](/src/TypedIR.hs) | Haskell | 2 | -2 | 0 | 0 |
| [src/Types.hs](/src/Types.hs) | Haskell | -3 | -2 | 1 | -4 |
| [src/Unify.hs](/src/Unify.hs) | Haskell | 23 | -3 | 10 | 30 |
| [stack.yaml](/stack.yaml) | YAML | 4 | 63 | 5 | 72 |
| [stack.yaml.lock](/stack.yaml.lock) | YAML | 7 | 4 | 2 | 13 |
| [test/Spec.hs](/test/Spec.hs) | Haskell | 5 | 0 | 2 | 7 |
| [test/UnifySpec.hs](/test/UnifySpec.hs) | Haskell | 941 | 29 | 121 | 1,091 |
| [todo.md](/todo.md) | Markdown | 12 | 0 | 0 | 12 |

[Summary](results.md) / [Details](details.md) / [Diff Summary](diff.md) / Diff Details