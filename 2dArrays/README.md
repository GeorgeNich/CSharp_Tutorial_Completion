# 2D Arrays Example

## Overview

This repository contains a simple C# console application that demonstrates the usage of 2D arrays. The program initializes a 2D array, accesses a specific element, and prints the result to the console.

## Project Structure

- `Program.cs`: The main C# file containing the source code.
- `_2dArrays.csproj`: The project file specifying the configuration and dependencies.

## Usage

1. Ensure you have [.NET Core](https://dotnet.microsoft.com/download) installed on your machine.
2. Clone this repository:

    ```bash
    git clone https://github.com/your-username/2d-arrays.git
    ```

3. Navigate to the project directory:

    ```bash
    cd 2d-arrays
    ```

4. Build and run the application:

    ```bash
    dotnet build
    dotnet run
    ```

## Example Output

The program initializes a 2D array:

    ```csharp
      int[,] numberGrid = { 
          {1, 2},
          {3, 4},
          {5, 6}
      };
      ```
It then accesses a specific element and prints the result to the console:
  
 ```csharp
    Console.WriteLine(numberGrid[2, 1]);
  ```

## License

This project is dedicated to the public domain under the [Unlicense](UNLICENSE).
