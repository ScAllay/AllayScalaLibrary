# Scala Library for Allay Plugins

Scala standard library and scala toolkit packages for allay.

## Usage

### For Plugin Users

Put the jar in release into `plugins` folder.

### For Plugin Developer

Write the following json to the `dependencies` to ensure that the dependency library is loaded

```json
{
    "name":"AllayScalaLibrary",
    "version":"3.6.2"
}
```

You can add `ivy"org.scala-lang::toolkit:0.6.0"` into your compilonly dependencies. and not carrying the scala standard library in the plugin.
