# Linear_regression_model
# Introduction
This project implements a simple Linear Regression Model in Rust. The goal is to explore how machine learning concepts can be applied using Rust, a systems programming language known for its safety and performance.

# Project Setup and Execution
Rust & Cargo (Installed via Rustup)
Restart your terminal and verify the installation (rustc --version, cargo --version)
Installed Visual Studio Build Tools
Cloned the Repository (git clone https://github.com/Ziweh64/linear_regression_model.git)
Running the Project(cargo run)

# Approach and Challenges
I implemented a linear regression model in Rust by first preparing training data (x and y values) and computing the best-fit line using the least squares method. Once the model was trained,i used it to make predictions and evaluated its accuracy with Mean Squared Error (MSE). The biggest challenges included Rust’s strict ownership model, which required careful handling of memory and variable lifetimes, the lack of built-in machine learning libraries, and floating-point precision issues that required using f64 instead of f32 for better accuracy.

# Resources Used
Rust Documentation: https://doc.rust-lang.org/
AI Tools: ChatGPT for Rust syntax clarification and debugging hints.

# Results and Lessons Learned
The project did not run because of the required Visual Studio Build Tools that are missing on Windows. Syntax errors, incorrect memory handling, or floating-point precision issues caused unexpected behavior. The main lesson learned is that Rust's strict ownership model requires careful management of memory and data references.Debugging in Rust also teached me structured problem-solving, as its compiler enforces strict rules that prevent common runtime errors.




