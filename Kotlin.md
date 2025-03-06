# [[Java]]-esq [[OOP]] language that also uses the [[jvm]]

```kotlin
fun name(arg: Type = defaultValue): ReturnType {
	val immutable: Int = 1 // all types are capitalized
	var mutable = "hi"
	mutable = "xelA"
	println("Hi $mutable")
	
	mutable = if (immutable == 1) {
		"The best"
	} else {
		"The worst"
	} // can also inline this whole statment
	
	val thebest: Boolean = when (mutable) {
		"The best" -> true
		"The worst" -> false
		else -> false // default
	}
	
	val array = arrayOf(1, 2, 3, 4)
	
	if (3 in array) {
		// do somthing
	} 
	
	for (item in array) {
		item++
	}
	
	for (i in 0..1000) {
		// does 1000 times
	}
}

// open means others can inherit
open class MyClass(var constructer: String) {
	fun associatedFun() {}
}

class ChildMyClass: MyClass(/* cant be bothered by this*/) {

}
```

## Features
- Must explicitly convert between types
- Named and default arguments
- Can index directly into a string `string[0]`
