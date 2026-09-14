# My Budget Tracker

## PLP Week 3 – Design the Visual Identity of Your Budget Tracker

### Project Description

My Budget Tracker is a simple personal finance web application designed to help users record, organize, and review their daily expenses.

This project continues the Budget Tracker developed during the previous weeks of the PLP Software Engineering program. For Week 3, the main focus was improving the **visual identity, layout, typography, color palette, spacing, and overall user experience** of the application.

The goal was to transform the basic Week 2 interface into a more professional and visually consistent budget dashboard.

---

## Week 3 Design Improvements

### 1. Intentional Color Palette

The application uses a consistent financial-themed color palette.

* **Primary Navy:** `#173b57`
* **Primary Light Blue:** `#245b82`
* **Accent Teal:** `#2a9d8f`
* **Light Background:** `#eef3f6`
* **White Cards:** `#ffffff`
* **Main Text:** `#263238`
* **Muted Text:** `#64748b`

CSS custom properties were used to make the color system consistent and easy to maintain.

```css
:root {
    --primary: #173b57;
    --primary-light: #245b82;
    --accent: #2a9d8f;
    --background: #eef3f6;
    --card: #ffffff;
}
```

---

## 2. Typography

The project uses Google Fonts to create a clear and professional visual hierarchy.

### Poppins

Used mainly for:

* Main headings
* Section headings
* Table headings

### DM Sans

Used for:

* Body text
* Labels
* Form fields
* Buttons
* Table content

This combination improves readability and gives the website a modern appearance.

---

## 3. Dashboard Layout

The Week 3 version introduces summary cards at the top of the application.

The dashboard displays:

* Total Expenses
* Number of Expense Recor
