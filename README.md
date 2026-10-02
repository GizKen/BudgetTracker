# My Budget Tracker

## PLP Week 4 – Rebuild the Tracker's Layout with Flexbox and Grid

My Budget Tracker is a simple personal finance web application designed to help users record, organize, and review their daily expenses.

This project continues the Budget Tracker developed during Week 3 of the PLP Software Engineering program.

Week 3 focused mainly on the application's visual identity, including the color palette, typography, spacing, cards, forms, tables and overall visual consistency.

For Week 4, the existing Budget Tracker was upgraded into a responsive dashboard using modern CSS layout techniques, particularly CSS Grid and Flexbox.

---

# Week 4 Project: Dashboard Layout

The main goal of Week 4 was to rebuild the Budget Tracker interface into a modern dashboard layout without changing the application's overall visual identity.

The upgraded dashboard contains:

- Sidebar navigation
- Dashboard header
- Financial summary cards
- Six spending category cards
- Add Expense form
- Recent Expenses table
- Budgeting Tips section
- Responsive mobile layout

---

# 1. Dashboard Structure

The overall page is structured using CSS Grid.

The dashboard contains two main areas:

1. Sidebar
2. Main content area

The main dashboard layout uses:

```css
.dashboard {
    display: grid;
    grid-template-columns: 250px minmax(0, 1fr);
}