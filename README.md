# Day-07

# 🔍 MATLAB Sorting and Search Algorithms

This MATLAB project demonstrates the implementation and performance comparison of **Selection Sort**, **Linear Search**, and **Binary Search**.

---

## 📌 Features

### ✅ Selection Sort
Sorts an array by selecting the minimum element and swapping it with the current index.
```matlab
arr = [64, 25, 12, 22, 11];
% Output: [11, 12, 22, 25, 64]
```

### 🔄 Linear Search vs Binary Search
Search for a target value within an array and compare their time efficiency.
```matlab
array = 1:1000;
target = 550;
```

| 🔍 Algorithm       | ✅ Found | ⏱️ Execution Time (Example) |
|-------------------|----------|------------------------------|
| Linear Search      | true     | ~0.00005000 sec              |
| Binary Search      | true     | ~0.00000400 sec              |

```matlab
fprintf('Time Difference: Linear - Binary = %.8f seconds\n', linearTime - binaryTime);
```

---

## 🧠 Time Complexity Comparison

| Search Type   | Best Case | Worst Case | Time Complexity                |
|---------------|-----------|-------------|--------------------------------|
| Linear Search | O(1)      | O(n)        | Simple but slow for large data |
| Binary Search | O(1)      | O(log n)    | Fast but requires sorted data  |

---

## 📈 Outputs
- Sorted array is displayed with `disp()`
- Time comparisons use `tic`, `toc`, and `fprintf()`

---

## 🚀 How to Run
1. Open MATLAB
2. Copy and paste the `.m` file or script
3. Run the script to view results and performance

---

## 👨‍💻 Author
**Dinuka Avindra Silva**
