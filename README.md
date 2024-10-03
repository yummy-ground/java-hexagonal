# About

---
I simply implemented a simple book rental service to study hexagonal.

### Domain
- **User**
  - Name
  - Age
  - Gender
  - Phone Number
- **Book**
  - Name
  - Author
  - Category
  - Publish Date
  - Quantity
- **Rental**
  - Start Date
  - End Date

### E.R.D
- `users`
  - `id`
  - `name`
  - `age`
  - `gender`
  - `phone`
- `books`
  - `name`
  - `author`
  - `category`
  - `publish_at`
  - `quantity`
- `rentals`
  - `id`
  - `user_id`
  - `book_id`
  - `start_at`
  - `end_at`


### UseCase
- **Start Book Rental**
- **End Book Rental**
- **Find Book**
  - by Rental Possibility
  - by Id (One)
  - by Author (Many)
  - by Name - `like` query(Many)
  - by Category (Many)
  - by Publish Date (Many)
    - Year query
    - Month query
    - Date query
  - by Quantity
- **Find Rental**
  - by Id (One)
  - by Book Name (Many)
  - by User Id (Many)

<br/>

# Try Out

---
> _I try to keep adding things I want to try..._
- [**TEST**] Package Dependency
  - _use Java `access modifier` as much as possible._
- []