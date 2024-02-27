# Applying Variables and Mixins in SASS

In this section, we delve into two powerful features of SASS: variables and mixins. These features help in writing more readable, maintainable, and reusable CSS code.

## Objectives:
- Learn how to declare and use variables in SASS.
- Understand how to create and include mixins.
- Apply variables and mixins in a practical example.

## Variables
Variables in SASS are used to store values that you can reuse throughout your stylesheet. They can store colors, fonts, sizes, and more. Declaring a variable is done using the `$` symbol.

Example:
```scss
$primary-color: blue;

Mixins
Mixins allow you to define styles that can be reused throughout your stylesheet. They can also take arguments, making them even more flexible.

Example:

@mixin border-radius($radius) {
  -webkit-border-radius: $radius;
     -moz-border-radius: $radius;
          border-radius: $radius;
}

Practice
Create a simple webpage that utilizes both variables and mixins to style elements. Use the provided index.html and style.scss as your starting point.

