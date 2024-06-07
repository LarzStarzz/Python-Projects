# Python_Sorting_Algorithms

Anneliese Larson
M3 | Project 1: Sorting Algorithms

This code is used to test the time complexitys of several differnt sorting alorithms which include Insertion, Bubble, Merge, Quick, and Radix sort. Each algorithm was tested using differnt size data sets from 1,000, 10,000, 100,000, 1,000,000, and 10,000,000 ranging from integers of 0 to 2,147,483,647.

All functions which perform each algorithm are named as such, a few have supporting functions with a comment to which algorithm it belongs to. Aditional supporting functions include timing, and the creation of the random generated datasets. 

User Guide:
Download the python file called "Project_1.py" and open and run it on any code application or websites such has jupiter notebook or goole colab. To run this program all you have to do it start or run the program on whichever application you use.

When running these tests some algorithms take longer than others. For this we have this section which you will comment and uncomment which desired algorithms to test. This takes place in the main function at the bottom. For example to run for insertion sort, uncomment the first two line in the for loop. It will print the results of each size data sets with the timing in seconds with how long the algorithm took. 

         for i, data in data_sets.items():\n",
            #timing = timer(insertion_sort, data)\n",
            #print(f\"Inserction sort of size {i}: {timing:.3f} seconds\")\n",
            #timing = timer(bubble_sort, data)\n",
            #print(f\"Bubble sort of size {i}: {timing:.3f} seconds\")\n",
            #timing = timer(merge_sort, data)\n",
            #print(f\"Merge sort of size {i}: {timing:.3f} seconds\")\n",
            #timing = timer(quick_sort, data)\n",
            #print(f\"Quick sort of size {i}: {timing:.3f} seconds\")\n",
            #timing = timer(radix_sort, data)\n",
            #print(f\"Radix sort of size {i}: {timing:.3f} seconds\")\n",

**Warning**
While runnning these time analysis test, there will be algorithms which take a considereable amount of time to complete. Once a test takes longer than 20min, terminate the program as it can take longer than an hour to run a test. 
