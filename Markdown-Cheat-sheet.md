# Markdown Cheat Sheet

## Basic Syntax

Markdown is a lightweight markup language for creating formatted text. Below are examples with common syntax.

---

### Heading

Use `#` for headings. Add more `#` for smaller headings.

```markdown
# H1 - Main Title
## H2 - Section Title
### H3 - Subsection Title
```

---

### Bold

Use double asterisks (`**`) for bold text.

Example:
```markdown
**This is bold text**
```

Result:
**This is bold text**

---

### Italic

Use single asterisks (`*`) or underscores (`_`) for italic text.

Example:
```markdown
*This is italic text*
```

Result:
*This is italic text*

---

### Blockquote

Use the greater-than symbol (`>`).

Example:
```markdown
> This is a blockquote.
```

Result:
> This is a blockquote.

---

### Ordered List

Use numbers followed by a period.

Example:
```markdown
1. First item
2. Second item
3. Third item
```

Result:
1. First item  
2. Second item  
3. Third item  

---

### Unordered List

Use `-`, `+`, or `*`.

Example:
```markdown
- First item
- Second item
- Third item
```

Result:
- First item  
- Second item  
- Third item  

---

### Code

Wrap inline code with backticks (\`), or use triple backticks for code blocks.

Example:
```markdown
Inline code: `print("Hello, World!")`

Code block:
```python
def greet():
    print("Hello, World!")
```
```

Result:  

Inline code: `print("Hello, World!")`  

Code block:
```python
def greet():
    print("Hello, World!")
```

---

### Horizontal Rule

Use three dashes (`---`), underscores (`___`), or asterisks (`***`).

Example:
```markdown
---
___
***
```

---

### Link

Use `[text](URL)`.

Example:
```markdown
[Visit GitHub](https://github.com/)
```

Result:  
[Visit GitHub](https://github.com/)

---

### Image

Use `![alt text](image URL)`.

Example:
```markdown
![Markdown Logo](https://www.markdownguide.org/assets/images/tux.png)
```

Result:
![Markdown Logo](https://www.markdownguide.org/assets/images/tux.png)

---

### Table

Use pipes (`|`) and dashes (`-`) to create tables.

Example:
```markdown
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |
```

Result:
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

---

### Footnote

Add references using `[^1]`.

Example:
```markdown
This is a footnote example.[^1]

[^1]: Footnote content goes here.
```

Result:
This is a footnote example.[^1]  
[^1]: Footnote content goes here.

---

### Strikethrough

Use `~~` to strike through text.

Example:
```markdown
~~This text is crossed out.~~
```

Result:
~~This text is crossed out.~~

---

### Task List

Use `- [ ]` for incomplete tasks and `- [x]` for completed tasks.

Example:
```markdown
- [x] Complete homework
- [ ] Learn Markdown
- [ ] Submit the project
```

Result:
- [x] Complete homework  
- [ ] Learn Markdown  
- [ ] Submit the project  

---

### Emoji

Use text codes for emojis.

Example:
```markdown
I love programming! :heart_eyes:
```

Result:
I love programming! 😍

---

### Subscript and Superscript

Use `<sub>` for subscript and `<sup>` for superscript.

Example:
```markdown
H<sub>2</sub>O (Water)
E = mc<sup>2</sup> (Einstein's equation)
```

Result:  
H<sub>2</sub>O (Water)  
E = mc<sup>2</sup> (Einstein's equation)
