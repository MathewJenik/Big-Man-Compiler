# Big-Man-Compiler
Custom compiler and language made for the purpose of allowing me to gain a greater understanding of how compilers work.

The langauge created for this compiler, known as BigMan or BM as short, follows this language structure:

##### if statements structure.
```
if (1 == 1) {

}
```

##### inline variables structure.
```
int i = 0;
```

##### public accessable variables.
```
public int i = 0;
```

##### private accessable variables.
```
private int i = 0;
```

##### method 1 of printing to the console. This way prints to a new line each time.
```
println("message");
println("number" + i);
```

##### methed 2 of printing to the console. This way prints to the same line unless specified with the new line character.
```
console.log("message");
console.log("number" + i);
```

##### how a function will be structured.
```
public void printError(string error) {
	println("ERROR: " + error);
}

public int addition(int x, int y) {
	return(x + y);
}
```
