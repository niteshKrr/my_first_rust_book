# Chapter 1

```rust

fn main() {
    println!("Hello world");
}


```


```rust,editable

# fn main() {
    let x = 5;
    let y = 6;

    println!("{}", x + y);
# }

```

```rust,ignore
# This example won't be tested.
panic!("oops!");
```


```rust,noplayground
let mut name = String::new();
std::io::stdin().read_line(&mut name).expect("failed to read line");
println!("Hello {}!", name);
```
![loading..](./assets/405644238_max.jpg)

<p><img class="right" src="assets/405644238_max.jpg" height="300px" width="300px" alt="The Rust Logo" /></p>

<br>

<div class="warning">

This is a bad thing that you should pay attention to.

Warning blocks should be used sparingly in documentation, to avoid "warning
fatigue," where people are trained to ignore them because they usually don't
matter for what they're doing.

</div>
