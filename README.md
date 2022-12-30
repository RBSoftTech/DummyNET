# DummyNET
DummyNET is a project to make generating dummy data easy. It consists of a suite of engines to create dummy data.

## Getting started with DummyNET

You can create dummy data using three objects
- Dummy engine
- Sequence
- Sequence options

### Dummy Engine

Dummy engine allows you to create sequences of dummy values. An engine can manage more sequences. Each sequence is uniquely identify by its name.

### Sequence

A sequence is a set of values. You can change the behavior of a sequence using sequence options. A sequence can have four different behaviors:
- Random : engine creates values in random mode. The sequence can contain the same value more than once
- Random unique : engine creates values in random mode. The sequence can contain the same value only once 
- Random constant : engine creates a random value and it repeats always the same value
- Defined constant : you can choise a specific value. Engine repeats the constant value.

### Sequence options

Sequence's options allow you 
- to change the behavior of a sequence
- to choise the name of a sequence
- to choise a constant value (used for defined constant behavior only)

## DummyNET packages

DummyNET project includes some packages :
- [DummyNET.Core](https://www.nuget.org/packages/RBSoftTech.DummyNET.Core) : it is a core library. It contains interfaces and base implementations
- [DummyNET.Boolean](https://www.nuget.org/packages/RBSoftTech.DummyNET.Boolean) : it contains implementations to create sequences of boolean values
