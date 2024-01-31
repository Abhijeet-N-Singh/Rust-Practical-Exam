# Rust-Practical-Exam
This is a repository on practical exam of Rust programming language !
Practical exam on Rust Programming Language

1) Write a Rust Program that implements a looping statement for loop.

answer- Command is :

$ cargo new rust_programs

next open the rust_programs folder in visual studio code and edit with the file main.rs present in src directory with the below program that i want to execute.

fn main(){
    for i in 1..=6 {
        println!("Count: {}", i);
    }
}


Then enter into the rust_programs folder from the source directory using the below command:

cd rust_programs

After entering into the directory run the below commands for executing main.rs file present in src directory.

cargo build

cargo run
