# A Short Exercise to Explore Object-Oriented Programming - C# - Encapsulation

---
## Overview

This repository is a short exercise designed for you to explore **Encapsulation** which is one of the
four pillars of Object-Oriented Programming (OOP).

---
## 📖 Instructions

- Fork this repository

- To run the program, go to [Program.cs](/Encapsulation/Encapsulation/Program.cs) which is the entry point and run it using Visual Studio.

- 💡 You will notice that as of .NET 6+, the code you would need to write for a new program has been simplified. You can learn more [here](https://docs.microsoft.com/en-us/dotnet/core/tutorials/top-level-templates).

- There are two models `DodgyBankAccount` and `SecureBankAccount`, these are located in the [Models](/Encapsulation/Encapsulation/Models/) directory.

---
## 🤓 Study Prompts

Use the following questions to guide your exploration and learning! 🗺

- Run your Console application, what is it doing? What is being outputted to the console?

- Look at the `DodgyBankAccount`, this class is not well-encapsulated. Can you note down the problems with how the class is designed, and the ways it is being misused?

- Compare and contrast the `DodgyBankAccount` and the `SecureBankAccount`, how is the `SecureBankAccount` different to the `DodgyBankAccount`? How is it designed to prevent it from being misused? Are there instances of better method names for clearer abstraction?

---
## 🐸 Extension Challenge

- Now that you've had the chance to explore a well-encapsulated vs. poorly-encapsulated class,
your next challenge is to put your newly minted skills into practice 💪!

- Refactor the `WeatherReporter` class located in the [Models](/Encapsulation/Encapsulation/Models/) directory.

- You may want to think about Encapsulation here. Do the methods follow the Single Responsibility Principle (SRP)? Are the method names suitable? Are there any magic numbers / hardcoded numbers in the code that needs to be represented by a constant? Are there better ways to write the code?

- As an added challenge, could you write some unit tests to test the class' methods?
