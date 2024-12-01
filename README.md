# LC-1346.-Check-If-N-and-Its-Double-Exist

**Intuition**
This problem is designed to help beginners get comfortable with basic array operations and the implementation of basic data structures. We are given an array and our goal is to find out if there are two different indices, represented by i and j, where the value of one is twice the value of the other.

**How to interpret the three conditions:**
i and j must be different indices. This might seem like an obvious point unless you consider that 0=2×0. Without this condition, we'd be able to count just one 0 in the array as satisfying the goal. With this condition, an array would need two 0s to satisfy the conditions.
0 <= i, j < arr.length just means that the indices are within the bounds of the array. This condition doesn't mean much, it's essentially a requirement for any array-based algorithm.
arr[i] == 2 * arr[j] is how we know i needs to be double j.

**Complexity**
Time complexity:Runtime 0 ms( Beats 100.00% )
Space complexity: Memory 13.53 MB
