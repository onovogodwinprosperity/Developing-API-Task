# Note-Taking API with TypeScript, Express, and MongoDB

This is a simple note-taking API built with **TypeScript**, **Node.js**, **Express**, and **MongoDB**. It allows users to create, read, update, and delete notes, as well as categorize notes and perform type-safe operations.

---

## Features

- **CRUD Operations for Notes**:
  - Create, read, update, and delete notes.
- **Categories**:
  - Each note can belong to a category.
- **Type Safety**:
  - TypeScript interfaces and validation ensure type safety.
- **Validation**:
  - Custom middleware validates note data using Zod.
- **Logging**:
  - Typed logging middleware tracks API requests.
- **Error Handling**:
  - Custom error classes for consistent error responses.

---

## Technologies Used

- **Node.js**: Runtime environment.
- **Express**: Web framework.
- **TypeScript**: Adds type safety and modern JavaScript features.
- **MongoDB**: Database for storing notes and categories.
- **Mongoose**: MongoDB object modeling for Node.js.
- **Zod**: Schema validation library.
- **Postman**: For testing the API.

---

## Setup and Installation

### Prerequisites

- Node.js (v16 or higher)
- MongoDB (local or cloud instance)
- Postman (for testing)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/note-taking-api.git
   cd note-taking-api
