# Swift
For ios Swift
1. Apart from Int, String, Boolean swift also has Array, Set, and Dictionary. Like C, Swift uses variables to store and refer to values by an identifying name. Swift also makes extensive use of variables whose values can’t be changed. These are known as constants, and are much more powerful than constants in C. Swift also has Tuples. Tuples enable you to create and pass around groupings of values. You can use a tuple to return multiple values from a function as a single compound value.
2. You declare constants with the let keyword and variables with the var keyword. If you need to give a constant or variable the same name as a reserved Swift keyword, surround the keyword with backticks.
3. The print(_:separator:terminator:) function is a global function that prints one or more values to an appropriate output. In Xcode, for example, the print(_:separator:terminator:) function prints its output in Xcode’s “console” pane. The separator and terminator parameter have default values, so you can omit them when you call this function. By default, the function terminates the line it prints by adding a line break. To print a value without a line break after it, pass an empty string as the terminator—for example, print(someValue, terminator: ""). For information about parameters with default values, see Default Parameter Values. Swift uses string interpolation to include the name of a constant or variable as a placeholder in a longer string, and to prompt Swift to replace it with the current value of that constant or variable. Wrap the name in parentheses and escape it with a backslash before the opening parenthesis.
4.  Swift is type safe, it performs type checks when compiling your code and flags any mismatched types as errors. If you don’t specify the type of value you need, Swift uses type inference to work out the appropriate type. Type inference enables a compiler to deduce the type of a particular expression automatically when it compiles your code, simply by examining the values you provide. Swift always chooses Double (rather than Float) when inferring the type of floating-point numbers. 
  ```
      let meaningOfLife = 42
   ``` 
5. To convert one specific number type to another, you initialize a new number of the desired type with the existing value. In the example below, the constant twoThousand is of type UInt16, whereas the constant one is of type UInt8. They can’t be added together directly, because they’re not of the same type. Instead, this example calls UInt16(one) to create a new UInt16 initialized with the value of one, and uses this value in place of the original:
  ```
let twoThousand: UInt16 = 2_000
let one: UInt8 = 1
let twoThousandAndOne = twoThousand + UInt16(one)
  ```
Because both sides of the addition are now of type UInt16, the addition is allowed. The output constant (twoThousandAndOne) is inferred to be of type UInt16, because it’s the sum of two UInt16 values.
6. @IBOutlet, is a connection from an Interface Builder user interface component – e.g. a UIButton – to a property in a view controller or other piece of Swift code.
7. Let is a keyword for constant and var is a keyword for variables.
8. left is anchor for leading area and right is an anchor for trailing area. Superview is the view that represents the entire screen. Safe area is the area which is 44px from top and 34 px from bottom.
