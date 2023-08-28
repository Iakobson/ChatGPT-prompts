# ChatGPT-prompts


## Загальна структура промпту

1. **Роль**
    + «Act as»
2. **Суть завдання**
3. **Контекст**
4. **Мета завдання**
5. **Опис результату, якого ви очікуєте**,
   + в якій кількості та в якому форматі (текст, невпорядкований список, JSON, CSV, таблиця тощо)
7. **Умови та обмеження.**
   + «Do not write your own opinion» — просимо не додавати власну думку.

### приклади

Act as a cybersecurity specialist.\
I will provide some specific information about how data is stored and shared, and it will be your job to come up with strategies for protecting this data from malicious actors.\
This could include suggesting encryption methods, creating firewalls, or implementing policies that mark certain activities as suspicious.\
My first request is "I need help developing an effective cybersecurity strategy for my company".

Act as a code generation tool and develop a Node.js microservice for the e-commerce domain that includes endpoints for user authentication, product catalog management, and order processing.\
The microservice should adhere to the MVC (Model-View-Controller) design pattern.

Act as a code generation tool and generate a HTML template for a basic blog website.\
The template should include placeholders for the blog post title, content, author, and publication date.

Act as a code generation tool and generate a JavaScript function that calculates the total price of a shopping cart.\
The function should take an array of items with their prices and quantities as input.


**Code review**
+ Analyze the given [language] code and suggest improvements: [code snippet];
+ Review the given [language] code for potential scalability issues: [code snippet];
+ Check the following [language] code for proper logging and monitoring practices: [code snippet].

Act as a code reviewer and analyze my JavaScript code for a responsive website design.\
Look for any potential performance issues or ways to optimize the code.

Act as a code reviewer and assess the security of my application.\
Check for any potential vulnerabilities or best practices that should be implemented.

Act as a code reviewer for my JS application that handles database operations.\
Please review the database design and query optimization strategies.

Act as a code reviewer and analyze my SQL queries for a database-driven application.\
Check for any potential security vulnerabilities or ways to improve query performance.


**Документація**

Act as a technical writer and explain the input parameters, output, and usage guidelines for the [function/class] in the given JavaScript code: [code snippet].

Act as a developer and generate detailed documentation for the [API/library] in the following JavaScript code, including its methods, parameters, and return values: [code snippet].

Act as a technical writer and describe the purpose, dependencies, and usage instructions for the [module/package] in the given JavaScript code: [code snippet].

Act as a technical writer and provide detailed documentation for the [function/class] in the following TypeScript code, including its purpose, parameters, and usage examples: [code snippet].

Act as a technical writer and explain the purpose, workflow, and configuration options of the [framework/library] in the provided TypeScript code: [code snippet].

Act as a developer  and generate API documentation for the [RESTful API/endpoint] in the given Node.js code, including supported HTTP methods, request/response formats, and authentication requirements: [code snippet].


**Рефакторинг коду**

Act as a Developer and suggest ways to improve the efficiency and readability of the [function/class/module] in the following TypeScript code: [code snippet].

Act as a Developer and identify any code smells or antipatterns in the provided TypeScript code, suggesting alternative approaches for cleaner and more maintainable code: [code snippet].

Act as a Developer and propose refactoring techniques to simplify the complex conditional statements and loops in the given JavaScript code: [code snippet].

Act as a Developer and refactor the redundant code blocks and duplicate logic in the provided TypeScript code to improve code reusability and maintainability: [code snippet].

Act as a Developer and suggest ways to enhance the performance and scalability of the [class/module] in the following TypeScript code, considering best practices and design patterns: [code snippet].

Act as a Developer and propose a more concise and elegant implementation for the [function/class] in the given TypeScript code, eliminating any unnecessary complexity or repetition: [code snippet].

Act as a Developer and identify opportunities for abstraction and modularization in the provided TypeScript code, making it more modular and easier to maintain: [code snippet].

Act as a Developer and suggest improvements to the naming conventions, variable declarations, and code organization in the given TypeScript code to enhance code clarity and readability: [code snippet].

Act as a Developer and propose refactoring techniques to optimize the database queries and improve the overall performance of the provided SQL script: [code snippet].

Act as a Developer and suggest ways to make the code in the given TypeScript script more testable and decoupled, promoting better separation of concerns and code modularity: [code snippet].


**Проєктування системи та архітектура**

Act as a system design and architecture consultant and provide guidance on designing a scalable and fault-tolerant distributed system.\
Discuss key principles and patterns, such as load balancing, replication, and partitioning, that should be considered in the design.

Act as a system design and architecture expert and outline the architectural components and their interactions for building a real-time chat application.\
Consider aspects like message routing, data synchronization, and scalability in your design.

Act as a system design and architecture consultant and propose an architecture for a cloud-based e-commerce platform.\
Discuss how to handle high traffic, ensure data consistency, and incorporate features like user authentication and order processing.

Act as a system design and architecture expert and explain the design considerations for building a microservices-based architecture.\
Discuss topics like service decomposition, communication protocols, and fault tolerance in the design.

Act as a system design and architecture consultant and design a data warehouse system for analyzing large volumes of data.\
Discuss the selection of appropriate storage technologies, data ingestion processes, and query optimization techniques.

Act as a system design and architecture expert and propose an architecture for a content delivery network (CDN) to efficiently serve multimedia content worldwide.\
Discuss concepts like caching, edge servers, and content routing in your design.

Act as a system design and architecture consultant and design a high-performance database system for a financial application.\
Discuss strategies for data indexing, query optimization, and ensuring data integrity in the design.

Act as a system design and architecture expert and propose an architecture for a scalable and secure IoT (Internet of Things) platform.\
Discuss topics like device management, data processing, and authentication mechanisms in your design.

Act as a system design and architecture consultant and design a fault-tolerant backup and disaster recovery system for a critical business application.\
Discuss replication strategies, backup scheduling, and failover mechanisms in your design.

Act as a system design and architecture expert and propose an architecture for a real-time analytics platform.\
Discuss topics like data ingestion, stream processing, and visualization components in your design.



