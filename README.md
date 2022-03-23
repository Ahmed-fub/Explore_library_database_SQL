# Explore_library_db_SQLite

## Data 
Library data base  

It Includes different tables: 

1. Patrons
2. Books
3. Loans

- Books table include columns :  
 BookID (PK)	 , Title , Author ,	Published , Barcode

- Patrons: FirstName ,	LastName ,	Email ,	PatronID(PK)

- Loans  : LoanID(PK)	 , BookID(FK) ,	PatronID(FK)	, LoanDate ,	DueDate	 , ReturnedDate

## Tools : 
- Python with SQLite sqlite3 , Pandas 


## challenges

1. Explore the available of some books in library
2. Insert new copies from some books to Library to Books table 
3. Check the people who should return their books back to librarz on 17 July 2020
4. The number of loaning books for each person
5. How many books published every year  
