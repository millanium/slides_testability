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

## Value-Related Testability (1/2)

- oracle availability -> as much info as possible (analyzation basis for problem identification)
- oracle authority -> ones able to identify important problems
- oracle reliability -> trustworthy over time and in much conditions
- oracle precision -> as precise as (practically) possible
- oracle inexpensiveness -> little cost or effort to aquire or operate

oracle: anything which provides information relevant for testing (people, tools, documents, etc.)

+++

## Value-Related Testability (2/2)

- user stability & unity -> little user change and variety
- user familiarity -> much understanding gathered with users (testing by users)
- user availability -> talk with and observe users as much as possible
- user data availability -> as much user specific (use case) data
- user environment availability -> as natural/final environment as possible
- user environment stability & unity -> little user environment and environment changes

+++

## Subjective Testability

- product knowledge -> know a lot, learn with exploratory testing
- technical knowledge -> programming, technology, tools, sw development
- domain knowledge -> user involvement
- testing skill -> learn test patterns, system modeling, think critical
- engagement -> tight integrattion of testing (roles) into (agile) development process
- helpers -> much people considering about testing (even if not formally responsible)
- test strategy -> as well-designed as possible

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
