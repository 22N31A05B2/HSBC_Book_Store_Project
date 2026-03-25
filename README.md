# HSBC Book Store Project using MERN Stack

This is a full-stack web application for a book store built using the MERN stack (MongoDB, Express.js, React.js, Node.js). Users can browse through a collection of books, search for specific titles, view details of each book, add them to their cart for purchase, create new books, edit existing books, and delete books.

## Features
1. **Show Books:** Browse through a collection of books using cards and tables.
2. **Create New Books:** Add new books to the collection.
3. **Edit Existing Books:** Modify details of existing books.
4. **Delete Books:** Remove books from the collection.
5. **Show Description:** View detailed description of each book.
6. **Database Support**: Abilty to retain information for a long time.

## Installation
1. Clone the repository to your local machine:
    ```
    git clone https://github.com/22N31A05B2/book-store.git
    ```

2. Navigate to the project directory:
    ```
    cd HSBC_Book_Store_Project
    ```

3. Install dependencies for both frontend and backend:
    ```
    npm install
    cd ./frontend
    npm install
    ```

4. Create a `.env` file in the root directory of the project:

    ```
    PORT=3000
    mongoDBURL="your_mongodb_url"
    ```

    Replace `your_mongodb_url` with the URL of your MongoDB database.


5. Navigate to backend folder and run:
    ```
    cd backend
    npm install
    npm run dev
    ```

6. Start the client:
    ```
    cd frontend
    npm install
    npm run dev
    ```

7. Open your browser and navigate to `http://localhost:5173` to view the application.

## Usage
- As a user, you can browse through the collection of books using cards and tables, view detailed descriptions of each book, and add them to your cart for purchase.
- If you are an admin, you can access the admin panel by logging in with your credentials. From there, you can manage books by creating new ones, editing existing ones, or deleting books.

## Technologies Used
- MongoDB
- Express.js
- React.js
- Node.js

## Contributors
- [RaviTejaKurapati](https://github.com/22N31A05B2)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
