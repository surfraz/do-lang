# do-lang
The Do Programming Language

# concept
Do is a radical event-driven, distributed high-level programming language.

It is based around the concept of event-driven functions that can be scheduled across a cluster of compute nodes.

It does not have a type system, instead every object is responsible for handling its environment and signals.

Do, does not require the use of variables; data is instead handled by broker functions that are based around stream processing.

# example code
```aidl
  when ever:
    do:
      something
```