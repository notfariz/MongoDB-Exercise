# MongoDB-Exercise

## Purpose
This document captures the list of MongoDB commands used, their purpose, and screenshots of each step taken during the exercise. The intent is to demonstrate working knowledge of basic MongoDB shell operations.

---

## Commands Used & Explanation

### Start MongoDB
```bash
brew services start mongodb/brew/mongodb-community

Why: Starts MongoDB server as a background macOS service.

### Connect to Shell
mongosh

<img width="2880" height="598" alt="image" src="https://github.com/user-attachments/assets/44f939dd-016b-451c-966a-ea7e6665d3b5" />

##1. Create a new database and switch to it.
Use "library"

// Create a collection named "books"

// Insert a document into the "books" collection

<img width="1440" height="702" alt="Screenshot 2025-07-27 at 9 39 30 PM" src="https://github.com/user-attachments/assets/01fdbb83-fc1a-4132-ab5f-4abed56776fe" />

###2. Read 
// Retrieve all documents from the "books" collection

<img width="1440" height="261" alt="Screenshot 2025-07-27 at 9 41 07 PM" src="https://github.com/user-attachments/assets/7499a5f0-6c87-41d5-b0ef-a1cb5424971f" />

// Find and display only the documents where the author is "F. Scott Fitzgerald"

<img width="1440" height="265" alt="Screenshot 2025-07-27 at 9 42 04 PM" src="https://github.com/user-attachments/assets/38bdb577-84cf-4432-ae82-141b8a0c35e1" />

// Fetch and display the document with the earliest published year

<img width="1440" height="175" alt="Screenshot 2025-07-27 at 9 42 53 PM" src="https://github.com/user-attachments/assets/76d10f2e-ab43-4572-b7c1-4d7ccbf8680e" />

###3. Update
// Update the published year of the book with the title "The Great Gatsby"

<img width="1440" height="397" alt="Screenshot 2025-07-27 at 9 44 15 PM" src="https://github.com/user-attachments/assets/6b9f2a11-dc0a-41bc-971e-063eab2f7b18" />

// Add a new field "genre" with the value "Mystery" to all documents

<img width="1440" height="460" alt="Screenshot 2025-07-27 at 9 44 37 PM" src="https://github.com/user-attachments/assets/724c9c13-6f11-4403-8f45-ee4143cd9709" />

###4. Delete
// Remove the document with the title "1984"

<img width="1440" height="815" alt="Screenshot 2025-07-27 at 10 25 53 PM" src="https://github.com/user-attachments/assets/1b439af9-49b5-4827-8972-c1af68b27930" />

// Delete all documents where the published year is before 2000

<img width="1440" height="272" alt="Screenshot 2025-07-27 at 10 30 18 PM" src="https://github.com/user-attachments/assets/e426f78d-b6e8-4a99-9922-585d4970af56" />











