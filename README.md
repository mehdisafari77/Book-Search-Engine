# Book-Search-Engine

## Deployed Link
https://book-search-engine-mehdi.herokuapp.com/

## Summary
This is a fullstack book search engine connected to google, users are able to  create accounts and be authenticated, and add books to their saved books section.

## Screenshot Of Website
<img width="998" alt="Screenshot 2021-11-29 at 19 07 15" src="https://user-images.githubusercontent.com/75599021/143993903-bf07e408-b91e-4d51-9b15-ee3cd5c54dfa.png">

## Built With
* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [Node.js](https://nodejs.org/en/docs/)
* [NPM-Library](https://docs.npmjs.com/)
* [Expres.js](https://expressjs.com/)
* [React.js] (https://reactjs.org/)
* [Apollo] (https://www.apollographql.com/)

## Installation Steps For Local Running
1. Clone project.
2. Open terminal and run these commands in order
    - npm install
    - npm run develop

## Code Snippet Of typeDefs 
```javascript
const typeDefs = gql`
  type User {
    _id: ID
    username: String
    email: String
    bookCount: Int
    savedBooks: [Book]
  }

  type Book {
    bookId: ID
    authors: [String]
    description: String
    title: String
    image: String
    link: String
  }

  type Auth {
    token: ID!
    user: User
  }
```

## Author

* **Mehdi Safari**

- [Link to Portfolio Site](https://mehdisafari77.github.io/Basic-Bio/)
- [Link to Github](https://github.com/mehdisafari77)
- [Link to LinkedIn](https://www.linkedin.com/in/mehdi-safari-992799142/)
