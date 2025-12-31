Inventory Management System
A GUI-based desktop application developed in C# (WPF) that allows users to manage inventory records efficiently using CRUD operations, file-based storage, object-oriented programming, and basic multithreading.
________________________________________
📌 Project Overview
VPLAssist+ Inventory Management System is designed to help users maintain product records such as ID, name, category, price, and quantity through a visual interface.
The application eliminates manual record-keeping and automates calculations like total inventory value.
This project was developed as part of a Visual Programming Lab / CCP assignment.
________________________________________
✨ Features
•	✔ Add, Update, Delete inventory products
•	✔ Display records using DataGrid (WPF)
•	✔ Search products by name or category
•	✔ Automatic calculation of:
o	Total items
o	Total quantity
o	Total inventory value
•	✔ Persistent storage using JSON file
•	✔ Multithreading using Task.Run() to keep UI responsive
•	✔ Input validation & error handling
________________________________________
🛠 Technologies Used
•	Language: C#
•	Framework: WPF (.NET Framework / .NET)
•	IDE: Visual Studio
•	Serialization: Newtonsoft.Json
•	Architecture: OOP + Event-driven programming
________________________________________
🧩 System Design
Class Diagram
The system is designed using two main classes:
•	Product
o	Represents an inventory item
o	Stores product information and calculates total value
•	ProductRepository
o	Handles loading and saving product data
o	Manages JSON file operations
📷 Class Diagram Image:
(Add your uploaded UML image here in GitHub)
![Class Diagram](images/class-diagram.png)
________________________________________
📂 Project Structure
VPLAssistPlus/
│
├── Models/
│   └── Product.cs
│
├── Data/
│   └── ProductRepository.cs
│
├── MainWindow.xaml
├── MainWindow.xaml.cs
├── products.json
└── README.md
________________________________________
💾 Data Storage
•	Data is stored locally in products.json
•	JSON is used because it is:
o	Lightweight
o	Human-readable
o	Easy to maintain
•	Serialization handled using Newtonsoft.Json
________________________________________
⚙️ Multithreading
To prevent UI freezing:
•	Data loading, saving, and searching are executed on background threads
•	Implemented using Task.Run()
This ensures a smooth and responsive user experience.
________________________________________
🛡 Error Handling
•	Input validation for numeric and empty fields
•	try–catch blocks for file operations
•	User-friendly error messages via message boxes
________________________________________
🚀 How to Run
1.	Clone the repository:
2.	git clone https://github.com/your-username/VPLAssistPlus.git
3.	Open the solution in Visual Studio
4.	Install required NuGet package:
o	Newtonsoft.Json
5.	Build and run the project
________________________________________
📘 Academic Purpose
This project demonstrates:
•	Visual Programming concepts
•	GUI development
•	Object-Oriented Programming
•	File handling
•	Event-driven architecture
•	Basic multithreading
________________________________________
👤 Author
Anas Shahid
Visual Programming Lab Project
________________________________________
📄 License
This project is created for educational purposes only.

