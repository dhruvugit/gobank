# **Go Bank Application**

A simple command-line banking application written in Go. This project demonstrates basic banking functionalities such as checking balance, depositing money, and withdrawing money, while persisting the balance to a file for future use.
(This application is built to just understand the syntax of Go, it's not a fancy web app)

---

## **Features**

- **Check Balance**: View your current account balance.
- **Deposit Money**: Add funds to your account.
- **Withdraw Money**: Deduct funds with validation to prevent overdrafts.
- **Data Persistence**: Account balance is saved to a file (`balance.txt`) for future sessions.

---

## **Getting Started**

Follow these steps to set up and run the application on your local machine.

### **Prerequisites**

- Go 1.16 or later installed on your system. [Download Go](https://go.dev/dl/).

### **Installation**

1. **Clone the Repository**  
   Run the following command in your terminal:
   ```bash
   `git clone https://github.com/yourusername/gobank.git`
   `cd gobank`

2. **Build the Application**
   Use the go build command to build the executable and then run it:
   ```bash
   `go build -o gobank`
   `./gobank`

