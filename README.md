# axiom-solver v0.2.0

Compiles the supported Axiom arithmetic/boolean fragment to SMT-LIB2. Unlike v0.1, postconditions are translated rather
than emitted as TODO comments. A production backend is expected to invoke Z3/cvc5 and validate or reconstruct solver
evidence.
