# Guess the Number – Razor Pages App 🎯

This is a web-based application built with **.NET 8** and **Razor Pages**. The app allows users to enter two numbers (`A` and `B`) and validates the inputs using a custom **Endpoint Filter** before performing any logic. The goal is to enforce specific mathematical rules on the input and return appropriate feedback.

## 🚀 Features

- ✅ Built with **.NET 8** using **ASP.NET Razor Pages**
- ✅ Implements **Endpoint Filters** for input validation
- ✅ Stores results temporarily using **In-Memory Services**
- ✅ Clean UI built with Razor and Bootstrap

## 🔍 Input Validation Rules

The application checks the following:

1. `A` and `B` must be integers **≥ 1**
2. `A` and `B` must be integers **≤ 10**
3. `A` must be **less than** `B`
4. `B` must be an **even number** (multiple of 2)

If any of the above rules are violated, the app returns a **structured validation error message** using `Results.ValidationProblem`.

## 🧱 Tech Stack

- .NET 8
- ASP.NET Core Razor Pages
- C#
- Endpoint Filters (new in .NET 8)
- In-Memory Data Store

## 🖼️ UI Screens

- 📝 Razor Page Form for input (`A`, `B`)
- ✅ Displays success message when valid
- ❌ Shows validation errors inline when rules are broken

## 🛠 How to Run

1. Clone the repository
2. Open the folder in Visual Studio
3. Run the project


## 👨‍💻 Author
**Hussein El Mazbouh**  
Computer Science Graduate – Lebanese University  
📧 husseinelmazbouh1@gmail.com