# Danubius Test

## Short questions

- What is GIT? What is it used for and what kind of
situations is it designed to solve/make it easier?

```
GIT is a version control system which helps software development is terms of developing a new feature on a different branch without changing production code.
Also helps revert your changes in the sourc code to a previews version with ease.
```

- What is HTTP? What kind of HTTP methods are you
familiar with? What are their characteristics?

```
HTTP stands for Hyper Text Transfer Protocol. This is the main protocol to transfer the content of a website between server and client.
GET = Read a record
POST = Create a record
DELETE = Delete a record
PUT = Update a record
```

- What is the difference between HTTP and HTTPS?

```
HTTPS is the secure version of HTTP. With this protocol the communication will be performed over an encrypted transport layer. Encrypted earlier with SSL, but nowadays with TLS. 
```

- What do you know about the following HTML tags?
What are their characteristics and when do we use them?
  - `<div>`  ```It creates a new block, which comes into a new line(in standard cases)``` 
  - `<span>`   ```It crates an inline element```
  - `<p>`   ```It creates a new pharagraph```
  - `<a href="...">...</a>`   ```It creates an anchor, which can be also a new link to another website```

- What do you know about dependency injection?
What is it used for? What is its advantage?

```
When we create a new instance of something and we want to use it in different places of our program, in this way, we don't need to creat a new instance every time.
We can inject the original instance into different places of our program.
In JAVA we can use the Autowire and Beans annotations to do that. 
```

- Briefly describe a current topic in the IT field
that you are interested in!

```

```

## Programming task

Given a table that contains units and multipliers
that belongs to them. The multipliers tell you what
is the number that you need to multiply the value
with if you'd like to calculate the base unit.
The base units for example: liter, meter, etc...
Those that doesn't have a metric prefix.

### Length

| Unit | Value |
|------|-------|
| mm   | 0.001 |
| cm   | 0.01  |
| dm   | 0.1   |
| m    | 1     |
| km   | 1000  |

### Weight

| Unit | Value   |
|------|---------|
| mg   | 0.001   |
| g    | 1       |
| dkg  | 10      |
| kg   | 1000    |
| t    | 1000000 |

### Task

Create a data structure(could be a class but also
any type of combination of primitive types, array,
but also the series of well named variables) which
is suitable to store the values in the table and
makes the implementation of the exercises below easier(You don't have to
implement the actual operations they are just there
as an example).

- List a given type(e.g.: Length) of measurement units.
For example: mm, cm, dm, m, km
- Query of the multipliers.
For example: input -> km, output -> 1000
- Given an actual unit, return the value in the base unit.
For example: input -> "1200 cm", output -> 12

Initialize the datastructure with example inputs.

```JavaScript
const length = { mm: 0.001, cm: 0.01, dm: 0.1, m: 1, km: 1000, };

console.log(Object.entities(length));

let input = 'km';

if (length.hasOwnProperty(input)) {
 console.log(length.key(input));
} else {
 console.log('Input is not a unit of lenght');
}

input = '1200 cm';
let inputParts[] = input.split(' ');

if (length.hasOwnProperty(inputParts[1])) {
 console.log(inputParts[0] * length.valueOf(inputParts[1]));
} else {
 console.log('Input is not a unit of lenght');
}
```
