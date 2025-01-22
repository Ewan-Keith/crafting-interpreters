## jlox

my (probably quite poor) implementation of the java compiler for lox from the Crafting Interpeters book.


### handy commands

Compile the project:
```sh
mvn package
```

run the build:
```sh
java -cp target/jlox-1.0-SNAPSHOT.jar com.craftinginterpeters.lox.Lox
```

run the code-gen tool:
```sh
java -cp target/jlox-1.0-SNAPSHOT.jar com.craftinginterpeters.tool.GenerateAst src/main/java/com/craftinginterpeters/lox
```
