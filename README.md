# Open Module Api Documentation

One markdown file should contains the complete public api for a module = Open Api for modules.
First Idea as example SomeClass.md:
```
# Module x

fun root1(a: Int)

...

## Subpackage1 --> should be foldable

fun sub1(): String

fun sub2(): SomeClass --> SomeClass should be a link to its spec.

...

```

All referenced types must be linked and therfore stored as an additional file:
```
# Data Class A

propertyA: String
proertyB: Int
```
