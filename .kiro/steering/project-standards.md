# BetterUtilities Project Standards

## Project Overview
- **Name**: BetterUtilities
- **Namespace**: BetterUtilities
- **Target Frameworks**: .NET 6.0, 7.0, 8.0 (backwards compatible)
- **Type**: NuGet Library Package

## Code Standards
- Use C# nullable reference types
- Follow Microsoft C# coding conventions
- Use XML documentation comments for all public APIs
- Implement proper error handling and validation
- Write unit tests for all public methods
- Use meaningful names for classes, methods, and variables

## Project Structure
- Keep utility classes organized by functionality
- Use static classes for utility methods where appropriate
- Implement extension methods in separate static classes
- Follow single responsibility principle

## NuGet Package Guidelines
- Increment version following semantic versioning
- Update package description and release notes
- Ensure backwards compatibility within major versions
- Test against all target frameworks before release