# My Budget Tracker

## PLP Week 2 Assignment

This project is a simple personal Budget Tracker built using **HTML and CSS**.

The project builds on the Budget Tracker created in Week 1 and adds an expense table, an improved expense form, multimedia content, an interactive details section, and advanced CSS selectors.

## Features

### 1. Expense Table

The project contains a properly structured HTML table using:

* `<table>`
* `<thead>`
* `<tbody>`
* `<tr>`
* `<th>`
* `<td>`

The table contains four columns:

* Name
* Amount
* Category
* Date

It also contains five sample expense records.

The CSS includes:

* Collapsed borders
* Cell padding
* Colored table headers
* Alternating row colors
* Hover effects

### 2. Add Expense Form

The Add Expense section contains a proper `<form>` element.

The form includes:

* Expense name input
* Amount input
* Category dropdown
* Date input
* Add Expense button

The category dropdown contains:

1. Food
2. Transport
3. Rent
4. Entertainment
5. Other

Each input has a matching `id` attribute for future JavaScript functionality.

### 3. Multimedia

A budget tracker logo has been added using an `<img>` element with:

* `src`
* `alt`
* `width`

A relevant budgeting video has also been embedded using an `<iframe>` with:

* `width`
* `height`
* `title`
* `frameborder`

### 4. Interactive Element

A `<details>` and `<summary>` element provides a collapsible "How to use this tracker" section.

The table rows also change appearance when the user moves the mouse over them.

The Add Expense button uses `cursor: pointer`.

### 5. Advanced CSS Selectors

The project demonstrates several advanced CSS selectors:

#### Descendant Selector

```css
.expenses-section td,
.expenses-section th
```

#### Position Pseudo-class

```css
.expenses-section tbody tr:nth-child(even)
```

#### Negation Pseudo-class

```css
input:not([type="submit"])
```

#### Focus Pseudo-class

```css
input:focus,
select:focus
```

#### Hover Pseudo-class

```css
.expenses-section tbody tr:hover
```

## Technologies Used

* HTML5
* CSS3

## Project Files

```text
Budget-Tracker/
│
├── index.html
├── style.css
└── README.md

## Future Improvements

JavaScript functionality can be added in future weeks to allow users to add expenses dynamically, calculate totals, and manage their budget.

## Author

Kenneth Cheruiyot

