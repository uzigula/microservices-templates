# node-microservices-example
Using HTTP GET (without parameters)
---
The main goal here is coding a microservices example using Node and TypeScript

**How to run the code** </br>

Run this command in the console:
```
npm start
```
If everything is okay, you'll see this message:
```
Server started on port 3000
````

**How to test the code** </br>
You can also use the terminal :)

```
curl http://localhost:3000/books
```

You'll see:
```
[{"title":"Code Complete 2nd Edition","author":"Steve McConnell","year":"2004"},{"title":"Clean Code","author":"Robert C. Martin","year":"2008"},{"title":"The Last Lecture","author":"Randy Pausch","year":"2008"}]
```

If you don't like the terminal you can use Postman :D