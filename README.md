# LINQ PRACTICES AND GOOD-BAD CODE EXAMPLE

This repository contains a C# console application showcasing good and bad coding practices, emphasizing SOLID principles. The project is divided into two parts:

1. **LINQ Practice Code:**
   - File: `LinqPractice.cs`
   - This section explores LINQ queries applied to a collection of books. It demonstrates various LINQ operations such as filtering, ordering, projecting, and grouping.

2. **HowToNotCode Project:**
   - Files: `BookRepository.cs`, `BookService.cs`
   - In this part, we present a simple book management system. It includes a book repository, book service, and an exception handler. The focus here is to provide examples of both bad and good coding practices, allowing developers to compare and understand the principles.

## LINQ PracticeS

### Overview
Explore LINQ queries applied to a collection of books. The examples cover different scenarios, showcasing the power and flexibility of LINQ in querying and manipulating data.

### Running LINQ Practice Code
1. Open `LinqPractice.cs` in your preferred C# development environment (e.g., Visual Studio).
2. Build and run the application.

## HowToNotCode

### Project Overview
The HowToNotCode Project is designed to demonstrate both good and bad coding practices within a book management system. The components include:

- `BookRepository.cs`: Implements the book repository.
- `BookService.cs`: Implements the book service with good and bad coding examples.
- `ExceptionHandler.cs`: Provides a centralized approach to exception handling.
- `Book.cs`: Defines the Book class.

### Features
1. **Dependency Inversion Principle (DIP):**
   - `BookService` utilizes the DIP by injecting an interface (`IBookRepository`) for the `bookRepository` dependency.

2. **Single Responsibility Principle (SRP):**
   - Methods in `BookService` adhere to SRP, handling specific tasks such as adding, updating, deleting books, and viewing books and authors.

3. **Clean Error Handling:**
   - The code demonstrates clean error handling practices, providing informative messages for invalid input.

### HowToNotCode Examples
The `BookService` class includes both good and bad examples, allowing developers to compare and understand the impact of applying SOLID principles.
