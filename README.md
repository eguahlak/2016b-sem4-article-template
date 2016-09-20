# Title with name of feature

Short description of the feature your article is about

## Authors

Name of group 

* Author Number One
* Second author
* Third author if a third author exists

## Examples of use

Examples of use including examples.
You can find a description of how to write markdown *.md* files
[here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "Markdown Cheatsheet")

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



