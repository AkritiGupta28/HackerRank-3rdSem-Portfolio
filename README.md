# HackerRank 3rd Sem Portfolio

**Student Name:** Akriti Gupta  
**Student ID:** R25EF020  
**HackerRank Profile:** [Akriti Gupta on HackerRank]([https://www.hackerrank.com/profile/h25020101180](https://www.hackerrank.com/profile/h25020102959))  
**Badge Earned:** Problem Solving Badge


\---



\## Complexity Analysis Summary Table



| No. | Problem Name | Topic / Category | Time Complexity | Space Complexity | Status |

|---|---|---|---|---|---|

| 1 | Diagonal Difference | 2D Arrays | $\\mathcal{O}(N)$ | $\\mathcal{O}(1)$ | Accepted |

| 2 | Dynamic Array | Data Structures | $\\mathcal{O}(N + Q)$ | $\\mathcal{O}(N + Q)$ | Accepted |

| 3 | Time Conversion | Strings \& Logic | $\\mathcal{O}(1)$ | $\\mathcal{O}(1)$ | Accepted |

| 4 | Compare the Triplets | Implementation | $\\mathcal{O}(1)$ | $\\mathcal{O}(1)$ | Accepted |

| 5 | Sparse Arrays | Hash Maps | $\\mathcal{O}(N + Q)$ | $\\mathcal{O}(N)$ | Accepted |



\---



\## Problem Approaches



\### 1. Diagonal Difference

Calculated primary (`arr\[i]\[i]`) and secondary (`arr\[i]\[n-1-i]`) diagonal sums in a single pass through the matrix, achieving $\\mathcal{O}(N)$ time complexity and $\\mathcal{O}(1)$ auxiliary space.



\### 2. Dynamic Array

Utilized a `List<List<Integer>>` to manage dynamic sequences and bitwise XOR (`x ^ lastAnswer`) for sequence indexing, reducing query handling to $\\mathcal{O}(1)$ per query.



\### 3. Time Conversion

Parsed 12-hour AM/PM string formats using basic string manipulation and converted hours according to 24-hour military time rules in constant $\\mathcal{O}(1)$ time.



\### 4. Compare the Triplets

Executed element-wise comparative checks across fixed 3-element arrays in a single loop, tracking ratings scores in $\\mathcal{O}(1)$ time and space.



\### 5. Sparse Arrays

Utilized a `HashMap<String, Integer>` to store string frequencies in $\\mathcal{O}(N)$ pre-processing time, enabling $\\mathcal{O}(1)$ lookup speed per query and reducing overall complexity from $\\mathcal{O}(N \\times Q)$ to $\\mathcal{O}(N + Q)$.

