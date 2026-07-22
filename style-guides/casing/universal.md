# Universal Casing Style Guide For Code in Kryft Studios.

| Type  | Casing | Exceptions|
| --    | --     | --        |
| Class | PascalCase | **Javascript**: The function is a constructor function |
| Method | camelCase |**Javascript**: The function is a variable value (Such as Symbol.*), **C++**: The function is a constructor/ destructor.|
| Types, Interfaces | SCREAMING_SNAKE_CASE | **Typescript**: The type/intf is an extension of a function/namespace/class |
| Variables, Properties, Private Fields | camelCase | Variable is an extension of another namespace/class/... |
| Constants, Constant Properties |SCREAMING_SNAKE_CASE | None |
| Enum | PascalCase | **Typescript**: The enum is an extension of a function/class/namespace |
| Enum Members | SCREAMING_SNAKE | None |
