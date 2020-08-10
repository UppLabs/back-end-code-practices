# Back-end General Code Practices

1. Self-documented code and clear code. Our code should be clear and well understandable for all current team members and anyone who will join the team later or will be supporting our projects. To do that we have to follow a few steps:

1.1 Naming conventions of variables, methods, classes, etc.

1.2 DO choose easily readable identifier names.

1.3 DO favor readability over brevity.

1.4 DO NOT use underscores, hyphens, or any other non alphanumeric characters.

1.5 DO NOT use abbreviations or contractions as part of identifier names.
For example, use GetWindow rather than GetWin.

1.6 DO use semantically interesting names rather than language-specific keywords for type names.
For example, GetLength is a better name than GetInt.

1.7 Limit the size of methods. If a method is longer than 1 screen of your monitor than split it in a couple of smaller methods.
Consider adding comments to your classes, methodes if the name or the responsibility of this one is not very clear.

1.8 DO NOT mutate objects in child methods. 

1.9 Limit the amount of params that are passed to a method. If there are more than 3-4 params consider creating a DTO (data transfer object).

1.10 Commented out code is not allowed in the master branch.

1.11 DO NOT hardcode values in the code (move them into constants and reuse).

2. Follow DRY principle. Don’t Repeat Yourself and reuse your code or code which was written by another team member. If there is no method to reuse it, feel free to create one. 

3. Follow SOLID principles. https://docs.microsoft.com/en-us/archive/msdn-magazine/2014/may/csharp-best-practices-dangers-of-violating-solid-principles-in-csharp

4. Follow the architecture of the application and don't mess the responsibility up in the layers.

5. Think about scalability of microservice when working with it.
