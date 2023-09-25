# This is ESLint
## Let's Learn an ESLint Rule
The rule states that if you do not add a semicolon at the end of your statments in Java
one will automatically be added for you. The problem is although this may work in most
cases it can also be confusing and cause errors if not done the right way. Such as
causing run time errors. There are rules which can be configured based on if it is an
object or string (both are always or never). String always will require semincolons
after while never does not. Object always will not allow semicolons when braces
are in the same line and the same thing while in a class. Object Never ignores
the semicolons at the end of statements but will require it if the line starts with
certain characters.
[EsLint Rules on Semi](https://eslint.org/docs/latest/rules/semi)