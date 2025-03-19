# Vidly-MVC - ASP.NET MVC Demonstration Project

## Overview
**Vidly-MVC** is a simple web application built using **ASP.NET MVC** to demonstrate the **Model-View-Controller (MVC) architecture**. This project serves as an educational example, showcasing how to structure an ASP.NET MVC application, manage data, and handle user interactions efficiently.

## Features
- **ASP.NET MVC Architecture** for clear separation of concerns.
- **Entity Framework (EF)** for database interaction.
- **CRUD Operations** (Create, Read, Update, Delete) for managing data.
- **Bootstrap and jQuery** for frontend enhancements.
- **Routing & Controller Actions** to manage different pages.
- **Validation** using ASP.NET MVC Model Binding.

## Technologies Used
- **ASP.NET MVC (C#)**
- **Entity Framework (EF Core)**
- **SQL Server** for data storage
- **Bootstrap** for responsive UI
- **jQuery** for client-side interactivity

## Project Structure
```
Vidly-MVC/
│-- Controllers/      # Handles user requests
│-- Models/           # Represents application data
│-- Views/            # UI templates (Razor)
│-- Scripts/          # JavaScript and jQuery
│-- Content/          # CSS and frontend assets
│-- App_Data/         # Database files (if using local DB)
```

## Installation and Setup
1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-repo/Vidly-MVC.git
   ```

2. **Open in Visual Studio**
   - Open the `Vidly-MVC.sln` file in **Visual Studio**

3. **Restore Dependencies**
   - Open the **Package Manager Console** and run:
     ```sh
     Update-Package
     ```

4. **Configure Database**
   - Update the **connection string** in `web.config` to match your SQL Server setup.
   - Apply migrations using:
     ```sh
     Update-Database
     ```

5. **Run the Application**
   - Press `F5` or `Ctrl + F5` to start the development server.

## How It Works
- **Models:** Define the application data structure.
- **Views:** Render UI using Razor templates.
- **Controllers:** Handle user input and interaction.
- **Routing:** Maps URLs to controller actions.
- **Entity Framework:** Manages database operations.

## Contributing
Feel free to contribute by submitting pull requests to enhance the project.

## License
This project is licensed under the **MIT License**.

