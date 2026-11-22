# Filipe Teixeira

Hi! I'm Filipe, a Software Engineer based in Luzern, Switzerland.

I've worked on projects across energy, medical devices, metrology, telecommunications, and transportation. This page highlights some of the personal projects I've built or contributed to.

> [!NOTE]
> Some of my work is private, either personal or tied to the companies I've worked with, so it isn't listed here.

## Featured

### [Customer Store API](https://github.com/filipeoliv02/customer-store-api)
A RESTful back end for an eCommerce application, built with C# and .NET following Clean Architecture.

- Create, retrieve, filter (by name or email), and delete customers, with unique-email enforcement
- Enriches customer records with geolocation data from the PositionStack API, configured via environment variables
- Entity Framework with an in-memory database for development and testing
- Dedicated unit test project

**Stack:** C# · .NET · Entity Framework · REST

## Projects

### Go

#### [Go Coin API](https://github.com/filipeoliv02/Go-Coin-API)
An HTTP API for retrieving coin account balances, returning structured JSON and handling error conditions gracefully. Built entirely on Go's standard library, with a GitHub Actions workflow that builds and tests every push and pull request.

**Stack:** Go · `net/http` · `encoding/json` · GitHub Actions

### Java

#### [Random Player Generator](https://github.com/filipeoliv02/random-player-generator)
Generates random players with names, countries, stats, and physical attributes, using data loaded from text files.

**Stack:** Java · File I/O · OOP

### C#

#### [SiUFP Grades](https://github.com/filipeoliv02/SiufpGrades)
Automates grade checking on a university portal that has no notifications of its own. It logs in, detects newly published grades, and alerts the user.

**Stack:** C# · Selenium · Web automation

### C

#### [Sudoku X Solver](https://github.com/filipeoliv02/Sudoku_X_Solver)
Generates and solves Sudoku X puzzles, a variant with two extra diagonal constraints, at varying difficulty levels using multiple solving algorithms.

**Stack:** C · Recursive algorithms · Multidimensional arrays

#### [Reservation System](https://github.com/filipeoliv02/Reservation-System)
A reservation manager for a local accommodation company. It syncs calendars across rental platforms, schedules cleaning and maintenance, resolves overbookings, and calculates dynamic pricing.

**Stack:** C · Linked lists · Dynamic arrays · Binary search · Manual memory management

### Shell

#### [PDF Search](https://github.com/filipeoliv02/pdf-search/)
Searches for a string across all PDFs in a directory, optionally recursively, and shows the matches in an interactive menu that opens the selected file.

**Stack:** Bash · `pdfgrep` · `xdg-open`
