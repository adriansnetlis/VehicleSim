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
Function name's first word must start with lowercase, every next - with uppercase. Must use only full names of functions, no first-letter-only or similar shorter versions (we must make sure that everybody can read and understand, what's going on).

| Name         | Correct? |
|:------------:|:--------:|
| TestFunction | No       |
| testfunction | No       |
| testFunction | Yes      |
| tf           | No       |
| testFunc     | No       |

##### variables
Variables, just like functions, start with lowercase and every next letter - with uppercase. For most of variables only full names are allowed. Exceptions are physics variables, where you can use the letters as used in physics(e.g. `v` for `velocity`, `t` for time, `d_t`(`d_` stands for delta) for `deltaTime`).

| Name          | Correct? |
|:-------------:|:--------:|
| DeltaVelocity | No       |
| deltavelocity | No       |
| deltaVelocity | Yes      |
| dv            | No       |
| d_v           | Yes      |
| deltaVel      | No       |
