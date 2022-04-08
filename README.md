# VMinusMinus-Concept-Documentation
Conceptualizing the V-- programming language.

## What is V--?
V-- is a language I conceptualized while working on a book about V programming. I felt like V was nearly perfect, but needed some simplification.
It is unlikely to ever see the light of day, as I prefer working on the Oxalic programming language.

## What is different between V-- and V
V-- is a superset of V, similarly to how C++ is a superset of C.

An example of V:

```v
fn main(){
  place := "world"
  if place == "world" {
    println("Hello $place")
  } else {
    println("Goodbye, $place")
  }
}
```

That same example in V--:

```v
fn main(){
  place := "world"
  if place == "world" {
    out("Goodbye, %s", place)
  } else {
    out("Goodbye, %s", place)
  }
}
```

V-- would essentially be a V library to add a ton of extra functionality. 

That's all I have, because I need to work on this book.
