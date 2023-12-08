# CQ9-Diego-Marin

Weighted Uniform Strings

Time Complexity:
The solution iterates once through the string 's' of length n in 'calculateWeights', performing constant time operations. Then, it iterates through the list of queries of size q to check for the presence of each query in the set. Therefore, the total time complexity is O(n + q)

Space Complexity:
The Set<Integer> weights can potentially store a unique weight for each character in the string in the worst-case scenario, where all characters are different, leading to 
O(n) space complexity. The space used by results and other variables is negligible compared to this.


Mini-Max Sum

Time Complexity:
The solution iterates through the array once, where n is the size of the array. During this iteration, it performs constant-time operations to calculate the total sum and identify the minimum and maximum values. O(n)

Space Complexity:
The solution uses a fixed number of variables (minSum, maxSum, totalSum, min, max). These do not depend on the size of the input array, hence the space complexity is constant.
O(1)
