# Friendzy

A simple **CRUD** application for managing a friends list, built with **Ruby on Rails**. This project demonstrates the core concepts of a standard Rails application.

---

## Key Features

* **Full CRUD Functionality**: Create, Read, Update, and Delete friend records.
* **Server-Side Rendering**: Uses standard Rails views with ERB.
* **Data Validation**: Includes basic model-level validations for friend attributes.
* **Built-in Testing**: Comes with a test suite to ensure functionality.

---

## Getting Started

Follow these instructions to get a copy of the project running on your local machine.

### Prerequisites

* **Ruby** (3.x recommended)
* **Ruby on Rails** (7.x recommended)
* **Node.js** & **Yarn**
* **SQLite3** (or another SQL database like PostgreSQL)

### Installation

1.  **Clone the repository and navigate to the app directory:**
    ```bash
    git clone [https://github.com/prnv007-rgb/Friendzy.git](https://github.com/prnv007-rgb/Friendzy.git)
    cd Friendzy/railsfriends
    ```

2.  **Install dependencies:**
    ```bash
    bundle install
    yarn install
    ```

3.  **Set up the database:**
    ```bash
    rails db:create
    rails db:migrate
    ```

---

## Usage

1.  **Start the Rails server:**
    ```bash
    rails server
    ```
2.  Open your browser and go to **`http://localhost:3000`**.

---

## Running Tests

To run the test suite, execute the following command:
```bash
rails test
