# Markdown Cheat Sheet

## Overview

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It covers both basic and extended syntax. While this cheat sheet offers a comprehensive guide, it may not cover every edge case. For more in-depth information about specific elements, refer to the reference guides for basic syntax and extended syntax.

## Basic Syntax

These elements are part of John Gruber's original design document, and all Markdown applications support them.

### Heading
```markdown
# H1
## H2
### H3
```

### Bold
```markdown
**bold text**
```

### Italic
```markdown
*italicized text*
```

### Blockquote
```markdown
> blockquote
```

### Ordered List
```markdown
1. First item
2. Second item
3. Third item
```

### Unordered List
```markdown
- First item
- Second item
- Third item
```

### Code
```markdown
`code`
```

### Horizontal Rule
```markdown
---
```

### Link
```markdown
[title](https://www.example.com)
```

### Image
```markdown
![alt text](image.jpg)
```

## Extended Syntax

Not all Markdown applications support these elements, but they provide additional features.

### Table
```markdown
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |
```

### Fenced Code Block
<pre>
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
</pre>

### Footnote
```markdown
Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.
```

### Heading ID
```markdown
### My Great Heading {#custom-id}
```

### Definition List
```markdown
term
: definition
```

### Strikethrough
```markdown
~~The world is flat.~~
```

### Task List
```markdown
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
```

### Emoji
```markdown
That is so funny! :joy:
```

### Highlight
```markdown
I need to highlight these ==very important words==.
```

### Subscript
```markdown
H~2~O
```

### Superscript
```markdown
X^2^
```

