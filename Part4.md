For more information:
[Part1](Part1.md)
[Part2](Part2.md)
[Part3](Part3.md)

Part 4: 

- [Lists](#Lists)
- [Referencing issues and pull requests](Referencing-issues-and-pull-requests)
- [Ignoring Markdown formatting](#Ignoring-Markdown-formatting)

## Lists

### Unordored List

By preceding one or more lines of text with - or *.

```
- George Washington
- John Adams
- Thomas Jefferson
```

- George Washington
- John Adams
- Thomas Jefferson

### Ordered List

By preceding each line with a number.

```
1. James Madison
2. James Monroe
3. John Quincy Adams
```

1. James Madison
2. James Monroe
3. John Quincy Adams

### Nested List

To create a nested list using the web editor on GitHub or a text editor that uses a monospaced font, like Atom,you can align your list visually. Type space characters in front of your nested list item, until the list marker character (- or *) lies directly below the first character of the text in the item above it.

```
1. First list item
    - First nested list item
    - Second nested list item
```

1. First list item
    - First nested list item
    - Second nested list item

To create a nested list in the comment editor on GitHub, which doesn't use a monospaced font, you can look at the list item immediately above the nested list and count the number of characters that appear before the content of the item. Then type that number of space characters in front of the nested list item.

In this example, you could add a nested list item under the list item 100. First list item by indenting the nested list item a minimum of five spaces, since there are five characters (100.) before First list item.

```
100. First list item
     - First nested list item
```

100. First list item
     - First nested list item

You can create multiple levels of nested lists using the same method. For example, because the first nested list item has seven spaces (␣␣␣␣␣-␣) before the nested list content First nested list item, you would need to indent the second nested list item by seven spaces.

100. First list item
     - First nested list item
       - Second nested list item

## Referencing issues and pull requests

You can bring up a list of suggested issues and pull requests within the repository by typing #. Type the issue or pull request number or title to filter the list, and then press either tab or enter to complete the highlighted result.

For more information, see [Autolinked references and URLs](https://help.github.com/en/articles/autolinked-references-and-urls).

### Ignoring Markdown formatting

You can tell GitHub to ignore (or escape) Markdown formatting by using \ before the Markdown character.

```
Let's rename \*our-new-project\* to \*our-old-project\*.
```

Let's rename \*our-new-project\* to \*our-old-project\*.