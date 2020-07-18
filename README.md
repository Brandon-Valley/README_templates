# This is a rank 1 header

___

## This is a table of contents

[toc]

# H1  
some more text

Alt-H1
======
some text under header 1

Alt-H2
------
some text under header 2

Alternatively, for H1 and H2, a # style:

# H1  
some text under header 1
## H2

**testing**

some text under header 2
### H3
#### H4
##### H5
###### H6

# This is an H1

some text after H1

## This is an H2
###### This is an H6

This is also an H1
==================

This is also an H2
------------------

Paragraph 1

Paragraph 2

Character styles

*Italic characters*
_Italic characters_
**bold characters**
__bold characters__
~~strikethrough text~~

<u>underlined text</u>



Unordered list

*  Item 1
*  Item 2
*  Item 3
    *  Item 3a
    *  Item 3b
    *  Item 3c



	Ordered list

1.  Step 1
2.  Step 2
3.  Step 3
    1.  Step 3.1
    2.  Step 3.2
    3.  Step 3.3





	Quotes or citations

Introducing my quote:

> Neque porro quisquam est qui
> dolorem ipsum quia dolor sit amet,
> consectetur, adipisci velit...





Inline code characters

Use the backtick to refer to a `function()`.

There is a literal ``backtick (`)`` here.






Code blocks

Indent every line of the block by at least 4 spaces.

This is a normal paragraph:

    This is a code block.
    With multiple lines.

Alternatively, you can use 3 backtick quote marks before and after the block, like this:

```
This is a code block
```

To add syntax highlighting to a code block, add the name of the language immediately
after the backticks:

```javascript
var oldUnload = window.onbeforeunload;
window.onbeforeunload = function() {
    saveCoverage();
    if (oldUnload) {
        return oldUnload.apply(this, arguments);
    }
};
```






Links to external websites

This is [an example](http://www.example.com/) inline link.

[This link](http://example.com/ "Title") has a title attribute.

Links are also auto-detected in text: http://example.com/





![Alt text](/https://images.pexels.com/photos/45201/kitty-cat-kitten-pet-45201.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260 "Optional title attribute")
![Alt text](https://images.pexels.com/photos/45201/kitty-cat-kitten-pet-45201.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260)





Tables

| Day     | Meal    | Price |
| --------|---------|-------|
| Monday  | pasta   | $6    |
| Tuesday | chicken | $8    |


# Local .gif that displays text when you hover over it with your mouse

![alt text](\doc\imgs\local_cat_gif.gif "Meow")