# GO with the flow

> The most basic Go project imaginable... 😊

This project demonstrates how to set up and run a simple Go module that prints a greeting message to the terminal.

## Requirements

To run this project, you need to have Go installed on your system.

## Installation

1.  **Install Go (Linux/macOS/Windows)**

    - **Linux:**
      ```bash
      sudo apt update
      sudo apt install -y golang-go
      ```
      This command installs the Go compiler and tools on Debian/Ubuntu-based systems.
    - **macOS:** Download the installer from [the official Go website](https://go.dev/doc/install) and follow the prompts.
    - **Windows:** Download the installer from [the official Go website](https://go.dev/doc/install) and follow the prompts.

2.  **Verify Go Installation**

    Open your terminal or command prompt and run:

    ```bash
    go version
    ```

    This should display the installed Go version, confirming a successful installation.

## Usage

1.  **Clone the Repository (if not already done):**

    ```bash
    git clone https://github.com/kevindmorris/go-with-the-flow.git
    cd go-with-the-flow
    ```

2.  **Run the Module:**

    ```bash
    go mod tidy
    ```

    This command adds all module requirements and sums.

    ```bash
    go run .
    ```

    This command compiles and executes the `main.go` file within the current directory, which defines the entry point of your Go program.

3.  **Expected Output:**

    ```
    // => returns a greeting.
    ```
