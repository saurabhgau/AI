# Overview
This C++ program implements a friend recommendation system based on a given table of relationships between candidates. The system employs depth-first search (DFS) to explore relationships and recommend friends for a given candidate.

# Input: 
Enter the selected candidate character when prompted.

# Output: 
The program will output the total number of cases and for each case, it will display the candidate followed by their recommended friends based on the relationships.

# Approach

# Data Structure: 
The program utilizes a vector of maps to represent the relationship table. Each character is mapped to a vector containing its friends.

# DFS Algorithm: 
DFS is applied to traverse the relationship graph starting from the selected candidate character. It explores all reachable friends and recommends them.

# Output Generation:
For a given candidate, all possible cases are considered where the candidate is recommended by different characters. Each case is enumerated, and the recommended friends are displayed.

# Testing

Automated test cases can be implemented to ensure the correctness and robustness of the program. Test cases should cover various scenarios, including:

# Inputting different candidate characters

Testing with different relationship tables
Verifying output for known relationships

# Sample Test Case:
# Input: 
M C
# Expected Output:
L,M,N,A,K,B,C,J,V,W,X,Y,Z
# Contributors
Saurabh Gautam
