# VMinusMinus-Concept-Documentation
Conceptualizing a potential V-- programming language.

## What is V--?
V-- is a language I conceptualized while working on a book about V programming. I felt like V was nearly perfect, but needed some simplification.
It is unlikely to ever see the light of day, as I prefer working on the Oxalic programming language.

## What is different between V-- and V
V-- is a superset of V, similarly to how C++ is a superset of C.

An example of V:

```v
fn main(){
	mut a := 0
	mut b := 1
	mut c := a + b
	for a < 1000000 {
		println(a)
		a = b 
		b = c 
		c = a + b
	}
}
```

That same example in V--:

```v
main {
    mut a := 0
    mut b := 1
    mut c := a + b
    for a < 1000000 {
        vout << a
        a = b 
        b = c
        c = a + b
    }
}
```

V-- is a simplified, C++ like version of V. Unlike C++, V-- would not be OOP.
