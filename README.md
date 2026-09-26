# AAYU Example Projects 🚀

Welcome to the **AAYU Examples Repository**! 

This repository contains sample projects written in **AAYU** - The Intent-to-Silicon Programming Language. AAYU is a single-file, full-stack, zero-dependency language built for the modern era.

## 📂 What's Inside?

Here are the sample .aayu files included in this repo. Each file is heavily commented so you can understand exactly how AAYU works under the hood.

### 1. ayu_webpage.aayu
Demonstrates AAYU's ability to act as a reactive, full-stack web framework.
- Defines state variables.
- Uses declarative UI syntax (like Flutter/SwiftUI).
- Includes click listeners that mutate state instantly.

### 2. calculator.aayu
Demonstrates AAYU's command-line capabilities and synchronous execution.
- Shows how to use the input() function to pause the VM and take user input.
- Showcases type-casting (e.g., loat()).
- Implements basic math and control flow (if statements).

### 3. power_test.aayu
A basic sanity check script to verify syntax and math operations on the VM.
- Shows variable declaration (let).
- Demonstrates AAYU's internal math routing.

## ⚡ How to Run
To run any of these files, you need the AAYU compiler installed globally.

Run a terminal script:
``bash
aayu run calculator.aayu
``

Run a web server script:
``bash
aayu run aayu_webpage.aayu --web
``

---
*Built with ❤️ using AAYU.*