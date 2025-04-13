> "What rubbish is this?" - Student X commenting on H2 Computing Notes


## Day_1 (12 Feb): (1) Input / Output

IDE: Integrated Development Environment 

print(" ")

x = input(" ")

strings concatenation (joins) - <b> only strings </b> { print(" " + 10): TypeError }



## Day_2 (13 Feb): (2) Variables | Primitive Data Types

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

1. while loop

2. repeat-until: must satisfy at least one condition

3. for loop

4. nested for loop

5. nested while loop

6. loop control statement: break, continue, pass


## Day_8 (6 Mar): Collection Data Types

Properties:

- Ordered/Unordered

whether items in the Collection Data Type have a defined order

- Changeable/Unchangeable

whether we can change, add, and remove items in the
Collection Data Type after it has been created.

- Allow Duplicates/Duplicates not allowed

whether it is possible to have items with the same value in the
Collection Data Type

Mainly Four:

1. List <br>

2. Dictionary <br>

3. Tuple <br>

4. Sets <br>

## Day_9 (7 Mar): (6) Lists

.append(value in list <- at the back)

listname[start:end] = [replace with...]

newlist = list1 + list2

.remove(value in list)

.pop(position) {default - remove last item}

newlist = [4, 5, 6] * 3: To repeat a list, use "*" operator. f

if x is a list, y = x, will make y pointing to the exact same list in memory as x. Thus, the change in list y is equal to the change in list x.

## Day_10 (10 Mar): Arrays and File Processing

Note: 'Subscript' in an array refers to the 'index' of an element. It is usually enclosed with [ ].

One-Dimensional (1D) Array: DECLARE `<`identifier`>`: ARRAY [<L>:<U>] OF `<`data type`>`

- e.g DECLARE StudentAges: ARRAY [1:10] OF INTEGER

Two-Dimensional (2D) Array: DECLARE `<`identifier`>`: ARRAY [<L1>:<U1>,<L2>:<U2>] OF `<`data type`>`

- e.g DECLARE Attendance: ARRAY [1:5,1:4] OF CHAR  <- means [row,column]

So, maybe we can look into Numpy 3D array in the future.

And, of course, c++ can manage memory more efficiently.

## Day_11 (13 Mar): (7) 2D Array & Dictionary

2D array can be seen as a table with rows and columns.

Dictionary = {} <- Flexible tools, uses mappings.

'Mapping' denotes (意味着) an object that maps key to associated values. (only for dictionary)

Mappings do not maintain any left-to-right positional ordering, only supports access to data stored by key and type-specific method calls.

## Day_12 (24 Mar): (8) Files Processing

- Read file:

f = open('data.txt','r')

for line in f:

- Write file:

f = open('data.txt', 'w')

f.write('...')

## Day_13 (27 Mar): Jupyter Notebook

Terminal Commands:

H: (open h: drive for personal storage)

jupyter notebook (opens up jupyter notebook)

cd ...

mkdir ...

ls -A

## Day_14 (28 Mar): (9) Tuples

not a list, tuples are more foundamental and definitional

## Day_15 (3 Apr): (10) Strings

immutable, so we have to change it to list, then join back to string

there are many formating, modifying, subsituting, printing, embedding methods

## Day_16 (4 Apr): (7) + More Dictionary

## Day_17 (7 Apr): Dicision Table

## Day_18 (10 Apr): Dicision Table

## Day_19 (11 Apr): (11) Functions
