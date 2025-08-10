### ✅ **Question (Problem Statement)**

What will be the output of the following tail-recursive pseudocode for calculating power?

### 🧠 **Pseudo Code**

```
function power(base, exp, acc):
if exp == 0:
    return acc
return power(base, exp - 1, acc * base)

print(power(2, 3, 1))
```

---

### 🔍 **Step-by-Step Execution**

**Call 1:** `power(2, 3, 1)`

- `exp != 0` → call `power(2, 2, 1 * 2)` → `power(2, 2, 2)`

**Call 2:** `power(2, 2, 2)`

- `exp != 0` → call `power(2, 1, 2 * 2)` → `power(2, 1, 4)`

**Call 3:** `power(2, 1, 4)`

- `exp != 0` → call `power(2, 0, 4 * 2)` → `power(2, 0, 8)`

**Call 4:** `power(2, 0, 8)`

- `exp == 0` → return `8`

---

### 🖨️ **Final Output on Console**

**✅ Correct Output:** `8`


