# HelloWorldApp

This is a simple ASP.NET MVC application that demonstrates a basic "Hello World" functionality.

## Project Structure

- **Controllers**: Contains the controllers for the application.
  - `HomeController.cs`: Manages the home page.
  
- **Models**: This folder is currently empty but is intended for model classes that represent the data structure of the application.

- **Views**: Contains the views for the application.
  - **Home**: Contains views related to the home page.
    - `Index.cshtml`: Displays a "Hello World" message.
  - **Shared**: Contains shared views and layouts.
    - `_Layout.cshtml`: Defines the layout for the application.

- **wwwroot**: Contains static files for the application.
  - `css`: Intended for CSS files.
  - `js`: Intended for JavaScript files.
  - `lib`: Intended for third-party libraries or frameworks.

- **appsettings.json**: Contains configuration settings for the application.

- **Program.cs**: The entry point of the application.

- **Startup.cs**: Configures services and the app's request pipeline.

## Getting Started

To run the application, ensure you have the .NET SDK installed. Then, navigate to the project directory and use the following command:

```
dotnet run
```

Open your web browser and go to `http://localhost:5000` to see the "Hello World" message.