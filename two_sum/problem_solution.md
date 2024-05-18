# Solution Explanation: Two Sum

**Purpose**

This solution finds the indices of the two numbers in an array that add up to a given target. The solution uses a hash table (dictionary) to achieve an efficient O(n) time complexity.

**Why Use a Hash Table?**

- A hash table allows for fast lookups and insertions, making it an ideal data structure for this problem.
- By storing the indices of the numbers in the hash table, we can quickly check if the complement (target - current number) exists.

**How It Works**

1. **Initialize a Hash Table**
   - Create an empty hash table (dictionary) to store the numbers and their corresponding indices.

2. **Iterate Through the Array**
   - Loop through each number in the array.
   - For each number, calculate its complement (target - current number).

3. **Check for Complement**
   - If the complement is already in the hash table, return the indices of the complement and the current number.
   - If the complement is not in the hash table, store the current number and its index in the hash table.

4. **Return the Result**
   - The function returns the indices of the two numbers that add up to the target.

**Detailed Steps**

1. **Initialize the Hash Table**
   - Start with an empty dictionary to store the numbers and their indices.

2. **Iterate Through the Array**
   - For each number in the array, calculate the complement by subtracting the current number from the target.

3. **Check for Complement**
   - If the complement exists in the hash table, return the indices of the complement and the current number.
   - If the complement does not exist, store the current number and its index in the hash table.

4. **Return the Result**
   - The function returns the indices of the two numbers as a list.

**Conclusion**

This solution efficiently finds the indices of the two numbers that add up to the target using a hash table for O(n) time complexity. By leveraging the fast lookup and insertion properties of the hash table, the solution ensures that each number is processed in constant time, resulting in an overall linear runtime.

[Problem Link](https://leetcode.com/problems/two-sum/description/)
