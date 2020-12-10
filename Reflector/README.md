# Reflector

The goal of this exercise is to implement a simple p4 program that makes switches bounce back packets to the interface the packets came from. It will also show you how to create simple topologies with hosts and p4 switches and how to add links between them.

The base **p4app.json**, **reflector.p4** and **send_receive.py** are provided.  

Use:

* **p4app.json** to define your topology;

* **reflector.p4** to define your p4 program;

* **send_receive.py** to test your program in Mininet.

## To run your program

```c
  sudo p4run
```