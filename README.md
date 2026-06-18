# ⏳ Age Calculator

An interactive Python script that calculates your exact age not just in years, but breaks it down into **months, days, hours, and seconds**. It accurately accounts for leap years using Python's built-in `calendar` and `time` modules.

---

## 🚀 Features

* **Detailed Breakdown:** Converts your age into months, days, hours, and seconds.
* **Leap Year Accuracy:** Uses the `calendar.isleap` method to correctly factor in 366-day years during calculations.
* **Real-time Local Data:** Fetches the current exact year, month, and day from your system clock to ensure precise results.

---

## 🛠️ How to Run

1. Ensure you have **Python 3** installed on your system.
2. Clone or download this repository.
3. Open your terminal, navigate to the project directory, and run:

```bash
python "calculate your age.py"

```
## 🎮 How it Works
 1. The script will prompt you to enter your **Name** and your **Age** (in years).
 2. It tracks back from the current year to your birth year.
 3. It loops through those years and counts the exact number of days, including leap years.
 4. Finally, it prints a complete summary of your life lived so far in various time units!
## 📝 Code Overview
 * **time.localtime**: Used to dynamically get the current system date.
 * **Functions (judge_leap_year, month_days)**: Modular logic written to handle the varying days in months and leap/non-leap year conditional checks.
 * **Time Conversion (to_hours, to_seconds)**: Simple arithmetic formulas wrapped in functions to scale days up to hours and seconds.
