# Laravel Library Management  

## About the Project  
The Laravel Library Management project is a sample application designed to illustrate the development of software using the Laravel 11 framework.

## Models  
- **Books**: Contains attributes like title, author, publisher, publication year, type (Printed book or Ebook), and `is_approved` (request status).  
- **CDs**: Includes title, artist, genre, stock, and `is_approved` (request status) attributes.  
- **Journals**: Features attributes such as title, author, publish date, abstract, and `is_approved` (request status).  
- **Newspapers**: Comprises title, publisher (e.g., *Kompas*, *Tribun Timur*, *Fajar*), publish date, `is_available`, and `is_approved` (request status).  

## User Roles  
- **Admin**:  
  - Can add or remove librarians.  
  - Has the authority to approve or reject collection updates requested by librarians.  

- **Librarian**:  
  - Responsible for managing the library inventory, including creating, reading, updating, and deleting items.  
