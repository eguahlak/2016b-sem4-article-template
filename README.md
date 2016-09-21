# Title with name of feature

Short description of the feature your article is about

## Authors

Name of group 

* Author Number One
* Second author
* Third author if a third author exists

## The feature

A deeper description of the feature.
Argue where this feature is usable and where it's not.
Are there any requirements to version of android or to the device or provider.

## Examples of use

Examples of use including examples.
You can find a description of how to write markdown `.md` files
[here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "Markdown Cheatsheet")
and [here](https://guides.github.com/features/mastering-markdown/ "Mastering Markdown")

Examples should include code as:

```kotlin
class Person(val id: Int, var name: String)
```
or
```java
public class Person {
  private final int id;
  private String name;
  
  public Person(int id, String name) {
    this.id = id;
    setName(name);
    }
  
  public int getId() { return id; }
  
  public String getName() { return name; }
  
  public void setName(String value) { 
    if (value == null) throw new IllegalArgumentException();
    name = value;
    }
  
  }
```

Only include relevant examples, try to leave out code that doesn't explain the subject.
In example code in Java it is quite ok to `throws Exception` in order to remove `try -- catch` blocks if they don't contribute
to the explanation. Remember to include the Kotlin version also.
It is a very good idea to refactor Kotlin code if it was generated from Java code.

## Pitfalls and hacks

Describe the pitfalls you have encountered when experimenting with the feature.
Also describe hacks that will help you out where features behave oddly. Argue why it could not be done the *real* way.

## List of sources

### Effective (good) sources

List and rate the sources you have found with useful information about the feature.

### Dead end sources

List the sources to avoid when exploring the feature.
Either because they are dead ends, waste of time or directly misleading.



