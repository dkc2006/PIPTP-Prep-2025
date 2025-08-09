### ✅ **Question (Problem Statement)**

What will be the output of the following code?

### 🧠 **Pseudo Code:**

```
function tailSum(n, acc):
if n == 0:
return acc
return tailSum(n - 1, acc + n)

print(tailSum(3, 0))

```


---

### 🔍 **Step-by-Step Execution:**

1. **Initial Call:** `tailSum(3, 0)`
    - `n != 0` → calls `tailSum(2, 0 + 3)` → `tailSum(2, 3)`

2. **Second Call:** `tailSum(2, 3)`
    - `n != 0` → calls `tailSum(1, 3 + 2)` → `tailSum(1, 5)`

3. **Third Call:** `tailSum(1, 5)`
    - `n != 0` → calls `tailSum(0, 5 + 1)` → `tailSum(0, 6)`

4. **Base Case:** `n == 0` → returns `acc = 6`

---

### 🖨️ **Final Output on Console:**

---

`Correct output is:` **6** ✅
