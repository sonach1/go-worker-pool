# Go Worker Pool System

This is a lightweight and concurrent Worker Pool and Job Queue system written in Go. It supports multiple worker pools running concurrently, such as:

- ✅ **Email Dispatch Queue** – sends emails asynchronously.
- 📄 **Log Processor Queue** – processes and stores logs in the background.

---

## 🚀 Features

- Efficient use of goroutines and channels.
- Graceful shutdown of all workers.
- Modular job types (`EmailJob`, `LogJob`) via interfaces.
- Easy to extend (add retries, priorities, metrics).

---

## 📦 Structure

```text
main.go         # Entry point, sets up both dispatchers
README.md       # Project documentation
.gitignore      # Ignored files/folders
go.mod          # Go module file
