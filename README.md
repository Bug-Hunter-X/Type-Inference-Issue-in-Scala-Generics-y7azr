# Type Inference Issue in Scala Generics

This repository demonstrates a type inference issue that can occur in Scala when using generics.  The issue arises in specific situations where the compiler struggles to infer the type parameter `T` accurately. The provided example showcases a simple class with a generic type parameter and its application in a main method. The issue is subtle and can be difficult to detect without careful analysis of the code. The solution involves explicitly specifying the type parameter `T` in specific cases to guide the compiler's type inference process.

## How to Reproduce

1. Clone this repository.
2. Open the `MyClass.scala` file.
3. Compile and run the code using a Scala compiler (e.g., `scalac MyClass.scala` and `scala Main`).
4. Observe the error encountered, demonstrating the type inference issue.

## Solution

The solution is detailed in the `MyClassSolution.scala` file.  The solution involves explicitly specifying the type parameter `T` during instantiation in certain complex scenarios to ensure proper type inference.