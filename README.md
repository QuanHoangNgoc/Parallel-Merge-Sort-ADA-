# 📦 Parallel Merge Sort

---
## ✨ What is it?
Parallel Merge Sort is an optimized sorting algorithm that leverages parallel processing to enhance the performance of the traditional merge sort. This project implements a parallel version of the merge sort algorithm using Python, allowing for efficient sorting of large datasets.

---
## 🤔 Why do we do it?
Sorting is a fundamental operation in computer science, and with the increasing size of datasets, traditional sorting methods can become inefficient. By utilizing parallel algorithms, we aim to significantly reduce the time complexity of sorting operations, making it feasible to handle larger datasets more effectively.

---
## 👥 Who is the user?
This project is intended for:
- **Data Scientists**: Who need to sort large datasets quickly.
- **Developers**: Looking for efficient algorithms to integrate into their applications.
- **Students**: Learning about algorithms and parallel processing.

### 🚀 Demo
Here’s a quick demonstration of the Parallel Merge Sort in action:

```python
input_data = [15, 10, 16, 0, 0, 10, 11, 9, 7, 4, 6, 16, 8, 15, 5]
sorted_output = parallelMergeSort(input_data)
print(sorted_output)  # Output: [0, 0, 4, 5, 6, 7, 8, 9, 10, 10, 11, 15, 15, 16, 16]
```

### 📊 Results
The parallel implementation has shown to outperform the traditional merge sort, especially with larger datasets. For example, the average run time for sorting 100,000 elements was significantly lower with the parallel approach.

<img src="https://github.com/user-attachments/assets/95293721-2076-47a3-8cae-c848f4d542cd" alt="visual" width="400"/>

---
## 🔧 How did we do it?
The development process involved several key steps:
1. **Problem Abstraction**: Defined the input and output requirements for the sorting algorithm.
2. **Algorithm Design**: Designed a parallel version of the merge sort algorithm.
3. **Implementation**: Utilized Python's `multiprocessing` library to handle parallel processing.
4. **Validation**: Conducted extensive testing to ensure the accuracy and efficiency of the algorithm.

## ⚙️ Frameworks and Tools Used
- **Python**: The primary programming language used for its simplicity and readability.
- **Multiprocessing Library**: Used to enable parallel execution of the merge sort algorithm, allowing multiple processors to work simultaneously.
- **NumPy**: Utilized for efficient array manipulation and random number generation.

---
## 📚 What did you learn?
Through this project, we learned:
- The intricacies of parallel computing and its impact on algorithm performance.
- How to effectively manage processes and data sharing in Python.
- The importance of testing and validation in algorithm development.

---
## 🏆 Achievements
- Successfully implemented a parallel merge sort algorithm that outperforms the traditional version for large datasets.
- Conducted tests with varying dataset sizes, demonstrating the scalability of the solution.
- Received positive feedback from users regarding the efficiency and ease of use of the algorithm.

---
## ⚙️ How to Install and Run the Project
1. **Clone the repository**:
2. **Install dependencies**:
3. **Run the notebook**:

---
## 📖 How to Use the Project
To use the Parallel Merge Sort, simply call the `parallelMergeSort` function with your list of integers as the argument:

```python
sorted_list = parallelMergeSort(your_list)
```

---
## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

