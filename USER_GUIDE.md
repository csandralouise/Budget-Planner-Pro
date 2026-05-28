# 📖 Budget Planner Pro — User Guide

> Everything you need to know to take full control of your finances with Budget Planner Pro.

---

## Table of Contents

1. [Getting Started](#1-getting-started)
2. [Dashboard](#2-dashboard)
3. [Monthly Budget](#3-monthly-budget)
4. [Weekly Budget](#4-weekly-budget)
5. [Zero-Based Budget](#5-zero-based-budget)
6. [Debt Payoff Planner](#6-debt-payoff-planner)
7. [50/30/20 Rule](#7-503020-rule)
8. [Savings Goals](#8-savings-goals)
9. [Financial Calendar](#9-financial-calendar)
10. [Reports & Analytics](#10-reports--analytics)
11. [Bill Reminders & Notifications](#11-bill-reminders--notifications)
12. [Profile & Settings](#12-profile--settings)
13. [Data Management](#13-data-management)
14. [Tips & Best Practices](#14-tips--best-practices)
15. [Cloning & Running Locally](#15-cloning--running-locally)

---

## 1. Getting Started

### First Launch — Onboarding

When you open Budget Planner Pro for the first time you will see the welcome screen. It walks you through three quick steps:

**Step 1 — Welcome screen**
Click **Get Started →** to begin.

**Step 2 — Your details** *(required)*
- **Your Name** — This personalises your dashboard, insights and welcome screen. It cannot be left blank.
- **Monthly Income** — Enter your total take-home income per month. This is the number the entire app budgets around. It cannot be zero.
- **Currency** — Choose from 8 currencies:
  - `$` US Dollar · `€` Euro · `£` British Pound · `¥` Japanese Yen
  - `₹` Indian Rupee · `C$` Canadian Dollar · `A$` Australian Dollar · `B$` Bahamian Dollar

> ⚠️ Both name and income are required before you can continue. Fields will highlight red if left empty.

**Step 3 — Ready!**
The app loads with sample data scaled to your income so you can explore every feature immediately. You can clear it anytime from Settings.

---

### Returning Users — Welcome Screen

Every time you reopen the app you will see a personalised welcome screen with:
- A greeting using your first name
- The current day and time of day (Good morning / afternoon / evening)
- A randomly selected Bible verse about money and wisdom
- A **Open My Dashboard →** button to enter

Press **Escape** or click the button to dismiss it.

---

### Navigation

The **sidebar** on the left contains all pages. The currently active page is highlighted with a teal indicator bar. On mobile, tap the floating button (bottom right) to open the sidebar.

The **topbar** at the top of every page shows:
- Current page title
- 🌙 / ☀️ Theme toggle (light / dark mode)
- 🔔 Bell icon — lights up red when a bill is due soon
- ⬇️ Export button — downloads your data as JSON
- 🖫 Print button
- **+ Add Item** button — quick shortcut to add income, expenses, debts or goals from anywhere

---

## 2. Dashboard

The Dashboard is your financial command centre. It updates live as you add data.

### Summary Cards (top row)

| Card | What it shows |
|------|--------------|
| **Total Income** | Sum of all your monthly income sources |
| **Total Expenses** | Sum of all your monthly expenses |
| **Remaining Balance** | Income minus expenses |
| **Total Savings** | Sum of all expenses categorised as *Savings* |
| **Total Debt Remaining** | Sum of all debt balances in your Debt Planner |

### Charts

- **Monthly Overview** — Bar chart comparing income vs expenses across 6 months
- **Spending by Category** — Doughnut chart showing what percentage of spending goes to each category
- **Budget Health Score** — A circular meter scored out of 100 based on your savings rate, expense ratio and debt load
- **Weekly Spending** — Bar chart showing spending by day of the current week

### Financial Insights

A rotating insight strip at the top shows a personalised tip based on your actual data — your savings rate, biggest spending category, debt situation and goal progress.

### Financial Tips

A panel of 3 rotating tips from personal finance best practices. Click **Refresh** to see a new set.

---

## 3. Monthly Budget

This is where you record all your income and expenses for a given month.

### Month Navigation

Use the **← →** arrows at the top to move between months. Each month is tracked independently.

### Income Sources

Click **+ Add Income** to add a new source. Fill in:

| Field | Description |
|-------|-------------|
| **Source Name** | e.g. Main Salary, Freelance Design, Rental Income |
| **Amount** | The amount for the selected frequency |
| **Frequency** | Monthly / Bi-weekly / Weekly / Yearly / One-time |
| **Category** | Salary, Business, Freelance, Investment, Rental, Other |

> 💡 Weekly and bi-weekly amounts are automatically converted to a monthly equivalent for all calculations.

To **edit** an entry click the **Edit** button on its row. To **delete** it click **Delete** (a confirmation dialog will appear).

Use the **search bar** to filter entries by name.

### Expenses

Click **+ Add Expense** to add a new expense. Fill in:

| Field | Description |
|-------|-------------|
| **Expense Name** | e.g. Rent, Groceries, Netflix |
| **Amount** | Monthly amount |
| **Category** | Housing, Food, Transport, Utilities, Health, Entertainment, Savings, Debt, Other |
| **Due Date** | Day of the month it is due (1–31) — used by bill reminders and the calendar |
| **Priority** | Essential / Important / Optional |
| **Notes** | Any extra information (optional) |

Use the **category filter** dropdown to view only one category at a time.

### Budget Summary

At the bottom of the page:
- **Net Balance** — What's left after all expenses (green = surplus, red = deficit)
- **Savings Rate** — Percentage of income being saved
- **Budget Status** — ✅ Surplus / ⚖️ Balanced / ⚠️ Deficit
- **Expense ratio bar** — Visual indicator of how much of your income is being spent

---

## 4. Weekly Budget

Track your day-to-day spending week by week, organised by month.

### Month Navigation

Use the **← →** arrows to switch months. Each month stores its own Week 1 through Week 4 data independently, so January's weeks are completely separate from February's.

### Switching Weeks

Click the **Week 1 / Week 2 / Week 3 / Week 4** tabs to switch between weeks within the current month.

### Adding Entries

Click **+ Add Entry** and fill in:
- **Description** — What you spent money on (e.g. Lunch, Coffee, Petrol)
- **Amount** — How much was spent
- **Category** — Food, Transport, Entertainment, Shopping, Health, Other

### Weekly Summary Panel

The right panel shows:
- Spending total for each of the 4 weeks
- A progress bar showing each week's share of the monthly total
- The combined monthly total across all 4 weeks

### 4-Week Overview Chart

A line chart showing the spending trend across all 4 weeks of the selected month. Useful for spotting which weeks you tend to overspend.

---

## 5. Zero-Based Budget

Zero-based budgeting means **every dollar of your income is assigned a job** — when you subtract all assignments from your income the result should be zero.

### How It Works

1. Your total monthly income appears at the top as the amount to assign
2. Click **+ Assign Funds** to create a category and assign an amount
3. The **Unassigned Funds** panel on the right updates live:
   - 🟡 **Yellow** — funds remaining to be assigned
   - 🔴 **Red** — you have assigned more than your income (over budget)
   - ✅ **Green** — every dollar is assigned

### Assignment Fields

| Field | Description |
|-------|-------------|
| **Category / Job** | What this money is for (e.g. Emergency Fund, Vacation, Car Repair) |
| **Amount Assigned** | How much of your income goes here |
| **Type** | Fixed / Variable / Savings / Debt |

### Allocation Chart

A doughnut chart on the right shows how your income is divided across all your assigned categories visually.

> 💡 **Tip:** Start with your fixed essentials (rent, utilities, loan payments), then assign variable expenses (groceries, entertainment), then savings, then anything left over to a fun or buffer category until you reach zero.

---

## 6. Debt Payoff Planner

Track all your debts and find the fastest path to becoming debt-free.

### Adding a Debt

Click **+ Add Debt** and fill in:

| Field | Description |
|-------|-------------|
| **Debt Name** | e.g. Credit Card A, Student Loan, Car Loan |
| **Current Balance** | How much you currently owe |
| **Interest Rate (%)** | The annual percentage rate (APR) |
| **Min. Monthly Payment** | The minimum payment required each month |
| **Debt Type** | Credit Card / Student Loan / Auto Loan / Mortgage / Personal Loan / Medical / Other |

### Summary Cards

- **Total Debt** — Combined balance of all debts
- **Monthly Payments** — Total minimum payments per month
- **Est. Interest** — Estimated interest you will pay per year at current balances
- **Debt-Free In** — Rough estimate of months to pay everything off at minimum payments

### Payoff Strategies

Use the two buttons at the top to switch strategy:

**🔵 Debt Snowball**
Pays off the **smallest balance first**. Once it's gone, roll that payment into the next smallest. Gives you quick wins and psychological momentum.

**🔴 Debt Avalanche**
Pays off the **highest interest rate first**. Mathematically saves the most money in interest over time.

The strategy panel shows your debts in the recommended payoff order with the suggested payment for each.

> 💡 **Which is better?** If you need motivation to stay on track — Snowball. If minimising total interest paid is the priority — Avalanche.

---

## 7. 50/30/20 Rule

A popular budgeting framework that divides your after-tax income into three buckets.

| Bucket | % of Income | What Goes Here |
|--------|------------|----------------|
| **Needs** | 50% | Rent/mortgage, groceries, utilities, transport, health insurance |
| **Wants** | 30% | Dining out, entertainment, subscriptions, hobbies, shopping |
| **Savings & Debt** | 20% | Emergency fund, investments, extra debt payments |

### How Budget Planner Pro calculates it

- **Needs** pulls from expenses categorised as: Housing, Food, Transport, Utilities, Health
- **Wants** pulls from: Entertainment, Shopping
- **Savings & Debt** pulls from: Savings, Debt

### Reading the progress bars

- Bar fills towards the budget limit for each category
- **Green** — you are within the recommended percentage
- **Orange / Red** — you are over the recommended limit

### Recommendations panel

Below the chart, personalised recommendations appear based on your actual data — for example "Reduce needs spending by $350" or "Increase savings by $200/mo".

> 💡 **Tip:** The 50/30/20 rule is a guideline, not a law. In high cost-of-living areas, needs often exceed 50%. Adjust the labels in your Monthly Budget to reflect your reality.

---

## 8. Savings Goals

Set specific financial targets and track your progress toward each one.

### Creating a Goal

Click **+ New Goal** and fill in:

| Field | Description |
|-------|-------------|
| **Goal Name** | e.g. Emergency Fund, Dream Vacation, New Car |
| **Target Amount** | The total amount you want to save |
| **Current Amount** | How much you have already saved toward this goal |
| **Target Date** | The date you want to reach the goal by |
| **Monthly Contribution** | How much you plan to add each month |
| **Icon / Emoji** | A fun emoji to represent the goal (e.g. 🏖️ 🚗 🏠 📚) |

### Goal Cards

Each goal shows:
- Current saved vs target amount
- Progress bar (fills as you save)
- Percentage complete
- Days remaining until target date (turns red if under 30 days)
- Monthly contribution amount and how much more is needed
- 🎉 **Goal Complete!** badge when you reach 100%

To update your saved amount as you contribute, click **Edit** on the goal card and update the Current Amount field.

### Savings Overview Chart

A stacked bar chart at the bottom shows the saved vs remaining amount for all goals side by side.

---

## 9. Financial Calendar

A full monthly calendar showing all your financial events in one place.

### What appears on the calendar

| Colour | Type | When it appears |
|--------|------|----------------|
| 🟢 Green | Income due | Day 1 (and Day 15 for bi-weekly income) |
| 🔴 Coral | Expense due | On the due date set in Monthly Budget |
| 🔴 Red | Debt payment | Day 1 of each month |
| 🟣 Indigo | Goal contribution | Day 1 of each month |

> 💡 **For expenses to appear on the calendar**, make sure you set a **Due Date** (day of month) when adding the expense in Monthly Budget.

### Month Navigation

Use the **← →** arrows or **Today** button to navigate months.

### Clicking a Day

Click any day that has events (shown with a coloured border) to open a **Day Detail Panel** below the calendar. It lists every event for that day with the amount.

### Monthly Summary Strip

Three cards below the calendar show:
- **Bills Due This Month** — Total of all expense payments
- **Income Expected** — Total monthly income
- **Next Bill Due** — The name and amount of the next upcoming bill

---

## 10. Reports & Analytics

A full analytics view of your financial patterns over time.

### Charts included

| Chart | What it shows |
|-------|--------------|
| **Income Trend** | Line chart of your income across 12 months |
| **Expense Trend** | Line chart of your expenses across 12 months |
| **Category Analysis** | Each expense category with amount and % of total spending |
| **Monthly Comparison** | Bar chart comparing recent months side by side |

### Exporting

- **Export CSV** — Downloads a spreadsheet-friendly file of all your income, expenses, debts and goals. Open in Excel or Google Sheets.
- **Export JSON** — Downloads a complete backup of all your data. Use this to restore the app on another device or browser.

---

## 11. Bill Reminders & Notifications

Budget Planner Pro includes a smart alert system that requires **no permissions and no setup** — it works automatically every time you open the app.

### Smart Alert Banner

A coloured banner slides in from the top of the screen when bills are coming up:

| Colour | Meaning |
|--------|---------|
| 🔴 Red | Bill is due **TODAY** |
| 🟠 Orange | Bill is due **tomorrow** |
| 🟢 Teal | Bill is due within your alert window |

The banner shows the bill name, amount and days until due. Click **View Bills** to go to Settings, or **✕ Dismiss** to close it.

### Bell Icon

The 🔔 bell icon in the topbar shows a **red dot** when bills are within your alert window. Clicking it clears the dot and takes you to Settings.

### Configuring Your Alert Window

In **Settings → Bill Reminders**, choose how many days in advance you want to be alerted:

**1 day · 2 days · 3 days · 5 days · 7 days**

Click the number you prefer — it saves automatically.

### Test Your Alerts

Click **🔔 Test Alert Now** to see a sample banner immediately and confirm everything is working.

### WhatsApp Reminders

For a personal message to yourself:

1. Select your country code from the dropdown (Bahamas 🇧🇸 +1242 is pre-selected)
2. Enter your WhatsApp phone number (numbers only, no spaces or dashes)
3. Click **💾 Save Number**
4. In the **Upcoming Bills** panel, click the green **💬 WhatsApp** button next to any bill
5. WhatsApp opens with a pre-written reminder message ready to send to yourself

### Upcoming Bills Panel

The right column in Settings shows all bills due in the next 7 days with:
- Bill name and amount
- Colour-coded urgency indicator
- WhatsApp button (if your number is saved)
- Click **↻ Refresh** to update the list

---

## 12. Profile & Settings

### Profile Card

- **Full Name** — Update your name at any time
- **Monthly Income** — Changing this updates the primary salary income line in Monthly Budget and re-calculates everything across the app
- **Currency** — Changing the currency symbol updates it everywhere instantly
- Click **Save Changes** when done — all pages refresh automatically

### Display Settings

Toggle between **☀️ Light** and **🌙 Dark** mode. Your preference is saved and remembered on your next visit.

---

## 13. Data Management

All your data is stored in your browser's **localStorage**. It never leaves your device.

### Exporting your data

| Option | Use it for |
|--------|-----------|
| **📦 Export JSON** | Full backup of everything — use to restore on another browser or device |
| **📄 Export CSV** | Spreadsheet export for Excel, Google Sheets or Numbers |

### Importing a backup

Click **📥 Import JSON Backup** and select a previously exported `.json` file. All your data will be restored.

> ⚠️ Importing will replace your current data. Export a backup first if needed.

### Clearing all data

Click **🗑️ Clear All Data** — a confirmation dialog will appear. This permanently deletes everything and resets the app to a fresh state.

### Important notes on data storage

- Each **browser** (Chrome, Firefox, Safari) has its own separate storage
- Each **device** (phone, laptop, tablet) has its own separate storage
- Clearing your browser's cache or cookies **will delete your data**
- **Always keep a JSON backup** exported somewhere safe (email it to yourself, save to Google Drive, etc.)
- To move data to a new device: Export JSON on the old device → Import JSON on the new one

---

## 14. Tips & Best Practices

### Getting the most from the app

**Set due dates on all your expenses**
Due dates unlock the Calendar view and Bill Reminder alerts. Without them, bills won't appear on the calendar or trigger reminders.

**Update your Weekly Budget regularly**
The more consistently you log weekly spending, the more accurate your monthly picture becomes. Aim to log entries a few times a week.

**Keep your debt balances current**
When you make a debt payment, edit that debt and reduce the balance. This keeps your debt-free estimate accurate.

**Update savings goal progress monthly**
After contributing to a savings goal, edit it and increase the Current Amount. Watch that progress bar grow!

**Export a JSON backup monthly**
Takes 2 seconds and means you never lose your data. Email it to yourself or save it to cloud storage.

**Use Zero-Based Budgeting alongside Monthly Budget**
Monthly Budget tracks what actually happened. Zero-Based is for planning ahead — assign your income before the month begins so every dollar has a purpose.

### Understanding the Budget Health Score

The score out of 100 is calculated from three factors:

| Factor | What earns points |
|--------|------------------|
| **Savings Rate** | 20%+ of income saved = maximum points |
| **Expense Ratio** | Spending less than 70% of income = maximum points |
| **Debt Load** | Total debt less than 30% of annual income = maximum points |

A score of 70+ is healthy. Below 50 means there is meaningful room to improve — start with reducing the largest expense category or increasing savings.

---

## 15. Cloning & Running Locally

### What you need

Nothing! Budget Planner Pro is a **single HTML file** with no build process, no Node.js, no package manager and no server required.

### Steps to run

```bash
# Clone the repository
git clone https://github.com/yourusername/budget-planner.git

# Navigate into the folder
cd budget-planner

# Open in your browser — that's it!
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

Or simply double-click `index.html` in your file manager.

### Hosting on GitHub Pages

```bash
# After cloning, make your changes, then push back
git add index.html
git commit -m "Update budget planner"
git push origin main
```

Your changes will be live at `https://yourusername.github.io/budget-planner` within a few minutes.

### Hosting on Netlify

1. Drag the project folder onto [netlify.com](https://netlify.com)
2. Get a live HTTPS URL instantly
3. To update: drag the folder again

### Dependencies (loaded from CDN)

| Library | Version | Purpose |
|---------|---------|---------|
| [Chart.js](https://www.chartjs.org/) | 4.4.1 | All charts and graphs |
| [Inter](https://fonts.google.com/specimen/Inter) | Google Fonts | Typography |

> **Offline use:** If you open the file without internet, charts will not display (Chart.js won't load) but every other feature — budgets, debt tracker, goals, calendar, reminders, export, import — works fully offline.

### Customising

All CSS variables are at the top of the `<style>` block:

```css
:root {
  --teal:     #006B6B;   /* primary colour */
  --coral:    #D84860;   /* accent / alerts */
  --blue:     #7AA8C0;   /* secondary accent */
  --navy:     #2C3A6B;   /* dark accent */
}
```

Change these four values to retheme the entire application instantly.

---

## Need Help?

If something isn't working:

1. Try refreshing the page
2. Check the browser console (F12 → Console tab) for any error messages
3. If data appears lost, check if you're in the same browser you originally used
4. Use **Import JSON** to restore from a backup

---

*Budget Planner Pro — built with love 🌴*
*"A budget is telling your money where to go instead of wondering where it went." — Dave Ramsey*
