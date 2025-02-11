Reference [this guide](https://openjdk.org/projects/jigsaw/quick-start) to follow along.

run a module:
```
java --module-path mods -m client/client.Main
```

compile all modules:
```
javac -d mods --module-source-path src $(find src -name "*.java")
```
