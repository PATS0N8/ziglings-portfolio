# Ziglings Progress Log

## 1. Hello World
Fixed by marking `main` as `pub` and adding newline.
Status:  Completed

## 2. std import
Added correct std import line and compiled successfully.
Status:  Completed

## 3. Assignment
Changed const to var for reassignment, fixed integer sizes (u32/i8).
Status:  Completed
## 4. Arrays
Changed const to var for mutability, used zero-based index, and .len for length.
Status:  Completed
## 5. Arrays 2
Used ++ to concatenate arrays and ** to repeat patterns.
Status: Completed
## 6. Strings 1
Indexed a character from a string, used ** to repeat, and ++ to concatenate strings.
Status: Completed

## 7. Strings 2
Practiced multi-line string syntax using \\ at the start of each line.
Status: Completed
## 8. Quiz
Reviewed variable mutability and array indexing to spell "Zig".
Status: Completed
## 9. If Statements
Learned that conditions must be booleans and compared foo == 1.
Status: Completed
## 10. If Expressions
Used an if...else expression to assign a value based on a condition.
Status: Completed
## 11. While Loops
Used while (n < 1024) to loop and double n until it reached 1024.
Status: Completed
## 12. While Loops (Continue Expressions)
Moved n *= 2 into a continue expression in the while loop.
Status: Completed
## 13. While with Continue
Used continue to skip numbers divisible by 3 or 5.
Status: Completed
## 14. While with Break
Used break to stop an infinite while loop when n == 4.
Status: Completed
## 15. For Loops
Used a for loop to iterate over an array and print reactions for each scene.
Status: Completed
## For with index / binary accumulation
Used `for (bits, 0..)` with index, `@intCast` to u32, and `std.math.pow` to compute place values; result 13.
Status: Completed
## 17. Quiz: FizzBuzz
Implemented a while loop with modulo conditions to print Fizz, Buzz, or the number as well as change function to pub fn
Status: Completed
## 18. Functions
Created a simple function `deepThought()` returning 42 and called it from main.
Status: Completed
## 19. Functions with Parameters
Defined a function twoToThe(my_number: u32) returning 2^my_number using std.math.pow.
Status: Completed
## 20. Loops in Functions
Replaced placeholder 'loop' with for and while, combining both in functional examples.
Status: Completed
## 21. Errors 1
Added TooSmall to error set and matched on it in main.
Status: Completed
## 22. Errors 2
Learned about error unions by combining MyNumberError with u8 using the ! operator.
Status: Completed
## 23. Errors 3
Used MyNumberError!u32 as a return type and handled errors with catch.
Status: Completed
## 24. Errors 4
Fixed fixTooSmall() using catch |err| to return 10 on TooSmall and propagate others.
Status: Completed


## 25. Errors 5
Used try to propagate errors from detect() in addFive().
Status: Completed

## 26. Errors 6
Used try to propagate possible stdout.print() error in main().
Status: Completed

## 27. Defer 1
Used defer to ensure 'Two' prints after 'One'.
Status: Completed

## 28. Defer 2
Used defer to print closing ") " after each animal.
Status: Completed

## 30. Switch 1
Added 'else' branch to switch to print '?' for unmatched values.
Status: Completed
## 31. Switch 2
Added else clause returning '!' for unmatched characters.
Status: Completed

## 32. Switch 3
Fixed missing closing brace and moved print outside switch.
Status: Completed

## 33. Error unions with switch
Added match for TooSmall printing '<4.'
Status: Completed
## 34. Error unions with try
Changed main to !void and added try getNumber().
Kept writer(&.{}) + interface.print for this Zig version.
Status: Completed

## 35. Enums and exhaustive switches
Added enum Ops { inc, dec, pow } and verified output sequence.
Status: Completed

## 36. Enum hex colors
Added Color.blue = 0x0000ff and formatted output with {x:0>6} for all RGB values.
Status: Completed

## 37. Structs and fields
Added health: u8 to Character struct and initialized with 100.
Status: Completed

## 38. Struct arrays
Added Zump the Loud with role=bard, gold=10, health=100, experience=20.
Status: Completed

## 39. Pointers and dereferencing
Used num1_pointer.* to set num2 equal to num1’s value.
Status: Completed

## 40. Pointer const correctness
Changed b to *const u8 because a is immutable.
Status: Completed

## 41. Mutable pointer reassign
Used 'var p: *u8' so it can point to foo or bar and mutate through p.*.
Status: Completed

## 42. Pointer parameter
Assigned via pointer with x.* = 5 in makeFive().
Status: Completed

## 43. Struct pointers and optionals
Passed &glorp into printCharacter to match *Character parameter.
Status: Completed

## 44. Self-referential structs
Added Elephant B and linked tails A->B->C->A to form circular chain.
Status: Completed

## 45. Optionals and orelse
Used result orelse 42 to handle null optional from deepThought().
Status: Completed

