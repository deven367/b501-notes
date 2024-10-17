# Turing Machines

> This doc contains some overall notes on Traces and Turing machines.

## Turing Machine

* Turing Machines can broadly be classified into two types, the Acceptors and the Transducers.
* Acceptor Turing Machine is an automaton used to define Turing-acceptable languages.
* Such a machine can be used to check whether a given string belongs to a language or not. It is defined as a 7-tuple machine.

A read-only Turing machine is a 2DFA. They are a class of models of computability that behave like a standard Turing machine and can move in both directions across input, except cannot write to its input tape.

## Turing Transducers

* Transducers are the devices used to convert one form of signal into another. The same can be told about Turing Machine Transducers.
* A transducer is a type of Turing Machine that is used to convert the given input into the output after the machine performs various read-writes. It doesn’t accept or reject an input but performs series of operations to obtain the output right in the same tape and halts when finished.
