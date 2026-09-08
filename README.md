# Personal Budget Tracker - Week 2 Upgrade

This project is a Personal Budget Tracker built using structured HTML5 and custom CSS. It allows users to view, structure, and submit spending records across multiple categories.

## Features & Project Overview

1. **Structured Expense Table**:
   - Replaced placeholder text with a full HTML table structure utilizing `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, and `<td>`.
   - Includes 5 hardcoded initial expenses covering names, amounts, categories, and dates.
   - Formatted with `border-collapse: collapse`, alternating row colors (`:nth-child(even)`), and cell padding.

2. **Upgraded Form**:
   - Wrapped inside a semantic `<form>` element.
   - Added a `<select>` dropdown with 5 mandatory categories: *Food, Transport, Rent, Entertainment, Other*.
   - Input elements equipped with distinct `id` attributes (`expense-name`, `expense-amount`, `expense-category`, `expense-date`).
   - Includes an explicit `<button type="button">` ready for future JavaScript bindings.

3. **Multimedia Elements**:
   - Integrated a logo graphic inside the main header via `<img>` configured with explicit `src`, `alt`, and `width` values.
   - Embedded an educational budgeting video via an `<iframe>` container.

4. **Interactive & Advanced CSS Features**:
   - Added an interactive collapse section using `<details>` and `<summary>`.
   - Enabled hover feedback on table rows (`tr:hover`) and set `cursor: pointer` for button interactions.
   - Implemented advanced CSS selectors including:
     - **Descendant Selector**: `.expenses-section td`
     - **Direct Child Selector**: `.add-expense-section > form`
     - **Position-based Selector**: `tr:nth-child(even)`
     - **Negation Selector**: `input:not([type="button"])`
     - **Focus State**: `input:focus`

## File Structure

```text
/
├── index.html   # Main HTML5 Document Structure
├── style.css    # Stylesheet containing table, form, and selector definitions
└── README.md    # Documentation file
