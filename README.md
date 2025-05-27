# Mfon
A simple shopping cart console application written in C#.

![alt text](image.png)

## Features
- The application allows users to select products from a list of products.
- The application allows users to add products to their cart.
- The application allows users to enter their budget.
- The application determines if the total cost of the products in the users cart is below or above their budget.
- The application prints out a message saying if the cart items are below or above the budget and then says goodbye.

## How to use Cart System
1. Clone the repository.
2. Open the project in Visual Studio.
3. Press F5 to run the application.
4. Follow the prompts to select products, add them to your cart, enter your budget, and see the result.

## How it works
The application uses a `Cart` class to keep track of the products in the users cart. The `Cart` class contains a list of `Product` objects, which are added to the cart when the user selects a product. The application also uses a `Program` class to contain the main entry point for the application. The `Program` class is responsible for prompting the user for input, adding products to the cart, and determining if the total cost of the products in the cart is below or above the users budget.

## Bugs and Issues
If you find a bug or issue with the application, please open an issue in the GitHub repository. If you have a fix for the bug or issue, please feel free to submit a pull request.

## Requirements
- .NET SDK 9 or later
- Visual Studio Code or any C# compatible IDE

## How to run Program.cs
1. Open the project in Visual Studio.
2. Ensure you have the .NET SDK installed.
3. Open the terminal in Visual Studio or navigate to the project directory in your command line.
4. Run the command `dotnet run` to execute the application.
5. If you have .NET SDK 9, you can navigate to the projects `.csproj` file and change `<TargetFramework>net9.0</TargetFramework>` to your desired version if needed.
6. Follow the prompts in the console to interact with the application.

## License
The application is licensed under the MIT License. See the LICENSE file for more information.

## Author
The application was created by [Mfon Ekpo](https://github.com/mfonekpo).