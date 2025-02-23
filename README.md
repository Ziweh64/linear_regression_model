# Introduction
This project implements a simple Linear Regression Model in Rust. The goal is to explore how machine learning concepts can be applied using Rust, a systems programming language known for its safety and performance.

# Project Setup and Execution
Rust & Cargo (Install via Rustup).
Verified the installation by restarting the terminal and checking the version(rustc --version, cargo --version).
Installed Visual Studio Build Tools.
Cloning the Repository(git clone https://github.com/Ziweh64/linear_regression_model.git) then navigate through the project(cd linear_regression_model).
Run the project by Cargo run.

# Approach and Challenges
I implemented a linear regression model in Rust by first preparing training data (x and y values) and computing the best-fit line using the least squares method. Once the model was trained, i used it to make predictions and evaluated its accuracy with Mean Squared Error (MSE). The biggest challenges included Rust’s strict ownership model, which required careful handling of memory and variable lifetimes, the lack of built-in machine learning libraries, and floating-point precision issues that required using f64 instead of f32 for better accuracy

# Resources Used
Rust Documentation: https://doc.rust-lang.org/
AI Tools: ChatGPT for Rust syntax clarification and debugging hints.

# Results and Lessons Learned
The project did not run because of Rust and Cargo were not installed correctly and the required Visual Studio Build Tools were missing on Windows. Syntax errors, incorrect memory handling, or floating-point precision issues caused unexpected behavior. The main lesson learned is that Rust's strict ownership model requires careful management of memory and data references. Unlike Python, which has built-in libraries for ML, Rust requires more manual implementation, making it a good learning experience in handling low-level computations efficiently.

# How Much Help I Received

AI Assistance: Used for understanding Rust’s borrow checker and resolving ownership conflicts.
Documentation: Rust’s official docs were essential for understanding Vec operations and iterators.
Other Sources: Followed a few open-source Rust ML projects for best practices.





