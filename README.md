# AF-Lab-03-async

## 📋 Overview
This lab demonstrates three key concepts of Asynchronous JavaScript:

### 🔹 **JavaScript Callbacks**
A **callback** is a function passed as an argument to another function, which is then executed after some operation completes. Callbacks ensure that code doesn't block execution while waiting for operations to finish.

**Example:** Getting a greeting message after a user enters their name.

### 🔹 **JavaScript Promises**
A **Promise** is an object representing the eventual completion (or failure) of an asynchronous operation. It has three states:
- **Pending**: Initial state, neither fulfilled nor rejected
- **Fulfilled**: Operation completed successfully
- **Rejected**: Operation failed

**Example:** Validating student marks and returning success/error messages.

### 🔹 **JavaScript Async/Await**
**Async/await** is modern syntax that makes promises easier to write and read. 
- `async` makes a function return a Promise
- `await` makes JavaScript wait until the Promise settles

**Example:** Waiting 2 seconds before displaying a success message.

## 🚀 Files Structure
- `callbacks.html` - Demonstrates JavaScript callbacks with user greeting
- `promises.html` - Shows JavaScript promises with marks validation  
- `async-await.html` - Illustrates async/await with 2-second delay
- `README.md` - Project documentation

## 🔧 Technologies Used
- HTML5
- JavaScript
- Git & GitHub

## 📝 How to Run
1. Clone this repository
   ```bash
   git clone https://github.com/YOUR_USERNAME/lab-03-async-git.git