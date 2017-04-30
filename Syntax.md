This is the syntax used in the project.

## C++
#### functions
```c++
int squarePlusOne(int a)
{
	return a * a + 1;
}

void forbiddenTest()
{
	cout << "Don't run this test!\n";
}
```
#### loops
```c++
while (time < 52.5) {
	time += 0.75;
}
for (int i = 0; i < 100; i++) {
	cout << i * i;
}
```
#### statements
```c++
if (a > b) {
	cout << "a is big\n";
} else if (b > a) {
	cout << "b is big\n";
} else {
	cout << "they're equal\n";
}
```

Identation must be consistent where each next identation level is 4 whitespaces(1 tab) deeper than previous one.

All the variables and function names must be exact and straightforward. To keep consitency and readability, I've decided that the names of functions and variables must be designed like so:

##### functions
* Function name's first word must start with lowercase, every next - with uppercase.

| Name         | Correct? |
|:------------:|:--------:|
| TestFunction | No       |
| testfunction | No       |
| testFunction | Yes      |
| tf           | No       |
| testFunc     | No       |
