# axiom-solver

The first solver backend. It evaluates Axiom postconditions over a finite integer domain and can emit an SMT-LIB
skeleton for migration to Z3/cvc5.

> **Maturity:** research prototype v0.1. The default verifier proves properties by exhaustive evaluation over an
> explicitly finite input domain. A VALID receipt is therefore a theorem about that bounded model, not a claim of
> unbounded program correctness.


Supported clauses in v0.1 include comparisons against `result`, `x`, `-x`, integer constants, conjunction (`&&`) and
disjunction (`||`).

```bash
cargo run -- eval spec.aix --x -7 --result 7
cargo run -- smt spec.aix
```
