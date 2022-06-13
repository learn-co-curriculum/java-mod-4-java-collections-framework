# Java Collections Framework

## Learning Goals

- Explain what is meant by data structures.
- Give an overview of the collections framework in Java.

## What are Data Structures?

At its core, programming is all about representing and manipulating data. Data
structures define how we represent data and algorithms define how we manipulate
them.

Data structures describe how data should be stored, arranged, and accessed. We
have to pick the right data structure depending on the problem at hand. For
example, if we need to assign priority to our data we could use a priority
queue.

Java provides us with several implementations of the most common data
structures. We’ll learn about the most common ones in the following lessons.

## What are Collections?

Collections are representations of different data structures and abstract data
types. All modern collections we’ll be using are generic, i.e., we can specify
any reference type as a generic parameter and store it in the collection. But
note that collections **do not** allow primitive values, so instead of using
primitives like `int`, `double`, `char`, we have to use `Integer`, `Double`,
`Character`.

## What is the Collections Framework?

Java organizes collections using a clear hierarchy. The framework contains
interfaces, abstract classes, concrete classes (the data structure
implementation) which incorporate unique algorithms. There are two main
interfaces: `Collection` and `Map`.

The `Collection` interface is used by data structures or collections that
contain a list of elements of the same type.

![List Interface Diagram](https://curriculum-content.s3.amazonaws.com/java-mod-4/List-Interface-Diagram.png)

The `Map` interface is used by collections that store a pair of values.

![Map Interface Diagram](https://curriculum-content.s3.amazonaws.com/java-mod-4/Map-Interface-Diagram.png)

These collections have a clear hierarchy, well-defined APIs, and
high-performance which drastically reduces programming overhead, increases
program speed, makes it easier to interoperate across systems, and makes it easy
to learn new APIs based on this structure.

In the next few lessons, we will discuss both the `Collection` and `Map`
interfaces along with most of the concrete classes shown in the diagrams.

## Conclusion

We'll take a deeper look at both of these interfaces in the coming sections.
You'll be using these interfaces quite frequently when working on applications.
