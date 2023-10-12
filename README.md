Remove Duplicates from Sorted List
Description
This Python program is a solution to the "Remove Duplicates from Sorted List" problem, a common coding challenge found on platforms like LeetCode. Given a sorted linked list, the program removes duplicate values, leaving only distinct elements. It does this by modifying the input list in place.

Problem Statement
Given a sorted linked list, delete all duplicates such that each element appears only once.

Example:

Input: 1 -> 1 -> 2
Output: 1 -> 2

Usage
You can use this Python code to remove duplicates from a sorted list. To use it, follow these steps:

Clone the repository or download the Python script.

Ensure you have Python installed on your machine.

Run the script with the sorted list as input, for example:

python
Copy code
from remove_duplicates import remove_duplicates

# Create a sorted list
sorted_list = [1, 1, 2, 3, 3]

# Remove duplicates
result = remove_duplicates(sorted_list)

print(result)  # Output: [1, 2, 3]
Approach
The program uses a simple approach that iterates through the sorted list while comparing adjacent elements. When a duplicate is found, it is removed from the list. The time complexity of this algorithm is O(n), where n is the number of elements in the list.

Contributing
If you'd like to contribute to this project or report issues, please feel free to submit a pull request or open an issue on the GitHub repository.
