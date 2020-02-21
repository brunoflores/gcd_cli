# gcd CLI

```rust
$ cargo run 5610 57057
   Compiling rust_book_gcd v0.1.0 (/Users/brunoflores/devel/rust_book_gcd)
    Finished dev [unoptimized + debuginfo] target(s) in 0.34s
     Running `target/debug/rust_book_gcd 5610 57057`
n: 5610, m: 57057
57057 % 5610 = 957
n: 957, m: 5610
5610 % 957 = 825
n: 825, m: 957
957 % 825 = 132
n: 132, m: 825
825 % 132 = 33
n: 33, m: 132
132 % 33 = 0
The greatest common divisor of [5610, 57057] is 33
```
