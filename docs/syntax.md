# Basics commands.

Markdown syntax is a lighweight markup language for creating formatted text. 
**John Gruber** and **Aaron Swartz** created Markdown in 2004.

## Titles 

# Heading level 1 
Syntax: ``# Heading level 1``      

### Heading level 2
Syntax:
``## Heading level 2``

### Heading level 3
Syntax:
``#### Heading level 3``

#### Heading level 4
Syntax:
``##### Heading level 4``

##### Heading level 5
Syntax:
``##### Heading level 5``

###### Heading level 6
Syntax:
``###### Heading level 6``

## Bold

This is a paragraph with **bold character**. 
The sistax is: ``** Your Text **``

## Italic

This is a paragraph with *italic character*. 
The sistax is: ``* Your Text *``

## Bold and Italic 

This is a paragraph with ***bold character***. 
The sistax is: ``*** Your Text ***``

## Order List

You need to write a some number with one dot

1. Item 1
2. Item 2

## Unorder List

Sintax: ``* Item 1`` or `` - Item 1`` or ``+ Item 1``
 
* Item 1 
* Item 2 

## Images 

Sintax:  `![Gato](./gato-risa.jpeg)`.<br>
![Gato](./gato-risa.jpeg)



## Tables 

To add a table, use three or more  hypherns ``---`` to create each column´s header. 
Use pipes ``|`` to separate each column.

##### Syntax:

```
| Syntax    | Description |
|   ---     |    ---      |
| Header    |    Title    |
| Paragraph 1 |    Text 1    |
| Paragraph 2 |    Text 2    |
```

##### Render:
| Syntax      | Description |
|   ---       |     ---     |
| Header      | Title       |
| Paragraph 1 | Text 1      |
| Paragraph 2 |    Text 2   |

## Alignment Tables

##### Syntax:

```
| Syntax          | Description          | Test Text       |
|   :---          |       :---:          |       ---:      |
|  Left Alignment |    Center Alignment  | Right Alignment |
| Paragraph 1     |    Text 1            |     Text 1      |
| Paragraph 2     |    Text 2            |     Text 2      |
```

##### Render:

| Syntax    | Description | Test Text|
|   :---     |    :---:      | ---:  |
| Left Alignment   |    Center Alignment   | Right Alignment |
| Paragraph 1 |    Text 1    |  Text 1  |
| Paragraph 2 |    Text 2    |  Text 2  |

## Block of code 

If we can write a block of code like one Json. You need to write `` ``` `` at the begining and other `` ``` `` at the end.
##### Syntax:
`` ``` ``
```
var myObject = {
    name = "Sergio",
    nameExample = "Block of code",
    GitHub = "https://github.com/sergio-gonzalez-sainz"
}
```
`` ``` ``
##### Render:
```
var myObject = {
    name = "Sergio",
    nameExample = "Block of code",
    GitHub = "https://github.com/sergio-gonzalez-sainz"
}
```