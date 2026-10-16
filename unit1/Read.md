🎯 Objectives of Unit 1
In this unit, the following array concepts and operations are implemented:
<table>
<tr>
<th>Sr. No.</th>
<th>Topic</th>
<th>Concept Covered</th>
</tr>

<tr>
<td>01</td>
<td>One-Dimensional Array</td>
<td>Declaration, initialization and traversal</td>
</tr>

<tr>
<td>02</td>
<td>Two-Dimensional Array</td>
<td>Rows, columns and nested traversal</td>
</tr>

<tr>
<td>03</td>
<td>Array Insertion</td>
<td>Inserting an element at a given position</td>
</tr>

<tr>
<td>04</td>
<td>Array Deletion</td>
<td>Deleting an element from a given position</td>
</tr>

<tr>
<td>05</td>
<td>Array Searching</td>
<td>Searching for an element</td>
</tr>

<tr>
<td>06</td>
<td>Array Rotation</td>
<td>Rotating array elements</td>
</tr>

<tr>
<td>07</td>
<td>Greatest Element</td>
<td>Finding the largest element</td>
</tr>

</table>

📊 01 — One-Dimensional Array
<details>
<summary><b>Click here to view details</b></summary>


📌 Problem Statement
Create a one-dimensional array, store elements in it and display the elements.
💡 Approach
1. Declare a one-dimensional array.
2. Initialize the array with elements.
3. Traverse the array using a for loop.
4. Display each element.
💻 Example
int a[5] = {10, 20, 30, 40, 50};

📤 Sample Output
10 20 30 40 50

⏱️ Complexity
<table>
<tr>
<th>Operation</th>
<th>Time Complexity</th>
</tr>

<tr>
<td>Access</td>
<td>O(1)</td>
</tr>

<tr>
<td>Traversal</td>
<td>O(n)</td>
</tr>

</table>

Space Complexity: O(n)
</details>

🔢 02 — Two-Dimensional Array
<details>
<summary><b>Click here to view details</b></summary>


📌 Problem Statement
Create a two-dimensional array using rows and columns and display its elements.
💡 Approach
1. Declare a 2D array.
2. Initialize the elements.
3. Use nested for loops to traverse the array.
4. Display the elements row by row.
💻 Example
int a[3][3] =
{
    {1, 2, 3},
    {4, 5, 6},
    {7, 8, 9}
};

📤 Sample Output
1 2 3
4 5 6
7 8 9

⏱️ Complexity
Time Complexity: O(n × m)
Space Complexity: O(n × m)
</details>

➕ 03 — Array Insertion
<details>
<summary><b>Click here to view details</b></summary>


📌 Problem Statement
Insert a new element at a specified position in a one-dimensional array.
💡 Approach
1. Select the required position.
2. Start from the last element.
3. Shift elements one position towards the right.
4. Insert the new element at the required position.
5. Increase the logical size of the array.
📊 Example
Before Insertion:

10 20 30 40

Insert 25

After Insertion:

10 20 25 30 40

⏱️ Complexity
Time Complexity: O(n)
Auxiliary Space: O(1)
</details>

➖ 04 — Array Deletion
<details>
<summary><b>Click here to view details</b></summary>


📌 Problem Statement
Delete an element from a specified position in an array.
💡 Approach
1. Select the position of the element to be deleted.
2. Shift all following elements one position towards the left.
3. Reduce the logical size of the array.
📊 Example
Before Deletion:

10 20 30 40 50

Delete 30

After Deletion:

10 20 40 50

⏱️ Complexity
Time Complexity: O(n)
Auxiliary Space: O(1)
</details>

🔍 05 — Searching in an Array
<details>
<summary><b>Click here to view details</b></summary>


📌 Problem Statement
Search for a given element in an array and display its position if it is present.
💡 Approach
1. Start from the first element.
2. Compare each element with the search value.
3. If a match is found, display its position.
4. If no match is found, display an appropriate message.
📊 Example
Array:

10 20 30 40 50

Search Element:

30

Result:

Element found at index 2

⏱️ Complexity
<table>
<tr>
<th>Case</th>
<th>Time Complexity</th>
</tr>

<tr>
<td>Best Case</td>
<td>O(1)</td>
</tr>

<tr>
<td>Worst Case</td>
<td>O(n)</td>
</tr>

</table>

Space Complexity: O(1)
</details>

🔄 06 — Array Rotation
<details>
<summary><b>Click here to view details</b></summary>


📌 Problem Statement
Rotate the elements of an array by moving the first element to the last position.
📊 Example
Before Rotation:

10 20 30 40 50

After Left Rotation:

20 30 40 50 10

💡 Approach
1. Store the first element in a temporary variable.
2. Shift the remaining elements one position towards the left.
3. Place the stored element at the last position.
⏱️ Complexity
Time Complexity: O(n)
Auxiliary Space: O(1)
</details>

🏆 07 — Greatest Element in an Array
<details>
<summary><b>Click here to view details</b></summary>


📌 Problem Statement
Create an array containing the elements A, B, and C and find the greatest element.
💡 Approach
1. Store A, B, and C in an array.
2. Assume the first element is the greatest.
3. Compare it with the remaining elements.
4. Update the greatest element whenever a larger element is found.
5. Display the greatest element.
📊 Example
Array:

A B C

Greatest Element:

C

For these character values:
A < B < C

Therefore, C is the greatest element among the three.
⏱️ Complexity
Time Complexity: O(n)
Auxiliary Space: O(1)
</details>

📈 Complexity Summary
<table>
<tr>
<th>Array Operation</th>
<th>Time Complexity</th>
<th>Auxiliary Space</th>
</tr>

<tr>
<td>Access</td>
<td>O(1)</td>
<td>O(1)</td>
</tr>

<tr>
<td>Traversal</td>
<td>O(n)</td>
<td>O(1)</td>
</tr>

<tr>
<td>Insertion</td>
<td>O(n)</td>
<td>O(1)</td>
</tr>

<tr>
<td>Deletion</td>
<td>O(n)</td>
<td>O(1)</td>
</tr>

<tr>
<td>Searching</td>
<td>O(n)</td>
<td>O(1)</td>
</tr>

<tr>
<td>Rotation</td>
<td>O(n)</td>
<td>O(1)</td>
</tr>

<tr>
<td>Greatest Element</td>
<td>O(n)</td>
<td>O(1)</td>
</tr>

</table>

Note: The space complexity shown above represents the extra/auxiliary space used by the operation. The array itself requires O(n) storage.

📸 Screenshots
Screenshots of the program outputs can be stored inside the Screenshots folder.
Example
unit1/
│
├── README.md
│
├── 1D_Array.cpp
├── 2D_Array.cpp
├── Array_Insertion.cpp
├── Array_Deletion.cpp
├── Array_Search.cpp
├── Array_Rotation.cpp
├── Greatest_Element.cpp
│
└── Screenshots/
    ├── 1D_Array.png
    ├── 2D_Array.png
    ├── Array_Insertion.png
    ├── Array_Deletion.png
    ├── Array_Search.png
    ├── Array_Rotation.png
    └── Greatest_Element.png

🎓 Learning Outcomes
After completing Unit 1, I learned:
- The basic concept of arrays.
- How to declare and initialize one-dimensional arrays.
- How to declare and work with two-dimensional arrays.
- How array indexing works in C++.
- How to traverse array elements.
- How to insert elements into an array.
- How to delete elements from an array.
- How to search for an element.
- How to rotate an array.
- How to find the greatest element in an array.
- How to analyze time and space complexity.
- How to organize and document C++ programs using GitHub.
🛠️ Technologies Used
<table>
<tr>
<td><b>Programming Language</b></td>
<td>C++</td>
</tr>

<tr>
<td><b>Data Structure</b></td>
<td>Array</td>
</tr>

<tr>
<td><b>Development Platform</b></td>
<td>GitHub</td>
</tr>

</table>
