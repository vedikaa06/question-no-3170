# question-no-3170
Solution to the question no 3170 on leet code 

3170. Lexicographically Minimum String After Removing Stars
You are given a string s. It may contain any number of '*' characters. Your task is to remove all '*' characters.

While there is a '*', do the following operation:

Delete the leftmost '*' and the smallest non-'*' character to its left. If there are several smallest characters, you can delete any of them.
Return the lexicographically smallest resulting string after removing all '*' characters.

This function removes letters from a string s when it sees a '*'.

How it works:
It stores the positions of each character (a to z) in a stack-like structure.

When it finds a '*', it removes (marks as '*') the smallest alphabetical character that appeared before it.

After processing the whole string, it builds a new string without any '*'.
