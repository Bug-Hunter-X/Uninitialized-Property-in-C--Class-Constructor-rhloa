# Uninitialized Property in C# Class Constructor

This repository demonstrates a common but often overlooked issue in C#: uninitialized properties in class constructors.  While C# provides default values for various types, relying solely on these defaults can lead to unexpected behavior if your application requires a specific initial state.

The `Bug.cs` file shows an example where the `MyProperty` is not explicitly initialized in the constructor. While the property defaults to 0, this might not always be the desired behavior. 

The `BugSolution.cs` file presents a corrected version explicitly setting the property to ensure the desired initial value.