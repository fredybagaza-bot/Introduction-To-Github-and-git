# Task 3: Learn Markdown

Markdown is a lightweight formatting language used **everywhere** on GitHub — in READMEs, issues, pull requests, comments, and wikis. If you can write Markdown, you can communicate effectively on GitHub.

This task will teach you the syntax and give you exercises to practice.

---

## What is Markdown?

Markdown lets you format plain text using simple symbols. GitHub renders it into nicely formatted content. The file you are reading right now is written in Markdown.
Files ending in `.md` (like `README.md`) are Markdown files.

---

## Syntax Reference

### Headings

Use `#` symbols. More `#` = smaller heading.

```markdown
# Heading 1 (largest)
## Heading 2
### Heading 3
#### Heading 4
```

### Text Formatting

```markdown
**bold text**
*italic text*
~~strikethrough~~
`inline code`
```

Renders as: **bold text**, *italic text*, ~~strikethrough~~, `inline code`

### Links

```markdown
[Link text](https://example.com)
```

Renders as: [Link text](https://example.com)

### Images

```markdown
![Alt text](https://url-to-image.com/image.png)
```

You can also drag and drop images directly into the GitHub editor.

### Lists

**Unordered list:**

```markdown
- Item one
- Item two
  - Nested item
- Item three
```

**Ordered list:**

```markdown
1. First step
2. Second step
3. Third step
```

### Blockquotes

```markdown
> This is a blockquote. Use it to highlight important information.
```

Renders as:

> This is a blockquote. Use it to highlight important information.

### Code Blocks

For inline code, wrap with backticks: `` `code here` ``

For multi-line code blocks, use triple backticks and optionally specify the language:

````markdown
```python
print("Hello, world!")
```
````

Renders as:

```python
print("Hello, world!")
```

### Tables

```markdown
| Name    | Role      | Status   |
|---------|-----------|----------|
| Alice   | Developer | Active   |
| Bob     | Designer  | Active   |
| Charlie | Tester    | On leave |
```

Renders as:

| Name    | Role      | Status   |
|---------|-----------|----------|
| Alice   | Developer | Active   |
| Bob     | Designer  | Active   |
| Charlie | Tester    | On leave |

### Task Lists (Checkboxes)

```markdown
- [x] Completed task
- [ ] Incomplete task
- [ ] Another task to do
```

Renders as:

- [x] Completed task
- [ ] Incomplete task
- [ ] Another task to do

These are especially useful in GitHub Issues and Pull Requests.

### Horizontal Rule

```markdown
---
```

Renders as a divider line (like the ones in this document).

---

## Practice Exercise

You will create a Markdown practice file in **your own repository** so your instructor can review it.

### How to do it

1. Go to your **profile README repository** (the one you created in Task 1, named after your username).
2. Click **Add file** > **Create new file**.
3. In the "Name your file" field, type `markdown-practice.md`.
4. Complete all the exercises listed below directly in this file. Write each exercise under its own heading.
5. Scroll down, type a commit message (e.g., "Add markdown practice exercises"), and click **Commit changes**.
6. After committing, click on the file in your repository to verify it renders correctly. If something looks wrong, click the pencil icon to edit and fix it.

### Exercises

Complete **all** of the following in your `markdown-practice.md` file:

**Exercise 1 — Headings:**
Create a heading level 2 that says "My Learning Goals" and a heading level 3 that says "This Semester".

**Exercise 2 — Text formatting:**
Write a sentence that includes a **bold** word, an *italic* word, and an `inline code` snippet.

**Exercise 3 — Links:**
Create a link to your GitHub profile page and a link to any website you find useful.

**Exercise 4 — Lists:**
Create an unordered list of 3 things you want to learn. Then create an ordered list of the steps to make a commit in Git (hint: there are at least 3 steps).

**Exercise 5 — Table:**
Create a table with 3 columns (Tool, Purpose, Link) and at least 2 rows listing tools you use or want to learn.

**Exercise 6 — Task list:**
Create a task list with at least 4 items related to your learning goals. Check off the ones you have already completed.

**Exercise 7 — Code block:**
Write a code block in any language (or copy an example from the syntax reference above). Make sure to specify the language after the triple backticks for syntax highlighting.

**Exercise 8 — Blockquote:**
Write a blockquote with a piece of advice, a quote you like, or something you learned recently.

**Bonus — Put it all together:**
At the end of the file, write a mini "About Me" section that uses at least 5 different Markdown features from the exercises above.

---

## What to Submit

When you are done, your instructor will check:

- [ ] Your profile README repository contains a file called **`markdown-practice.md`**.
- [ ] The file includes **all 8 exercises** completed with correct Markdown syntax.
- [ ] The file **renders correctly** on GitHub (headings display as headings, tables render as tables, etc.).

**Submit:** The link to your `markdown-practice.md` file (e.g., `https://github.com/janedoe/janedoe/blob/main/markdown-practice.md`).

---

## Reference

- [Basic writing and formatting syntax - GitHub Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [Markdown Guide](https://www.markdownguide.org/)
