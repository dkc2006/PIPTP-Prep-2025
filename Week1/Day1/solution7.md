### ✅ **Question (Problem Statement)**

What will be the output of the following recursive function?

---

### 🧠 **Pseudo Code**

```
function sum(n)
    if n == 1
        return 1
    return n + sum(n - 1)
 print(sum(5))
 
```

---

### 🔍 **Step-by-Step Execution**

**Call 1:** `sum(5)` → `5 + sum(4)`

**Call 2:** `sum(4)` → `4 + sum(3)`

**Call 3:** `sum(3)` → `3 + sum(2)`

**Call 4:** `sum(2)` → `2 + sum(1)`

**Call 5:** `sum(1)` → returns `1`

---

### 📤 **Return & Calculation Sequence**

- Returning from **Call 5:** `sum(1) = 1`
- Returning from **Call 4:** `2 + 1 = 3`
- Returning from **Call 3:** `3 + 3 = 6`
- Returning from **Call 2:** `4 + 6 = 10`
- Returning from **Call 1:** `5 + 10 = 15`

---

### 🖨️ **Final Output on Console**

**✅ Correct Output:** `15`

---
