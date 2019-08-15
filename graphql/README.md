# GraphQL with DataFetcher
- `allBooks`
`{
   allBooks {
     isn
     title
     authors
     publisher
   }
 }`
- `book`
`{
   book(id: "123") {
     title
     authors
     publisher
   }
}`
- Combination of both `allBooks` and `book`
`{
   allBooks {
     title
     authors
   }
   book(id: "124") {
     title
     authors
     publisher
   }
}`