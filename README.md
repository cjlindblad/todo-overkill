# todo-overkill

The purpose of this repo is for me to learn a new backend stack:
- Kotlin
- Spring Boot
- GraphQL
- Docker

To keep the domain as simple as possible, it will be yet another todo app! :tada:

Disclaimer: This repo will probably not represent any best practices, and the architecture is most certainly going to be overkill for the application.

Rough plan:
1. TDD the core application logic in Kotlin.
2. Slap on a Rest API with Spring Boot.
3. Add GraphQL - either to the existing API, or as a separate service. Consume it with a small React app.
4. Containerize (is that a real word?) with Docker and publish.

The choice of DB doesn't really matter for this one. I'll wait and see what seems to be the most straightforward choice for the stack.
