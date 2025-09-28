# PersonalFinance

A simple personal finance tracker written in Python that helps you log, categorize, and analyze your transactions.

## Table of Contents

- [Features](#features)  
- [Demo / Screenshots](#demo--screenshots)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Configuration / Data Files](#configuration--data-files)  
- [Requirements](#requirements)  
- [How It Works](#how-it-works)  
- [Future Improvements](#future-improvements)  
- [Contributing](#contributing)  
- [License](#license)  
- [Acknowledgements](#acknowledgements)  

---

## Features

- Log daily transactions (income / expense)  
- Assign categories (e.g. Food, Rent, Utilities)  
- Read/Write from a CSV (`Transaction.csv`)  
- Categories defined in a JSON file (`categories.json`)  
- (If applicable) summary, balance, filtering by date or category  

## Demo / Screenshots

Below are some sample screenshots:

### Dashboard – Upload & Manage Transactions
This screen lets you upload your transaction CSV, add new categories, and see your expenses in a clean table.

![Dashboard](docs/Adding_Categories.png)

---

### Expense Summary – By Category
This view shows a breakdown of expenses grouped by category, along with a pie chart for better visualization.

![Summary View](docs/Summary_View.png)

---

### Upload Transactions – CSV Import
This screen allows you to import your transaction data directly from a CSV file. Simply click **“Upload CSV”**, select your file, and the transactions will be added to your dashboard automatically.

![Upload CSV](docs/Upload_CSV.png)

---

## Installation

**1. Clone the repo**

```bash
git clone https://github.com/Sahdevnyc/PersonalFinance.git
cd PersonalFinance
