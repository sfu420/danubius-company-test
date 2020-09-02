# Danubius Test

## Short questions

- What is GIT? What is it used for and what kind of
situations is it designed to solve/make it easier?

- What is HTTP? What kind of HTTP methods are you
familiar with? What are their characteristics?

- What is the difference between HTTP and HTTPS?

- What do you know about the following HTML tags?
What are their characteristics and when do we use them?
  - `<div>`
  - `<span>`
  - `<p>`
  - `<a href="...">...</a>`

- What do you know about dependency injection?
What is it used for? What is its advantage?

- Briefly describe a current topic in the IT field
that you are interested in!

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

Create a data structure (could be a class but also
any type of combination of primitive types, array,
but also the series of well named variables) which
is suitable to store the values in the table and
makes the implementation of the exercises below easier (You don't have to
implement the actual operations they are just there
as an example).

- List a given type (e.g.: Length) of measurement units.
For example: mm, cm, dm, m, km
- Query of the multipliers.
For example: input -> km, output -> 1000
- Given an actual unit, return the value in the base unit.
For example: input -> "1200 cm", output -> 12

Initialize the datastructure with example inputs.

