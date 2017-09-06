# diplomaThesis
My diploma thesis titled Operational calculus on programming spaces

## Abstract

In this work we develop an algebraic language that represents a formal calculus for deep learning and is, at the same time a model which enables implementations and investigations of programs.

To this purpose, we develop an _abstract computational model of automatically differentiable programs_. In the model, programs are elements of op. cit. _programming spaces_. Programs are viewed as maps from a finite-dimensional vector space to itself op. cit. _virtual memory space_. Virtual memory space is an algebra of programs, _an algebraic data structure_ (one can calculate with). The elements of the virtual memory space give the expansion of a program into an infinite tensor series. We define a _differential operator_ on programming spaces and, using its powers, implement the _general shift operator_ and the _operator of program composition_.

The algebraic language constructed in this way is a complete model of deep learning. It enables us to express programs in such a way, that their properties may be derived from their source codes.