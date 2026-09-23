# Library Management System (C)

A console-based library management system written in C. It stores up to 100 books in memory and is driven by a simple menu.

## Features

| Option | Action |
|---|---|
| 1. Add Book | Enter a book ID, title, author and publication year |
| 2. Remove Book | Delete a book by its ID |
| 3. Display All Books | List every book in the library |
| 4. Exit | Close the program |

## Data Model

```c
struct Book {
    int  bookID;
    char title[50];
    char author[50];
    int  year;
};
```

## Build and Run

```bash
gcc Library.c -o library
./library
```

On Windows, run `library.exe` instead.

## Concepts Practised

Structs · arrays · menu-driven programs · input handling with `scanf`
