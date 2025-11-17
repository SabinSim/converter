

# 💱 Currency Converter (CHF ↔ EUR)


A simple **Swiss Franc (CHF) ↔ Euro (EUR)** currency converter project.
Runs in the console using Python’s `input()` and provides basic currency conversion.

---

## 🚀 Features 


* Convert CHF → EUR

* Convert EUR → CHF

* Executes different logic depending on user selection

* Console-based user interface

---

## 📂 Project Structure 

```
converter/
│
├── converter.py
└── README.md
```

---

## 🧩 Code Example 

```python
choice = input("Select an option: 1) CHF → EUR | 2) EUR → CHF: ")

if choice == "1":
    rate = 1.05  # exchange rate
    print("=== Currency Converter ===")
    amount = float(input("Enter amount in CHF: "))
    result = amount * rate
    print("EUR:", result)

elif choice == "2":
    rate = 1.05  # exchange rate
    print("=== Currency Converter ===")
    amount = float(input("Enter amount in EUR: "))
    result = amount / rate
    print("CHF:", result)

```

---

## 📝 How to Run

### 1. Clone or download

```bash
git clone https://github.com/yourname/converter.git
cd converter
```

### 2. Run

```bash
python3 converter.py
```

---

## 🔧 Future Improvements 

* Add real-time exchange rate API

* Build a GUI version (tkinter / streamlit)

* Support more currencies (USD, KRW, etc.)

* Add error handling and input validation

---

## 📜 License

MIT License


