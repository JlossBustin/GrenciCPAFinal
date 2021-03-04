# GrenciCPA

-----

### Final Version of GrenciCPA program
##### CIS 411

*Victor Stahlman*: vicstahlman@gmail.com, *Justin Bloss*: justinbloss14@hotmail.com, *William Hoffman*: whoffman21279@gmail.com, *Cameron Weaver*: C.G.Weaver@eagle.clarion.edu

Contact Victor Stahlman or Justin Bloss for updates, modification requests or bug reports.

----

### Prerequisites:
Visual Studio 2017/2019

Microsoft SQL Server Management Studio 18

SQL Server 19

C#, SQL

----

### Description:
GrenciCPA was a 15 week long project designed with the purpose of being used by a client selected by the professor of the course. The project was based around the idea that the client needed a program that could store, add, and manipulate client information and track work done for each client in an accounting environment via databases.

The benefit of using the program is efficiency, it has the ability to pull from multiple databases on each page to minimize time spent searching for client information, cost of services, and amounts paid/owed. Almost everything is automated aside from inputting services and new client information initially.

**Implemented for Quality of Life:**
  - Automatically generated invoices in PDF format with respective client information and jobs performed
    - Option to either email or print out PDF
  - Timer on JobScreen page to track how long a given job took easily (with ability to add and deduct time in case of human error)
  - Search bars on most pages including a datagridview for quick and easy findings
  - Reports page:
    - Tracks billed, paid and still owed for each client
    - Finds work completed on given date inputted by user (YYYY-MM-DD format)
  - Invoices page:
    - Displays current PDF's generated upon job completion
    - Shows "who owes what" and grants user the ability to have a client make a payment
    - File path to PDFs displayed

----

### IMPORTANT:
To use the program, you must change the Data Source located in the connection string in **App.config** to your SQL Server Management Studio server name.

----

Original repo: https://github.com/vcstahlman/GrenciCPA

Updated: 3/4/21
