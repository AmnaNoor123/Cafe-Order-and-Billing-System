# ☕ Cafe Order & Billing System

A Python console application that lets a customer register, browse the menu, order multiple items, and instantly receive an itemized bill — with automatic tax calculation based on the payment method.

---

## 📝 Description

The Cafe Order & Billing System validates customer details, takes a multi-item order, calculates tax (5% for card, 16% for cash), and prints a complete receipt with date, time, subtotal, tax, and grand total.

---

## 🚀 Features

- 👤 Customer name validation (alphabets only, auto-capitalized)
- 📱 Phone number validation (must be exactly 11 digits)
- 📋 Dynamic menu display
- 🛒 Multi-item ordering loop (order as many items as needed)
- 🔢 Quantity validation (positive whole numbers only)
- 💳 Payment method selection — Cash or Card
- 🧾 Automatic tax calculation:
  - Card payment → 5% tax
  - Cash payment → 16% tax
- 🕐 Auto date & time stamping
- 🧾 Auto-generated itemized receipt

---

## 🍽️ Menu

| Item | Price |
|---|---|
| Cookie | Rs 200 |
| Chocolate Latte | Rs 300 |
| Sandwich | Rs 100 |
| Coffee | Rs 90 |
| Cake Slice | Rs 300 |
| Brownie | Rs 100 |
| Hot Chocolate | Rs 400 |

---

## 🛠️ Technology

- **Language:** Python 3
- **Tested/Run on:** Google Colab and Notebook
- **Libraries used:** `datetime` (built-in)

---

## ▶️ How to Run

1. Open [Google Colab](https://colab.research.google.com) or any Python environment.
2. Paste the code from `cafe_order_system.py` into a cell/file.
3. Run the script.
4. Follow the on-screen prompts to enter customer details and place an order.

---

## 🧾 Sample Output

```
========== RECEIPT ==========
Date : 06-07-2026
Time : 09:20 AM
Customer Name : Ali
Phone Number  : 03001234567
Payment Method: CARD

Items Ordered:
-----------------------------
coffee x2 = Rs180
cake slice x1 = Rs300
-----------------------------
Subtotal        : Rs 480
Tax (5%)       : Rs 24.0
Total Payable   : Rs 504.0
=============================
Thank you for visiting
```

---

## 📄 License

This project is developed for educational purposes.
