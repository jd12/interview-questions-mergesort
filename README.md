# interview-questions-mergesort

Update this file with your answers. If you write outside files drop them in the repository

1. **Merging with smaller auxiliary array.** Suppose that the subarray `a[0]` to `a[n−1]` is sorted and the subarray `a[n]` to `a[2*n−1]` is sorted. How can you merge the two subarrays so that `a[0]` to `a[2*n−1]` is sorted using an auxiliary array of length n (instead of 2n)?

*Hint: copy only the left half into the auxiliary array.*

2. **Counting inversions.** An inversion in an array `a[]` is a pair of entries `a[i]` and `a[j]` such that `i < j` but `a[i] > a[j]`. Given an array, design a linearithmic algorithm to count the number of inversions.

*Hint: count while mergesorting.*

3. **Shuffling a linked list.** Given a singly-linked list containing n items, rearrange the items uniformly at random. Your algorithm should consume a logarithmic (or constant) amount of extra memory and run in time proportional to `n log n` in the worst case.

Hint: design a linear-time subroutine that can take two uniformly shuffled linked lists of sizes n<sub>1</sub> and n<sub>2</sub> and combined them into a uniformly shuffled linked lists of size n<sub>1</sub> + n<sub>2</sub>
