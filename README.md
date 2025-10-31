# 🦀 Rust Journey

Learning Rust through [The Rust Programming Language](https://doc.rust-lang.org/book/) book. Daily practice and exercises.

## 📚 Progress Through The Book

### Chapter 1: Getting Started
- [x] 1.1 Installation
- [x] 1.2 Hello, World!
- [x] 1.3 Hello, Cargo!

### Chapter 2: Programming a Guessing Game
- [x] 2.0 Guessing Game Project

### Chapter 3: Common Programming Concepts
- [x] 3.1 Variables and Mutability
- [x] 3.2 Data Types
- [x] 3.3 Functions
- [x] 3.4 Comments
- [x] 3.5 Control Flow ⬅️ **Currently Here**
- [ ] 3.6 Next up...

### Chapter 4: Understanding Ownership
- [ ] 4.1 What is Ownership?
- [ ] 4.2 References and Borrowing
- [ ] 4.3 The Slice Type

### Chapter 5: Using Structs
- [ ] 5.1 Defining and Instantiating Structs
- [ ] 5.2 An Example Program Using Structs
- [ ] 5.3 Method Syntax

### Chapter 6: Enums and Pattern Matching
- [ ] 6.1 Defining an Enum
- [ ] 6.2 The match Control Flow Construct
- [ ] 6.3 Concise Control Flow with if let

### Chapter 7: Managing Growing Projects
- [ ] 7.1 Packages and Crates
- [ ] 7.2 Defining Modules
- [ ] 7.3 Paths for Referring to an Item in the Module Tree
- [ ] 7.4 Bringing Paths Into Scope with the use Keyword
- [ ] 7.5 Separating Modules into Different Files

*...more chapters as I progress*

## 📂 Repository Structure

```
rust_journey/
├── ch01-getting-started/
│   ├── hello_world/
│   └── hello_cargo/
├── ch02-guessing-game/
│   └── guessing_game/
├── ch03-common-concepts/
│   ├── variables/
│   └── functions/
└── README.md
```

## 🎯 Goals

- Complete The Rust Programming Language book
- Code every day to build GitHub streak
- Document learnings and challenges
- Build muscle memory with Rust syntax

## 💡 Key Learnings So Far

**Ownership System:** The biggest mental shift from other languages. Every value has a single owner.

**Immutability by Default:** Variables are immutable unless marked with `mut`. This prevents bugs.

**Pattern Matching:** The `match` expression forces you to handle all cases. Super powerful.

**No Null:** Rust uses `Option<T>` instead of null, eliminating null pointer exceptions.

## 🔧 Running the Code

```bash
# Navigate to any chapter directory
cd ch03-common-concepts/functions

# Build and run
cargo run

# Run tests
cargo test
```

## 📖 Resources

- [The Rust Programming Language](https://doc.rust-lang.org/book/)
- [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
- [Rustlings](https://github.com/rust-lang/rustlings)

---

🚀 **Learning in public** | 📅 Started: October 2025

