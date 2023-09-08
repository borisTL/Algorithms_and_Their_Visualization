# Binary Search Algorithm

Binary search is a classic search algorithm that finds the position of a target value within a sorted array. It is significantly faster than linear search.

## How it Works

1. **Find the Middle:** Determine the middle of the sorted array.
2. **Compare:** Compare the middle element with the target value.
3. **Divide the Array:**
    - If the target value is greater than the middle element, the search continues in the upper half of the array.
    - If the target value is less than the middle element, the search continues in the lower half of the array.
4. **Repeat:** This process repeats until the target value is found or the size of the subdivided array reduces to zero.

## Advantages

- Efficient for large datasets. Binary search is much faster than linear search.
- Economical in terms of the number of comparisons.

## Limitations

- Only works with sorted arrays.

## Complexity

- **Best Case:** O(1)
- **Average Case:** O(log n)
- **Worst Case:** O(log n)

## Example

Let's consider a sorted array `[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]`, and we are looking for the value `7`. 

1. Middle element: `5`
2. Since `7` is greater than `5`, we discard the first half of the array.
3. Our new array becomes: `[6, 7, 8, 9, 10]`
4. The new middle element: `8`
5. Since `7` is less than `8`, we discard the second half.
6. Now, our array is: `[6, 7]`
7. The next middle element: `6`
8. Since `7` is greater than `6`, the next element is our target, which is `7`.

Finally, the value `7` is found after several iterations.
