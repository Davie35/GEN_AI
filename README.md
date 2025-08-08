
## 🧠 1. **Title:**

 Getting Started with Go (Golang) – A Beginner’s Toolkit

**Objective:**

* **Chosen Tech:** Go (Golang)
* **Why Go?** It’s a lightweight, compiled language with a simple syntax. It's ideal for writing fast, reliable software, and its setup is straightforward.
* **Goal:** Build and run a "Hello, World!" program using Go and document the process for beginners.

---

## 📌 2. Quick Summary of the Technology

**What is it?**
Go is an open-source programming language developed by Google. It’s known for its simplicity, speed, and excellent support for concurrency.

**Where is it used?**

* Building web servers
* CLI tools
* Cloud-native applications (e.g., Docker and Kubernetes are written in Go)

**Real-World Example:**
Kubernetes, one of the most popular container orchestration platforms, is written in Go.

---

## 💻 3. System Requirements

| Component      | Description                  |
| -------------- | ---------------------------- |
| OS             | Windows, Linux, or macOS     |
| Editor         | VS Code (recommended)        |
| Runtime        | Go SDK (1.22 or latest)      |
| Optional Tools | Git, Terminal/Command Prompt |

---

## ⚙️ 4. Installation & Setup Instructions

### 🔹 Step-by-Step

#### 1. Download Go

Visit: [https://go.dev/dl/](https://go.dev/dl/)
Download the installer for your OS and follow the setup instructions.

#### 2. Verify Installation

```bash
go version
```

*Expected Output:*

```
go version go1.22.0 linux/amd64
```

#### 3. Create a Project Folder

```bash
mkdir hello-go
cd hello-go
```

#### 4. Create the Go File

```bash
touch main.go
```

Or create it manually in your text editor.

---

## 🧪 5. Minimal Working Example

**Code: `main.go`**

```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, Go!")
}
```

**What it does:**
Prints `"Hello, Go!"` to the terminal.

**Run It:**

```bash
go run main.go
```

**Expected Output:**

```
Hello, Go!
```

---

## ✨ 6. AI Prompt Journal (with Curriculum Links)

| Prompt Used                                                | Curriculum Link                                    | Summary of AI's Help                                                              | Rating |
| ---------------------------------------------------------- | -------------------------------------------------- | --------------------------------------------------------------------------------- | ------ |
| “How do I install Go on Linux/Windows?”                    | **Learning a new programming language**            | Helped me find the official download page, gave exact install steps for both OSes | ⭐⭐⭐⭐   |
| “Write a Hello World in Golang”                            | **Learning a new programming language**            | Provided basic syntax, explained structure of a Go program                        | ⭐⭐⭐⭐⭐  |
| “How to run a Go file from terminal?”                      | **Learning a new programming language**            | Explained `go run`, `go build`, and the purpose of `main.go`                      | ⭐⭐⭐⭐   |
| “Explain what this Go function does”                       | **Using AI to comprehend existing codebases**      | Broke down the syntax and logic clearly, helped me understand types and functions | ⭐⭐⭐⭐   |
| “Generate a README for my Go project”                      | **Generating and Improving Documentation with AI** | Created a clean, beginner-friendly README with instructions                       | ⭐⭐⭐⭐⭐  |
| “Why is fmt.Println not printing anything?”                | **Using AI to debug errors**                       | Helped troubleshoot Go syntax and suggested checking the `main()` structure       | ⭐⭐⭐    |
| “How do I refactor this Go code to make it more readable?” | **Using AI to refactor and enhance code**          | Suggested variable renaming and function decomposition                            | ⭐⭐⭐⭐   |

---

## 🧩 7. Common Issues & Fixes

| Issue                     | Error Message           | Fix                                       | Reference                                     |
| ------------------------- | ----------------------- | ----------------------------------------- | --------------------------------------------- |
| Go not recognized         | `go: command not found` | Add Go to your system PATH                | [Go install docs](https://go.dev/doc/install) |
| Wrong output              | No output in terminal   | Check if `fmt.Println` is inside `main()` | StackOverflow                                 |


---

## 📚 8. References

* [Official Go Docs](https://go.dev/doc/)
* [Go by Example](https://gobyexample.com/)
* [Go Installation Guide](https://go.dev/doc/install)
* [Tour of Go](https://go.dev/tour)


