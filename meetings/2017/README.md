# C# Language Design Notes for 2017

Overview of meetings and agendas for 2017

## Jan 10, 2017

[C# Language Design Notes for Jan 10, 2017](LDM-2017-01-10.md)

1. Discriminated unions via "closed" types

## Jan 11, 2017

[C# Language Design Notes for Jan 11, 2017](LDM-2017-01-11.md)

1. Language aspects of [compiler intrinsics](https://github.com/dotnet/roslyn/issues/11475)

## Jan 17, 2017

[C# Language Design Notes for Jan 17, 2017](LDM-2017-01-17.md)

1. Constant pattern semantics: which equality exactly?
2. Extension methods on tuples: should tuple conversions apply?


## Jan 18, 2017

[C# Language Design Notes for Jan 18, 2017](LDM-2017-01-18.md)

1. Async streams (visit from Oren Novotny)

## Feb 21, 2017

[C# Language Design Notes for Feb 21, 2017](LDM-2017-02-21.md)

We triaged some of the [championed features](https://github.com/dotnet/csharplang/issues?q=is%3Aopen+is%3Aissue+label%3A%22Proposal+champion%22), to give them a tentative milestone and ensure they had a champion.

As part of this we revisited potential 7.1 features and pushed several out.

1. Implicit interface implementation in Visual Basic *(VB 16)*
2. Delegate and enum constraints *(C# X.X)*
3. Generic attributes *(C# X.0 if even practical)*
4. Replace/original *(C# X.0 if and when relevant)*
5. Bestest betterness *(C# 7.X)*
6. Null-coalescing assignments and awaits *(C# 7.X)*
7. Deconstruction in from and let clauses *(C# 7.X)*
8. Target-typed `new` expressions *(C# 7.X)*
9. Mixing fresh and existing variables in deconstruction *(C# 7.1)*
10. Implementing `==` and `!=` on tuple types *(C# 7.X)*
11. Declarations in embedded statements *(No)*
12. Field targeted attributes on auto-properties *(C# 7.1)*

## Feb 22, 2017

[C# Language Design Notes for Feb 22, 2017](LDM-2017-02-22.md)

We went over the proposal for `ref readonly`: [Champion "Readonly ref"](https://github.com/dotnet/csharplang/issues/38).

## Feb 28, 2017

[C# Language Design Notes for Feb 28, 2017](LDM-2017-02-28.md)

1. Conditional operator over refs (*Yes, but no decision on syntax*)
2. Async Main (*Allow Task-returning Main methods*)

## Mar 1, 2017
[C# Language Design Notes for Mar 1, 2017](LDM-2017-03-01.md)

1. Shapes and extensions (*exploration*)
2. Conditional refs (*original design adopted*)

## Mar 7, 2017
[C# Language Design Notes for Mar 7, 2017](LDM-2017-03-07.md)

We continued to flesh out the designs for features currently considered for C# 7.1.

1. Default expressions (*design adopted*)
2. Field target on auto-properties (*yes*)
3. private protected (*yes, if things work as expected*)

## Mar 8, 2017
[C# Language Design Notes for Mar 8, 2017](LDM-2017-03-08.md)

We looked at default interface member implementations.

1. Xamarin interop scenario
2. Proposal
3. Inheritance from interface to class
4. Overriding and base calls
5. The diamond problem
6. Binary compatibility
7. Other semantic challenges

## Mar 15, 2017
[C# Language Design Notes for Mar 8, 2017](LDM-2017-03-15.md)

Triage of championed features

1. JSON literals
2. Fixing of captured locals
3. Allow shadowing of parameters
4. Weak delegates
5. Protocols/duck typing/concepts/type classes
6. Zero and one element tuples
7. Deconstruction in lambda parameters
8. Private protected