data Types in Rust:

- Primitive data types in Rust
    - Scalar - Data types with a single value
    - Compound -data types with a mutiple value like a bytes, an array etc

different types of Primitive scalar data types in Rust
- integer (u8, u32, u64, u128, i8, i16, i32, i64, i128)
- float (f32, f64)
- boolean (true, false or 1 and 0)
- character type(declare with `char` key word)



different types of Primitive compound data types in Rust

- tuple (this can hold different type of data types, it is declare and access as follows, `let tup: (i32, bool, char) = (1, true, 's')` to access the element within a tuple we use this format tup.index_of_the element eg ` tup.1` will return true. When the `mut` keyword is added to the begining of a tup, we can change the value at the index we access)