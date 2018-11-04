# Merge sort

## Take 1

* Implementation of normal merge sort

## Take 2

  1. Pass temporary array once instead of creating again and again in merge
  2. When size less than threshold, use insertion sort

## Take 3

  1. Avoid unnecessary copying of values between the arrays. Copy the full array into buffer once and use it for sorting
  2. Use a while instead of for loop!

Use following commands to compile and run

* Compile `javac -d bin -sourcepath src src/pxp180031/MergeSort.java`
* Run `java -cp bin pxp180031.MergeSort <num_elements> <choice>`

## Choices

1. Insertion sort
2. Merge sort (Take 1)
3. Merge sort (Take 2)
4. Merge sort (Take 3)
