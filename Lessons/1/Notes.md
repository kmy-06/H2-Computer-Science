## Day_1 (12 Feb): (1) Input / Output

IDE: Integrated Development Environment 

print(" ")

x = input(" ")

strings concatenation (joins) - <b> only strings </b> { print(" " + 10): TypeError }



## Day_2 (13 Feb): (2) Variables | Data Types

change ‘age’ -> string: ’18’, to 18 as number using int(age), so that int(age) + 1 is 19 as an integer. 

Constant datatype -> C can, Python cannot (So, use FULL CAPITAL to show the variable should be a constant)

Conversion Uses:
1. str() 
2. int() 
3. float() 
4. bool() 
5. list()
6. tuple()
7. dict()
8. set()

## Day_3 (19 Feb): (3) Math, Relational and Logical Operators

1. Addition: x + y
2. Subtraction: x - y
3. Multiplication: x * y
4. Division: x / y
5. Modulus: x % y
6. Exponential: x ** y
7. Floor Division: x // y -> The floor of a real number x, written as ⌊x⌋, is defined as the greatest integer that is less than or equal to x.


"==" equals to (not assignment of value) <br>
"!=" not equals to # For SQL: "<>" <br>
">" greater than <br>
">=" greater than or equal to <br>
"<" less than <br>
"<=" less than or equal to <br>

print("\n") # New Line :)

## Day_4 (24 Feb): (Reading) System Development Life Cycle (SDLC) & Algorithms

SDLC:

1. Problem Definition (scope of requirements)
2. Problem Analysis (breakdown the main problem)
3. Design Using Flowchart and Pseudocodes (apply abstaction techniques)
4. Solution Development (translate to code)
5. Testing (test with data)
6. Documentation (version control)
7. Deployment ($$$)
8. Evaluation & Maintenance (scale up & updates)

Algorithms:

1. Problem Definition
2. Problem Analysis
3. Design Algorithm

< My God, So Boring ... >

## Day_5 (27 Feb): (Mind Mapping) Flowchart Symbols & Pseudocode Keywords

Flowchart (Without connector & module):

1. Start Programme: oval 
2. Processing Code: rectangle
3. Required Inputs: parallelogram
4. Resulting Output: parallelogram
5. Decision (T/F)(y/n): diamond
6. End Programme: oval

Pseudocode (Examples):

// Commenting <br>

DECLARE y, topspeed: REAL <br>
DECLARE x: INTEGER <br>
CONSTANT totalCars = 100 <br>

INPUT num <br>
topspeed <- 200 <br>
y <- 'E' <br>
x <- y*2 (give value 'y x 2' to 'x' variable) <br>

MATCH num: <br>
  CASE num OF <br>
    ... <br>
      (return "") <br>
    OTHERWISE: ... (case `_`:) <<< The `_` sign acts as a placeholder for any value. <br>
  ENDCASE <br>

WHILE x <= 10 DO: (While 'true' CHECK at the start, program stop until statement is 'false') <br>
  ... (cycles) <br>
ENDWHILE <br>

FOR x <- 1 TO 10 [step 1]: ('x' can be a var_name)(in range (start, end, increment_step)) <br>
  ... <br>
ENDFOR or [NEXT x] <br>

IF x > y THEN:  <br>
  ... (or IF or ELSE IF or ELSE) <br>
ENDIF <br>

OUTPUT result <br>

## Day_6 (28 Feb): (4) Conditions

1. `if-else` statement:

```
x = 3
if x > 5:
    print("x is greater than 5")
else:
    print("x is not greater than 5")
```

2. `if-elif-else` chain:

```
x = 5
if x > 5:
    print("x is greater than 5")
elif x == 5:
    print("x is equal to 5")
else:
    print("x is less than 5")
```

3. Nested `if` statement:

```
x = 10
if x > 5:
    print("x is greater than 5")
    if x > 8:
        print("x is also greater than 8")
```

4. Ternary Conditional Operator (One liner `if` statement):

```
x = 7
result = "x is even" if x % 2 == 0 else "x is odd"
print(result)
```

## Day_7 (3 Mar): (5) Loops



## Day_8 (6 Mar): (7) Collection Data Types

List:
.append(value in list <- at the back)
listname[start:end] = [replace with...]
newlist = list1 + list2
.remove(value in list)
.pop(position) {default - remove last item}
newlist = [4, 5, 6] * 3: To repeat a list, use "*" operator. 

if x is a list, y = x, will make y pointing to the exact same list in memory as x. Thus, the change in list y is equal to the change in list x.
