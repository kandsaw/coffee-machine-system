# ☕ Coffee Machine Python Project

This is a simple command-line coffee machine program written in Python. The program allows users to order different types of coffee while managing resources and handling transactions.

## 📜 Features

- Supports three coffee options:
  - **Espresso** ☕ (Water: 50ml, Coffee: 18g) - Cost: $1.5
  - **Latte** ☕ (Water: 200ml, Milk: 150ml, Coffee: 24g) - Cost: $2.5
  - **Cappuccino** ☕ (Water: 250ml, Milk: 100ml, Coffee: 24g) - Cost: $3.0
- Checks if enough resources are available before making a coffee.
- Accepts payments using:
  - Quarters ($0.25)
  - Dimes ($0.10)
  - Nickels ($0.05)
  - Pennies ($0.01)
- Calculates change if the user inserts more money than required.
- Provides a **report** on the remaining resources.
- Allows the machine to be turned **off**.

## 🛠 How It Works

1. The user is prompted to select a coffee type.
2. The program checks if there are enough resources.
3. If resources are sufficient, the user inserts coins.
4. The program verifies if the inserted money is enough.
5. If the transaction is successful, the coffee is served, and resources are updated.
6. The user can check the **report** for available resources.

## 📌 Usage

Run the Python script:

```bash
python main.py
```

## Commands:
- Enter espresso, latte, or cappuccino to order a coffee.
- Enter report to see the available resources.
- Enter off to shut down the coffee machine.
