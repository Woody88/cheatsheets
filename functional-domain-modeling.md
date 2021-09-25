---
title: Functional Domain Modeling
category: Domain Driven Design
layout: 2017/sheet
---

### What is an Algebra?

Algebra is the study of algebraic structures.

An Algebraic structure is a **set** (called _carrier set_ or _underlying set_)
with one or more finite operations defined on it which statisfies a list of rules/laws.

In the context of domain modeling a **set** will be a set of data types.

### Algebras Characteristic

For every algebra we have:

- A carrier type of the algebra
- Introductions Forms
- Combinators
- Elminators Forms
- Laws

### Algebraic Thinking

- Algebra scales from that of one single data type to an entire bounded context
- Algebras compose enabling composition of domain behaviours
- Algebras let you focus on the compositionality without any context of implementation
- Statically typed functional programming is programming with algebras

### Denotation Semantics

Takeaways:

- Our thought process should independent of the implementation. Understanding programs through independent implementation semantics tends to be more intuitive in understanding a program
- When thinking in terms of implementation, exact mode of execution, it because difficult to keep the entire concept in mind. However, thinking in terms of the operation, algebra, rules, makes it easier
- Detonational thinking leads to Alegbraic Thinking

## References

- [Algebraic Structure](https://en.wikipedia.org/wiki/Algebraic_structure) _(wikipedia.org)_
- [Denotational Semantics](https://en.wikipedia.org/wiki/Denotational_semantics) _(wikipedia.org)_
