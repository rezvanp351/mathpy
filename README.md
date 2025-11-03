# 🧮 Python Math Module – Complete Guide

This repository provides a **complete educational guide** for Python’s built-in `math` module, inspired by [W3Schools](https://www.w3schools.com/python/module_math.asp).  
Each function includes a detailed explanation and example.

---

## 📘 How to Use
Clone this repository and run the example file:

```bash
python math_examples.py
```

---

## 🧩 Main Functions with Explanations and Examples

### 1. `math.ceil(x)`
**Description:**  
Returns the smallest integer greater than or equal to `x`.

```python
import math
print(math.ceil(4.2))  # Output: 5
# Explanation: The next integer greater than 4.2 is 5.
```

---

### 2. `math.floor(x)`
**Description:**  
Returns the largest integer less than or equal to `x`.

```python
print(math.floor(4.9))  # Output: 4
# Explanation: The integer less than 4.9 is 4.
```

---

### 3. `math.sqrt(x)`
**Description:**  
Returns the square root of a number.

```python
print(math.sqrt(25))  # Output: 5.0
# Explanation: The square root of 25 is 5.
```

---

### 4. `math.pow(x, y)`
**Description:**  
Returns `x` raised to the power of `y`.

```python
print(math.pow(2, 3))  # Output: 8.0
# Explanation: 2 to the power of 3 equals 8.
```

---

### 5. `math.fabs(x)`
**Description:**  
Returns the absolute (positive) value of a number.

```python
print(math.fabs(-7))  # Output: 7.0
# Explanation: The absolute value of -7 is 7.
```

---

### 6. `math.factorial(x)`
**Description:**  
Returns the factorial of a number (x!).

```python
print(math.factorial(5))  # Output: 120
# Explanation: 5! = 5 × 4 × 3 × 2 × 1 = 120
```

---

### 7. `math.gcd(a, b)`
**Description:**  
Returns the greatest common divisor of two numbers.

```python
print(math.gcd(24, 36))  # Output: 12
# Explanation: 12 is the largest number that divides both 24 and 36.
```

---

### 8. `math.pi` and `math.e`
**Description:**  
Mathematical constants π (pi) and e (Euler’s number).

```python
print(math.pi)  # Output: 3.141592653589793
print(math.e)   # Output: 2.718281828459045
# Explanation: These are standard mathematical constants.
```

---

### 9. `math.log(x, base)`
**Description:**  
Returns the logarithm of a number with an optional base.

```python
print(math.log(10))       # Output: 2.302585092994046 (natural log)
print(math.log(100, 10))  # Output: 2.0 (base 10)
# Explanation: log(100) base 10 equals 2.
```

---

### 10. Trigonometric Functions – `sin()`, `cos()`, `tan()`
**Description:**  
Used to calculate trigonometric ratios.

```python
print(math.sin(math.pi / 2))  # Output: 1.0
print(math.cos(0))            # Output: 1.0
print(math.tan(math.pi / 4))  # Output: 1.0
# Explanation: These are basic trigonometric identities.
```

---

### 11. `math.degrees()` and `math.radians()`
**Description:**  
Converts between radians and degrees.

```python
print(math.degrees(math.pi))  # Output: 180.0
print(math.radians(180))      # Output: 3.141592653589793
# Explanation: 180 degrees equals π radians.
```

---

### 12. `math.trunc(x)`
**Description:**  
Removes the decimal part of a number (truncates towards zero).

```python
print(math.trunc(4.99))  # Output: 4
# Explanation: Removes the fractional part without rounding.
```

---

### 13. `math.modf(x)`
**Description:**  
Splits a float into fractional and integer parts.

```python
print(math.modf(3.14))  # Output: (0.14000000000000012, 3.0)
# Explanation: Returns a tuple (fractional_part, integer_part).
```

---

### 14. `math.isfinite(x)`, `math.isinf(x)`, `math.isnan(x)`
**Description:**  
Classifies numbers as finite, infinite, or NaN (Not a Number).

```python
print(math.isfinite(10))      # Output: True
print(math.isinf(math.inf))   # Output: True
print(math.isnan(math.nan))   # Output: True
# Explanation: Tests the type of numeric value.
```

---

## 💻 Full Example Code

```python
import math

print("math.ceil(4.2) =", math.ceil(4.2))
print("math.floor(4.9) =", math.floor(4.9))
print("math.sqrt(25) =", math.sqrt(25))
print("math.pow(2, 3) =", math.pow(2, 3))
print("math.fabs(-7) =", math.fabs(-7))
print("math.factorial(5) =", math.factorial(5))
print("math.gcd(24, 36) =", math.gcd(24, 36))
print("math.pi =", math.pi)
print("math.e =", math.e)
print("math.log(10) =", math.log(10))
print("math.log(100, 10) =", math.log(100, 10))
print("math.sin(math.pi/2) =", math.sin(math.pi / 2))
print("math.cos(0) =", math.cos(0))
print("math.tan(math.pi/4) =", math.tan(math.pi / 4))
print("math.degrees(math.pi) =", math.degrees(math.pi))
print("math.radians(180) =", math.radians(180))
print("math.trunc(4.99) =", math.trunc(4.99))
print("math.modf(3.14) =", math.modf(3.14))
print("math.isfinite(10) =", math.isfinite(10))
print("math.isinf(math.inf) =", math.isinf(math.inf))
print("math.isnan(math.nan) =", math.isnan(math.nan))
```

---
---

## 📎 Author
👩‍💻 **Created by:** Rezvan Panah  
📅 **Year:** 2025  
💬 **Language:** Python 3.10  
🎯 **Purpose:** Teaching Python functions in a clear and beginner-friendly way.

---

## 💖 Support & Feedback
If this repository helped you, please consider:
- ⭐ **Starring** the repo  
- 🗨️ **Commenting** your thoughts  
- 📢 **Sharing** it with others learning Python  

Your feedback motivates more free educational content!

