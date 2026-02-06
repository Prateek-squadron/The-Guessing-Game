# 🎯 Guess the Number — Rust Fundamentals Application

This project is a **command-line number guessing game** built using **core Rust fundamentals**.  
It is designed as a practical application to understand how Rust handles **input/output, randomness, control flow, ownership, and pattern matching**.

---

## 📌 Project Overview

The program:
- Randomly generates a secret number between **1 and 100**
- Continuously asks the user to guess the number
- Compares the guess with the secret number
- Provides feedback until the correct number is guessed

This project closely follows idiomatic Rust practices and mirrors real-world CLI application structure.

---

## 🧠 Rust Concepts Demonstrated

This project covers the following **Rust fundamentals**:

### 1. Standard Library Usage
- `std::io` → handling user input
- `std::cmp::Ordering` → comparing values safely

### 2. External Crates
- `rand` crate for random number generation

### 3. Ownership & Mutability
- Mutable variables using `let mut`
- Borrowing with references (`&mut`)

### 4. Error Handling
- `expect()` for handling potential runtime failures
- Safe parsing of user input

### 5. Control Flow
- `loop` for continuous execution
- `match` for exhaustive pattern matching

### 6. Type Safety
- Explicit type conversion (`String → u32`)
- Compile-time guarantees against invalid comparisons

---

## 🛠️ How It Works (Logic Flow)

1. Generate a random number between `1..=100`
2. Prompt the user for input
3. Read and parse the input
4. Compare the guess with the secret number
5. Print feedback:
   - `Too small`
   - `Too big`
   - `You win`
6. Repeat until the correct guess is made

---

## 🚀 How to Run the Project

### Prerequisites
- Rust installed (`rustc` and `cargo`)
- Internet access (for downloading the `rand` crate)

### Steps

```bash
# Clone the repository
git clone https://github.com/Prateek-squadron/The-Guessing-Game

# Navigate into the project directory
cd guess_the_number

# Run the application
cargo run
