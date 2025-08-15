### ✅ **Question (Problem Statement)**

What will be the output of the following pseudocode that prints numbers **after** the recursive call?

---

### 🧠 **Pseudo Code**

```
function printUp(n):
    if n == 0:
        return
    printUp(n - 1)
    print(n)
printUp(3)

```

---

### 🔍 **Step-by-Step Execution**

**Call 1:** `printUp(3)`
- `n != 0` → call `printUp(2)`

**Call 2:** `printUp(2)`
- `n != 0` → call `printUp(1)`

**Call 3:** `printUp(1)`
- `n != 0` → call `printUp(0)`

**Call 4:** `printUp(0)`
- `n == 0` → return

---

### 📤 **Return & Print Sequence**

- Returning from **Call 3:** print `1`
- Returning from **Call 2:** print `2`
- Returning from **Call 1:** print `3`

---

### 🖨️ **Final Output on Console**

**✅ Correct Output:** `1 2 3 `


---
