# crackyourjs

#### Array Techniques

- Sorting then scanning with right and left pointers (two pointers)
- When considering maximums and minimums, usual cases are updating some result when looking at each new element with a greater than or less than comparison of the current calculation (non constructable change). So when thinking of solutions, test the smaller, equal to and greater than cases to find understanding of how to solve the underlying problem. When creating test cases, design these with different possible greater than and less than checks in mind. (Non Constructable Change)
- For every array question, pay attention to whether we are positive numbers, negative numbers and how the number 0 works
- Sometimes we need to prefill an array to a certain length. In JS useful syntax to do this with is: new Array(array.length).fill(0);
- Off By One Errors are common, take the time to evaluate if there are off by one errors in looping structures or pointer comparisons
