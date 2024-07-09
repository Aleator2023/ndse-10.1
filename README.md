// Данные о книгах 

## MongoDB Queries

### Insert Data

```json
db.books.insertMany([
  {
    title: "Идиот",
    description: "Роман о жизни князя Мышкина.",
    authors: "Федор Достоевский"
  },
  {
    title: "Сто лет одиночества",
    description: "История семьи Буэндиа в вымышленном городе Макондо.",
    authors: "Габриэль Гарсиа Маркес"
  }
])

