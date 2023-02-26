`# Processes and signals

In this project, I learned about handling process ID's and signals in Bash with `ps`, `pgrep`, `pkill`, `pkill`, `exit`, and `trap`.

## Tasks 📃
- 0. What is my PID
     - [0-what-is-my-pid](https://github.com/richard-1257/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/0-what-is-my-pid):  Bash script that displays its own PID.
     
- 1. List your processes
     - [1-list_your_processes](https://github.com/richard-1257/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/1-list_your_processes): Bash script that displays a list of currently running processes.
     - Shows all processes for all users, including those not featuring a TTY.
     - Processes are displayed in a user-oriented hierarchy.
     
- 2. Show your Bash PID
     - [2-show_your_bash_pid](https://github.com/richard-1257/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/2-show_your_bash_pid): Bash script that displays lines containing the `bash` keyword based on the script defined in `1-list_your_processes`.
     
- 3. Show your Bash PID made easy
     - [3-show_your_bash_pid_made_easy](https://github.com/richard-1257/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/3-show_your_bash_pid_made_easy): Bash script that displays the PID along with the process name of processes who name contains the word `bash`.
     
- 4. To infinity and beyond
     - [4-to_infinity_and_beyond](https://github.com/richard-1257/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/4-to_infinity_and_beyond):  Bash script that displays `To infinity and beyond` indefinitely with a `sleep 2` in between each iteration.
    
- 5. Don't stop me now!
     - [5-dont_stop_me_now](https://github.com/richard-1257/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/5-dont_stop_me_now):  Bash script that kills the 4-to_infinity_and_beyond process using `kill`.
     - Prints the list after each swap.
     - [101-O](https://github.com/richard-1257/sorting_algorithms/blob/master/101-O): Text file containing the best, average, and worst case time complexities of the Cocktail Shaker Sort algorithm, one per line.
     
- 6. Counting sort
     - [102-counting_sort.c](https://github.com/richard-1257/sorting_algorithms/blob/master/102-counting_sort.c): C function that sorts an array of integers in ascending order using the Counting Sort algorithm.
     - Assumes that the array will only contain numbers `>= 0`.
     - Prints the counting array after it has been initialized.
     - [102-O](https://github.com/richard-1257/sorting_algorithms/blob/master/102-O): Text file containing the best, average, and worst case time complexities of the Counting Sort algorithm, one per line.
     
- 7. Merge sort
     - [103-merge_sort.c](https://github.com/richard-1257/sorting_algorithms/blob/master/103-merge_sort.c): C function that sorts an array of integers in ascending order using the Merge Sort algorithm.
     - Implements the `top-down` Merge Sort algorithm
         - When an array is divided, the size of the left subarray is always less than or equal to the size of the right subarray.
         - Always sorts the left subarray before the right one.
     - Prints subarrays each time they are merged.
     - [103-O](https://github.com/richard-1257/sorting_algorithms/blob/master/103-O): Text file containing the best, average, and worst case time complexities of the Merge Sort algorithm, one per line.

- 8. Heap sort
     - [104-heap_sort.c](https://github.com/richard-1257/sorting_algorithms/blob/master/104-heap_sort.c): C function that sorts an array of integers in ascending order using the Heap Sort algorithm.
     - Implements the `sift-down` Heap Sort algorithm.
     - Prints the array after each swap.
     - [104-O](https://github.com/richard-1257/sorting_algorithms/blob/master/104-O): Text file containing the best, average, and worst case time complexiites of the Heap Sort algorithm, one per line.
     
- 9. Radix sort
     -[105-radix_sort.c](https://github.com/richard-1257/sorting_algorithms/blob/master/105-radix_sort.c): C function that sorts an array of integers in ascending order using the Radix Sort algorithm.
     - Implements the Least-Significant-Digit (LSD) Radix Sort algorithm.
     - Assumes that the array will only contain numbers `>= 0`.
     - Prints the array for each significant digit increase.
     - [105-O](https://github.com/richard-1257/sorting_algorithms/blob/master/105-O): Text file containing the best, average, and worst case time complexities of the Radix Sort algorithm, one per line.
     
- 10. Bitonic sort
      - [106-bitonic_sort.c](https://github.com/richard-1257/sorting_algorithms/blob/master/106-bitonic_sort.c):  C function that sorts an array of integers in ascending order using the Bitonic Sort algorithm.
      - Assumes that `size` is a power of 2 (ie. `size` can be expressed as `2^k` where `k >= 0`).
      - Prints subarrays each time they are merged.
      - [106-O](https://github.com/richard-1257/sorting_algorithms/blob/master/106-O): Text file containing the best, average, and worst case time complexities of the Bitonic Sort algorithm, one per line.
      
- 11. Quick Sort - Hoare Partition scheme
      - [107-quick_sort_hoare.c](https://github.com/richard-1257/sorting_algorithms/blob/master/107-quick_sort_hoare.c): C function that sorts an array of integers in ascending order using the Quick Sort algorithm.
      - Implements the Hoare partition scheme.
      - Always uses the last elemement of the partition being sorted as the pivot.
      - Prints the array after each swap.
      - [107-O](https://github.com/richard-1257/sorting_algorithms/blob/master/107-O): Text file containing the best, average, and worst case time complexities of the Quick Sort Hoare Partition cheme algorithm, one per line.
      
- 12. Dealer
      - [1000-sort_deck.c](https://github.com/richard-1257/sorting_algorithms/blob/master/1000-sort_deck.c): C function that sorts a `deck_node_t` doubly-linked list deck of cards.
      - Assumes that there are exactly 52 elements in the doubly-linked list.
      - Orders the deck from spades to diamonds and from aces to kings.
