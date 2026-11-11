# Backend Service

A simple Go backend service for pg-app.

## Prerequisites

- Go 1.26.7 or higher

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd pg-app/backend
   ```

2. Install dependencies (if any):
   ```bash
   go mod download
   ```

## Running the Service

To run the backend service:

```bash
cd backend
go run main.go
```

This will start the server and print "Hello, World!" to the console.

## Building

To build the executable:

```bash
go build -o backend main.go
```

This will create an executable named `backend` in the current directory.

## Project Structure

```
backend/
├── main.go          # Main application entry point
├── go.mod           # Go module definition
├── README.md        # This file
└── .gitignore       # Git ignore patterns
```

## License

This project is part of the pg-app application.
