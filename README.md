# 🥖 Lehem Havita - The Game

### By: Itay Vazana & Assaf Milner

---

## 📌 Project Overview

Lehem Havita - The Game is a **desktop game for Windows**, developed in **C#** using **Visual Studio 2019** and built upon **object-oriented programming (OOP)** principles.  
This project was created as the **final project** for the **Object-Oriented Programming** course during the first year of my Computer Science degree.

The game is inspired by the viral **"Lehem Havita" TikTok trend**, which gained popularity across Israel in early 2023.  
The gameplay and design revolve around the theme of **Lehem Havita**, a popular sandwich shop in Netanya, Israel.

---

## 🕹️ Platform & Technologies

- **Platform:** Windows (PC)
- **Language:** C#
- **Development Environment:** Visual Studio 2019
- **Framework:** .NET Framework 4.7.2
- **Database:** Local MDF file (SQL Server)

---

## 🎮 Game Concept

Players manage a sandwich shop, where they must **catch falling ingredients** and **avoid harmful objects**, all while completing sandwich orders correctly and within the time limit.

The game implements:
- **Real-time object movement and player control**
- **Order system that dynamically updates based on player actions**
- **Score and lives management system**
- **Visual feedback and graphical object representations**
- **A persistent high-score table stored in a local database**

---

## 🛠️ Object-Oriented Structure

The project follows a clear **OOP hierarchy**, including:

### Core Classes
- **GameState** - Controls game flow, object management, and player interaction.
- **Player** - Represents the player, including score and lives management.
- **Order** - Manages sandwich orders and updates the display accordingly.
- **FallingItem** - Base class for all falling objects (ingredients and obstacles).

### Ingredients (Falling Items)
- Objects that can be part of the sandwich order.
- Examples: Egg, Tomato, Cucumber, Mayo.
- Each has its own **score value** and visual representation.

### Not Ingredients (Obstacles)
- Objects that cannot be part of the sandwich and may negatively affect the player.
- Examples: Cockroach, Bomb, Clock.
- Each object has its own effect on **time, score, or player lives**.

---

## 🗂️ Game Flow & Mechanics

- Players use the **mouse to control the player cursor**, catching ingredients or avoiding obstacles.
- Completed sandwiches increase the score.
- Incorrect or missing ingredients reduce the score or lives.
- Real-time **timers** and **event-driven programming** manage object falling speed and order updates.
- Visual elements such as **ingredient images**, **order panels**, and **score/life counters** provide live feedback.

---

## 💾 Database Integration

- A **local MDF database file** stores **high scores**.
- Players can view high scores via the **Score History** screen.
- Admins can **reset the high score table** using a **password-protected form**.
- SQL queries are executed via a **DataSet**, handling data storage, retrieval, and updates.

---

## 📊 Key Screens

- **Main Menu**
- **Player Registration & Difficulty Selection**
- **In-Game Screen with Real-Time Order & Score Display**
- **Game Over Screen with Final Score**
- **High Score Table**
- **Admin Reset Screen (Password Protected)**
- **Help Screen**

---

## 🔑 Key OOP Concepts Applied

- ✅ **Encapsulation** - Private fields and controlled access.
- ✅ **Inheritance** - `FallingItem` base class with `Ingredient` and `NotIngredient` subclasses.
- ✅ **Polymorphism** - Objects are managed and processed via their base class type.
- ✅ **Dynamic Object Collection Management** - Real-time list management for falling objects.
- ✅ **Event-Driven Programming** - Game responds to timers, mouse events, and user inputs.

---

## ⚠️ Project Status

This project was developed as a **course requirement**, and no further updates are planned.  
The repository serves as an **archive** demonstrating **early programming projects and growth**.

---

## 📧 Contact

For more information, feel free to contact me through my GitHub profile:  
[Itay Vazana on GitHub](https://github.com/ItayVazana1)

---

## ⭐️ If you found this project interesting, don't forget to star the repository!
