# CSV to JSON Converter Utility

A Java mini project that converts CSV files to JSON format using Java, Regex, Streams, and Collections.

## Project Structure

```
CSV-to-JSON-Converter
│
├── src
│   └── com
│       └── wipro
│           └── csvconverter
│               ├── util
│               ├── model
│               ├── service
│               └── main
│
├── resources
│     employees.csv
│     output.json
│
├── lib
│     gson-2.10.1.jar
│
├── README.md
│
└── .gitignore
```

## Requirements

- Java 17 or higher (Java 26 is configured)
- Gson library (included in lib folder)

## Setup Instructions

### Prerequisites
1. Install Java JDK 17 or higher
2. Install VS Code with Java Extension Pack (recommended)

### VS Code Setup
1. Install the following extensions:
   - Java Extension Pack
   - Language Support for Java
   - Debugger for Java
   - Project Manager for Java

### Building and Running

#### Using VS Code Tasks
1. Open the project in VS Code
2. Press `Ctrl+Shift+B` to build
3. Run using the Run and Debug panel

#### Using Command Line
```powershell
# Compile
javac -d bin -sourcepath src -cp lib/* src/com/wipro/csvconverter/main/Main.java

# Run
java -cp bin;lib/* com.wipro.csvconverter.main.Main
```

## Features

- Parse CSV files using Java Regex
- Convert CSV data to JSON objects
- Use Java Streams for data processing
- Use Java Collections for data manipulation
- Generate formatted JSON output

## Dependencies

- Gson 2.10.1 (Google JSON library)

## License

This is a learning project for educational purposes.
