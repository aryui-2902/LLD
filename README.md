# LLD

Low-Level Design / machine-coding interview prep in Python.

## Contents

- **`OOPS/`** — core OOP concepts: classes/objects, encapsulation, abstraction, inheritance, abstract base classes, composition over inheritance, Liskov substitution.
- **`SOLID/`** — bad vs. good examples for each SOLID principle (SRP, OCP, LSP, ISP, DIP).
- **`UML/`** — class-relationship examples (association, aggregation, composition, dependency, inheritance) with diagrams.
- **`playground/`** — 33 interview-style LLD problems (9 easy, 16 medium, 8 hard), each with a prompt (`README.md`), an interface `contract.py`, a `solution.py`, and runnable `unittest` tests. See [`playground/README.md`](playground/README.md) for the catalog and practice guide.

## Running

Requires Python 3 (standard library only).

```bash
# Run an example
python3 OOPS/inheritance.py

# Run all playground problem tests
cd playground && ./run_tests.sh

# Run tests for a single problem
./run_tests.sh parking_lot
```
