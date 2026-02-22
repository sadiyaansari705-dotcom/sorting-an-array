Bubble Sort in C

This project contains a simple C program that implements the Bubble Sort Algorithm to sort an array in ascending order.

🧾 Program Description

The program:

Takes the number of elements as input.

Accepts array elements from the user.

Sorts the array using the Bubble Sort technique.

Displays the sorted array.

Bubble Sort works by repeatedly comparing adjacent elements and swapping them if they are in the wrong order.

🧠 Concepts Used

Arrays

Nested for loops

Swapping values using a temporary variable

Sorting algorithms

Input/Output functions (scanf, printf)

🔄 How Bubble Sort Works

Compare two adjacent elements.

Swap them if the first element is greater than the second.

Repeat this process for all elements.

After each pass, the largest element moves to its correct position.

Continue until the array is fully sorted.

⏱ Time Complexity

Best Case: O(n) (if optimized with flag — not used here)

Average Case: O(n²)

Worst Case: O(n²)

🚀 How to Run
🔹 Compile the Program
gcc filename.c -o output
🔹 Run the Program
./output

(For Windows)

output.exe
🧪 Sample Input
Enter number of elements: 5
Enter elements:
5 3 8 1 2
📤 Sample Output
Sorted array:
1 2 3 5 8
📂 Project Structure
📁 bubble-sort-c
 ├── main.c
 └── README.md
🔧 Possible Improvements

Add optimization using a swap flag.

Sort in descending order.

Implement other sorting algorithms (Selection Sort, Insertion Sort).

Add error handling for invalid input.


⭐ A more professional GitHub version with badges

⭐ Version with optimized Bubble Sort
