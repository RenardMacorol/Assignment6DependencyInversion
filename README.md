# Assignment6DependencyInversion

### Problem Statement 
The NEU Library offers a variety of resources, including books, theses, capstones, internet access, journals, and newspapers.

Currently, the Student object has methods like borrowBook(), borrowJournal() with a parameter of title, which directly depend on specific resource types.

To adhere to the Dependency Inversion Principle (DIP) and ensure flexibility for future changes (such as introducing audio books or e-journals), we need to refactor the program while maintaining SOLID principles. The goal is to create a robust system that can seamlessly accommodate new resource types in the future.

### UML Diagram Solution to the Problem

![uml](https://github.com/RenardMacorol/Assignment6DependencyInversion/assets/84180143/fe43184b-86e1-46ca-ac1a-4ce4703e83f8)

