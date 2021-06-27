# Outrageous Villager Accents

Add-on for the Bedrock edition of Minecraft that gives villagers a really bad French accent

Build the pack with [Bazel](http://bazel.build)

In the project folder use the command:

```
bazel build :outrageous_accents
```

Of course, you can also just zip up the assets folder and rename it to have an mcpack extension. That's probably easier for most people.

For the Java edition resource pack use the following command:

```
bazel build :outrageous_accents_java
```

To build both, and it is pretty fast so you might as well, use the following command:

```
bazel build :all
```
