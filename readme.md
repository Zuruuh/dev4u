## UML Diagrams

UML diagrams are written using PlantUML expression, then built into images using their cli. To facilitate development you can use an extension for your IDE.

- [VS Code](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)
- [Jetbrains IDEs](https://plugins.jetbrains.com/plugin/7017-plantuml-integration)

To keep some consistency between diagrams, some rules/guidelines might be defined here. Please read them before writing new diagrams

- A visitor is a new user, that does not have an account on the app.
- A member has an account, but is not authenticated.
- A user has an account and is authenticated

### Build UML into images

You can use the cli in the `bin` folder to build your images

```sh
./bin/plantuml diagrams/use_cases/my_diagram.puml
```

If you want to rebuild all diagrams you can use this command

```sh
./bin/plantuml diagrams/**/*.puml
```
