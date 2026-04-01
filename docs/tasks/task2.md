# Task 2: How to format notes in Obsidian

Obsidian notes are stored as Markdown files, which have a specific way of formatting text. This task will show you all the ways to format your text.

## Bolding and italicizing

Surrounding text in different amounts of asterisks (\*) results in your text being italic, bold, or both, as shown in the table below.

| Unformatted  | Formatted  |
| ------------ | ---------- |
| `*Italic*`   |  *Italic*  |
| `**Bold**`   |  **Bold**  |
| `***Both***` | ***Both*** |

## Creating headings

Additionally, you can create headings by using the hashtag symbol \#, with more hashtags resulting in a smaller heading.

```
# Heading 1
## Heading 2
### Heading 3
```

# Heading 1
## Heading 2
### Heading 3

## Writing equations

Obsidian also uses MathJax to interpret LaTeX equations, which allows for writing complex math equations. Surrounding an equation in dollar sign symbols \$ creates a math equation, which will render inline with other text unless you use two dollar sign symbols instead. Inline: $2x+3$ `$2x+3$`

```
$$2x+3$$
```

$$2x+3$$

## Creating lists

You can make numbered or bulleted lists in Obsidian by typing 1. or - and pressing space. Writing something and pressing enter will result in the next list item being created.

Numbered list:
```
1. Numbered list item
```

1. Numbered list item

Bulleted list:
```
- Bulleted list item
```

- Bulleted list item

You can even make checklists by typing - [ ] and pressing space.

## Creating tables

To create tables you can either right click and select *Insert -> Table* or type vertical and horizontal bars as shown below.

```
| Left column | Right column |
| ----------- | ------------ |
| Example     | Row 1        |
| Example 2   | Row 2        |
```

| Left column | Right column |
| ----------- | ------------ |
| Example     | Row 1        |
| Example 2   | Row 2        |

## Writing code blocks

To make a code block you can write three backticks (`) and optionally the programming language for highlighting, then press enter. Write your code and end the block by putting another three backticks on a new line. Alternatively, you can write inline code blocks by surrounding text in single backticks.

````
```java
public static void main(final String[] args) {
    List<Shape> list = ShapeLoader.loadShapes(Path.of("shapes.txt"));
    for (Shape shape : list) {
        System.out.println(shape);
    }
}
```
````

```java
public static void main(final String[] args) {
    List<Shape> list = ShapeLoader.loadShapes(Path.of("shapes.txt"));
    for (Shape shape : list) {
        System.out.println(shape);
    }
}
```
