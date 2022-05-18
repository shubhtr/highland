# Swift-Reference

This repository contains a collection of sample code, recipes, snippets, etc for the Swift programming language.

# Declaring Constants

    //using let keyword
    let a: Double = 2.0

    //error - cannot reassign a let
    //a = 3.0

    //inferred double
    let inferredDouble = 2.0

# Declaring variables

    //using var keyword
    var mutableInt: Int = 1
    
    //reassign a var
    mutableInt = 2

# Numeric Type Conversion

    let a = 8       //integer
    let b = 8.0     //double

    //let sum = a + b
    //error: type mismatch

    //opt-in approach - prevent hidden conversion errors and
    //makes type conversion intentions explicit
    let sum = Double(a) + double
    //ok: both values have the same type
