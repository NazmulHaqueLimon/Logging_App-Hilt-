In this logging app we'll learn the importance of dependency injection (DI) to create a solid and extensible application that scales to large projects. We'll use Hilt as the DI tool to manage dependencies.


# Introduction
Dependency injection is a technique widely used in programming and well suited
to Android development. By following the principles of dependency injection, you
lay the groundwork for a good app architecture.

Implementing dependency injection provides you with the following advantages:
* Reusability of code.
* Ease of refactoring.
* Ease of testing.

Hilt provides a standard way to do DI injection in your application by providing containers to every Android component in your project and managing the container's lifecycle automatically for you. This is done by leveraging the popular DI library: Dagger.
