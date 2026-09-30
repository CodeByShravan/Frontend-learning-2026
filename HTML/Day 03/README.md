# 🚀 Day 03 — HTML Lists & Tables

Welcome to Day 03 of my Frontend Development journey.

**Student:** Shravan Kumar  
**Goal:** Become a Frontend Developer  
**Day:** 03  
**Technology:** HTML5

---

## 🎯 Today's Goal

Today I learned how to organize information using HTML Lists and Tables.

Today's targets:

- Understand Unordered Lists
- Understand Ordered Lists
- Learn List Items
- Learn Nested Lists
- Learn Description Lists
- Understand HTML Tables
- Learn Table Rows and Cells
- Learn Table Headers
- Learn `colspan` and `rowspan`
- Build a practical HTML webpage

---

## 📚 1. What is an HTML List?

An HTML list is used to display related items in an organized format.

There are three main types of HTML Lists:

1. Unordered List
2. Ordered List
3. Description List

---

## 🔹 2. Unordered List — `<ul>`

An unordered list displays items using bullets.

### Example

```html
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
🔹 3. Ordered List — <ol>
An ordered list displays items in a sequence, usually with numbers.
Example
HTML
<ol>
    <li>Learn HTML</li>
    <li>Learn CSS</li>
    <li>Learn JavaScript</li>
</ol>
🔹 4. List Item — <li>
The <li> tag represents an individual item inside an ordered or unordered list.
Example
HTML
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
🔹 5. Nested Lists
A nested list is a list inside another list.
Example
HTML
<ul>
    <li>Frontend Development
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
        </ul>
    </li>
</ul>
🔹 6. Description List
A description list is used to display terms and their descriptions.
Important Tags
<dl> — Description List
<dt> — Description Term
<dd> — Description
Example
HTML
<dl>
    <dt>HTML</dt>
    <dd>Defines the structure of a webpage.</dd>

    <dt>CSS</dt>
    <dd>Styles the webpage.</dd>

    <dt>JavaScript</dt>
    <dd>Adds functionality and interaction.</dd>
</dl>


📊 7. What is an HTML Table?
An HTML table is used to display structured data in rows and columns.
Important Table Tags
Tag
Purpose
<table>
Creates a table
<caption>
Adds a table title
<tr>
Creates a table row
<th>
Creates a header cell
<td>
Creates a data cell
<thead>
Groups table header
<tbody>
Groups main table data
<tfoot>
Groups table footer

🔹 8. HTML Table Example
HTML
<table border="1">

    <caption>Student Marks</caption>

    <thead>
        <tr>
            <th>Name</th>
            <th>Subject</th>
            <th>Marks</th>
        </tr>
    </thead>

    <tbody>
        <tr>
            <td>Shravan</td>
            <td>HTML</td>
            <td>90</td>
        </tr>
    </tbody>

</table>

🔹 9. colspan and rowspan
colspan
colspan is used to make a table cell span across multiple columns.
Example
HTML
<table border="1">

    <tr>
        <th colspan="2">Student Details</th>
    </tr>

    <tr>
        <td>Name</td>
        <td>Shravan Kumar</td>
    </tr>

</table>
rowspan
rowspan is used to make a table cell span across multiple rows.
Example
HTML
<table border="1">

    <tr>
        <th rowspan="2">Frontend</th>
        <td>HTML</td>
    </tr>

    <tr>
        <td>CSS</td>
    </tr>

</table>

💻 10. Practical Project
Today I created a webpage containing:

.My skills using an unordered list
.My learning roadmap using an ordered list
.A nested list
.A description list
.A learning schedule using an HTML table
.colspan example
.rowspan example
.Header and footer

🧠 11. Interview Questions

1. What is the difference between <ul> and <ol>?
<ul> creates an unordered list, while <ol> creates an ordered list.

2. What is the purpose of <li>?
<li> represents a list item.

3. What is <table>?
<table> is used to create an HTML table.

4. What is <tr>?
<tr> represents a table row.

5. What is the difference between <th> and <td>?
<th> represents a table header cell, while <td> represents a normal data cell.

6. What is <caption>?
<caption> provides a title for an HTML table.

7. What is a nested list?
A list placed inside another list is called a nested list.

8. What is colspan?
colspan allows a table cell to span multiple columns.

9. What is rowspan?
rowspan allows a table cell to span multiple rows.

⚡ 12. Quick Revision
<ul>      = Unordered List
<ol>      = Ordered List
<li>      = List Item
<dl>      = Description List
<dt>      = Description Term
<dd>      = Description
<table>   = Table
<tr>      = Table Row
<th>      = Table Header
<td>      = Table Data
<thead>   = Table Header Section
<tbody>   = Table Body Section
<tfoot>   = Table Footer Section
colspan   = Span Columns
rowspan   = Span Rows

📝 13. Learning Notes
Today I learned how to organize information using HTML Lists and Tables.
I practiced:
Unordered Lists
Ordered Lists
Nested Lists
Description Lists
HTML Tables
Table Rows
Table Headers
Table Data
colspan
rowspan

🛠️ 14. Tools Used
GitHub Codespaces
Visual Studio Code
HTML5
Git
GitHub

📁 15. Project Structure
frontend-learning-2026/
└── HTML/
    ├── Day 01/
    ├── Day 02/
    └── Day 03/
        ├── index.html
        └── README.md

📤 16. GitHub Commit
Commit message:
Day 03: Added HTML lists and tables

✅ 17. Day 03 Result
[x] Learned Unordered Lists
[x] Learned Ordered Lists
[x] Practiced Nested Lists
[x] Learned Description Lists
[x] Created HTML Tables
[x] Practiced colspan
[x] Practiced rowspan
[x] Built a practical webpage
[x] Pushed Day 03 to GitHub

🚀 18. Next Day
Day 04 — HTML Forms & Input Elements
👨‍💻 Author
Shravan Kumar
Frontend Development Learner
GitHub: CodeByShravan

💡 Learning Rule
Learn → Practice → Build → Push to GitHub → Repeat
