# Testability

---

## What means Testability

Testability is a system/software quality attribute which describes if the system/software is testable and
if so how easy it is testable.

---

## Classification of Testability

- epidemistic ("Testability influenced by the knowledge gap between what we know and what we should know about the product.")
- project-related ("Testability influenced by changing conditions under which we test.")
- value-related ("Testability influenced by changing the quality standard or our knowledge of it.")
- subjective ("Testability influenced by changing the tester or the test process.")
- intrinsic ("Testability influenced by changing the product itself.")

(Bach, 2015)

+++

## Epidemistic Testability

- prior knowledge of quality -> much knowledge
- tolerance of failure -> little quality required or high risk tolerated

+++

## Project-Related Testability

- change control -> infrequent and controlled
- information availability -> complete and explicit 
- testware availability -> all relevant configurations
- system under test availability -> all relevant versions
- sandboxing or redundance -> disruptive testing
- test environment controllability -> all relevant configuration parameters
- time -> enough for most critical tests

+++

## Value-Related Testability

+++

## Subjective Testability

+++

## Intrinsic Testability

- observability -> any state or behaviour in any point "get-able" (direct and indirect inputs)
- controllability -> any state or behaviour in any point "set-able" (direct and indirect outputs)
- algorithmic simplicity -> easy correlation between inputs and outputs
- conditional simplicity -> little paths
- unbugginess -> little bugs
- smallness -> little extend and interaction
- decomposability -> "detachable" system components
- similarity -> reuse known and trusted technologies

---

## Test Unsupported Refactoring to Testability Patterns

Patterns which can be applied to enable changing the design of untestable production code
which has no tests without changing its behaviour and without introducing regression bugs
with the aim of making it testable.

---

## Classification of Test Unsupported Refactoring to Testability Patterns

- psychological (based on psychological effects)
- mechanistic (based on mechanism)

+++

## Psychological Test Unsupported Refactoring to Testability Patterns

- Hyperaware Editing (Feathers 2011, p. 319)
- Single-Goal Editing (Feathers 2011, p. 321)
- Pair Programming (Feathers 2011, p. 327)

+++

## Mechanistic Test Unsupported Refactoring to Testability Patterns

- Preserve Signature (Feathers 2011, p. 322)
- Lean on the Compiler (Feathers 2011, p. 325)

---

## References

- Bach, James: *Heuristics of Software Testability*, http://satisfice.com/tools/testability.pdf, Version 2.3, 2015
- Feathers, Michael C.: *Effektives Arbeiten mit Legacy Code*, 1st edition, 2011
