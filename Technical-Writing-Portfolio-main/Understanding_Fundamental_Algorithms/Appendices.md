### Appendices

#### Appendix A: Sample Code for Sorting Algorithms

Here's some sample code for commonly used sorting algorithms for those who want to get their hands dirty.

    # Bubble Sort
    def bubbleSort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0, n-i-1):
            if arr[j] > arr[j+1]:
                arr[j], arr[j+1] = arr[j+1], arr[j]

2. 

    // Quick Sort
    public class QuickSort {
    static void quickSort(int[] arr, int low, int high) {
        if (low < high) {
            int pivot = partition(arr, low, high);
            quickSort(arr, low, pivot-1);
            quickSort(arr, pivot+1, high);
        }
    }
    }

#### Appendix B: Additional Resources for Search Algorithms

-   "Linear Search vs Binary Search" - A comprehensive article comparing the two most common search algorithms.
-   GitHub Repositories containing optimized versions of search algorithms.
