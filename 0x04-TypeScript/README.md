TypeScript is a strongly typed programming language that builds on JavaScript, adding syntax for types1. This allows for better tooling and editor support, and can help catch errors early in your development process1. TypeScript code converts to JavaScript, which can run anywhere JavaScript runs: in a browser, on Node.js or Deno, and in your apps1.

TypeScript allows you to describe the shape of objects and functions in your code, making it possible to see documentation and issues in your editor1. For example, you can define an interface for an account like this:

interface Account {
    id: number;
    displayName: string;
    version: 1;
}
Copy
And then use it in a function like this:

function welcome(user: Account) {
    console.log(user.id);
}
Copy
This way, TypeScript provides a way to add static types to JavaScript, helping you write more robust and maintainable code1. 
