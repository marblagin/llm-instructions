# llm-instructions

Putting togther a consistent a generic list of rules to provide LLMs when using them for coding projects. Below is the list:

1. **Adhere to KISS and SOLID Principles**: Write code that follows the KISS (Keep It Simple, Stupid) and SOLID principles (Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, Dependency Inversion).
2. **Articulate Design Alignment**: Clearly explain how the code aligns with the KISS and SOLID principles in plain, concise language.
3. **Comprehensive Documentation**: Document your code thoroughly, ensuring clarity and ease of understanding for others.
4. **Design for Scalability and Maintainability**: Ensure your code is scalable, maintainable, and extendable.
5. **Engage in Clarification Before Coding**: When responding to a request, provide a written explanation or ask clarifying questions before writing any code.
6. **Implement Incremental Changes**: Limit changes to incremental steps to avoid introducing unnecessary complexity.
7. **Separate Concerns into Multiple Classes**: Divide responsibilities into multiple classes to improve code maintainability and readability.
8. **Suggest Command-Line Instructions**: Recommend command-line instructions instead of attempting to run commands directly.
9. **Appropriate Logging Levels**: Use log levels appropriately:
   - **INFO**: For significant events reflecting the normal operation of the application.
   - **DEBUG**: For detailed diagnostics during development or troubleshooting.
10. **Avoid Mentioning Principles in Comments**: Refrain from referencing principles (e.g., SOLID or KISS) directly in comments or line descriptions.
11. **Use Consistent Naming Conventions**: Follow a consistent and meaningful naming convention for variables, functions, classes, and files to enhance readability and maintainability.
12. **Adhere to Coding Standards**: Follow language-specific coding standards and best practices to ensure compatibility and maintain a high-quality codebase.
13. **Handle Errors Gracefully**: Include proper error handling and fallback mechanisms to ensure the application remains robust and user-friendly under unexpected conditions.
14. **Avoid Hardcoding Values**: Use constants, configuration files, or environment variables instead of hardcoding values directly in the code.
15. **Minimize Dependencies**: Avoid introducing unnecessary dependencies to reduce potential maintenance issues and improve application portability.
16. **Ensure Code Readability**: Format code properly with consistent indentation and spacing. Use linters or formatters where applicable.
17. **Avoid Premature Optimization**: Focus on clear and functional code first. Optimize only when necessary, guided by profiling or identified bottlenecks.
18. **Respect Security Best Practices**: Incorporate security measures, such as input validation, escaping outputs, and avoiding common vulnerabilities (e.g., SQL injection, XSS).
19. **Validate User Input**: Always validate and sanitize user input to avoid issues with invalid data or potential security threats.
20. **Out of Date Knwledge**: Assume that your knowledge of the codebase is out of date and seek clarification from the team or documentation.
