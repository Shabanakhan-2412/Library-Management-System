Library Management System
Overview
The Library Management System is a console-based Java application that allows users to manage a library's book inventory. It includes functionalities such as adding books, removing books, updating book information, and fetching book details.

Table of Contents
Features
Classes
Usage
Contributing
License
Features
Add Book: Users can add new books to the library.
Remove Book: Users can remove existing books from the library.
Update Book: Users can update the information of a specific book.
Get Book: Users can fetch and display details of a particular book.
Console Interface: The application provides a simple console-based interface for user interaction.
Classes
1. Library
Attributes:

libraryName: Name of the library.
libraryAddress: Address of the library.
pincode: Pincode of the library.
books: List of Book objects in the library.
Methods:

getLibraryName(), setLibraryName(String): Get and set methods for libraryName.
getLibraryAddress(), setLibraryAddress(String): Get and set methods for libraryAddress.
getPincode(), setPincode(int): Get and set methods for pincode.
getBooks(), setBooks(List<Book>): Get and set methods for books.
2. Book
Attributes:

bookName: Name of the book.
bookAuthor: Author of the book.
bookPrice: Price of the book.
Methods:

getBookName(), setBookName(String): Get and set methods for bookName.
getBookAuthor(), setBookAuthor(String): Get and set methods for bookAuthor.
getBookPrice(), setBookPrice(double): Get and set methods for bookPrice.
toString(): Override of the toString() method to provide a string representation.
3. View
Attributes:

library: Static instance of the Library class.
myInput: Scanner object for user input.
controller: Instance of the Controller class.
Methods:

getLibrary(), setLibrary(Library): Get and set methods for library.
main(String[]): Main method containing the user interface logic.
4. Controller
Attributes:

library: Instance of the Library class.
Methods:

addBook(Book): Adds a new book to the library.
getBook(String): Retrieves a book from the library based on its name.
update(Book, Book): Updates the information of a specific book.
removeBook(String): Removes a book from the library.
Usage
Clone the repository.
Open the project in your preferred Java development environment.
Run the View class to start the Library Management System.
Follow the on-screen instructions to perform various operations.
Contributing
Feel free to contribute to the project by forking the repository and creating pull requests. If you have suggestions, bug reports, or feature requests, please open an issue.

License
This project is licensed under the MIT License.


















### 5. Exit 

![image](https://github.com/Shabanakhan-2412/Library-Management-System/assets/162796897/7093da4d-4102-4f3e-844e-23a70b460713)




