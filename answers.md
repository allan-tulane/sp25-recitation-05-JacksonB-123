# CMPS 2200 Reciation 5
## Answers

**Name:**______Jackson Burch___________________


Place all written answers from `recitation-05.md` here for easier grading.







- **1b.**
results from shuffeled sorted list sizes=[100, 200, 500, 1000, 2000, 5000, 10000, 20000, 50000, 100000]

|      n |   qsort-fixed-pivot |   qsort-random-pivot |
|--------|---------------------|----------------------|
|    100 |               0.096 |                0.170 |
|    200 |               0.235 |                0.300 |
|    500 |               0.793 |                1.022 |
|   1000 |               1.411 |                2.164 |
|   2000 |               3.311 |                4.669 |
|   5000 |               8.625 |               13.451 |
|  10000 |              17.183 |               29.412 |
|  20000 |              70.079 |               69.934 |
|  50000 |             157.112 |              188.123 |
| 100000 |             338.983 |              376.542 |

results from shuffled sorted list sizes=[100, 300, 700, 1500, 3000, 7000, 15000, 30000, 70000, 100000]

|      n |   qsort-fixed-pivot |   qsort-random-pivot |
|--------|---------------------|----------------------|
|    100 |               0.142 |                0.207 |
|    300 |               0.483 |                0.634 |
|    700 |               1.364 |                1.435 |
|   1500 |               2.133 |                3.097 |
|   3000 |               5.995 |                7.771 |
|   7000 |              12.616 |               19.132 |
|  15000 |              26.536 |               36.906 |
|  30000 |              67.928 |               87.247 |
|  70000 |             143.142 |              160.686 |
| 100000 |             180.808 |              220.307 |

results from shuffled unsorted sizes=[3, 1, 4, 1, 5, 9]

|   n |   qsort-fixed-pivot |   qsort-random-pivot |   selection-sort |
|-----|---------------------|----------------------|------------------|
|   3 |               0.006 |                0.009 |            0.051 |
|   1 |               0.001 |                0.000 |            0.000 |
|   4 |               0.005 |                0.007 |            0.029 |
|   1 |               0.000 |                0.000 |            0.000 |
|   5 |               0.004 |                0.006 |            0.032 |
|   9 |               0.007 |                0.013 |            0.108 |

results for unshuffled unsorted sizes=[300, 100, 50, 70]

|   n |   qsort-fixed-pivot |   qsort-random-pivot |   selection-sort | 
|-----|---------------------|----------------------|------------------|
| 300 |               3.243 |                0.391 |           19.023 |
| 100 |               0.530 |                0.194 |            2.490 |
|  50 |               0.117 |                0.055 |            3.464 |
|  70 |               0.235 |                0.141 |            1.812 | 


results for in sorted shuffled sizes=[20, 60, 90, 150, 200]

|   n |   qsort-fixed-pivot |   qsort-random-pivot |   selection-sort | 
|-----|---------------------|----------------------|------------------|
|  20 |               0.029 |                0.038 |            0.496 |
|  60 |               0.127 |                0.201 |            1.426 | 
|  90 |               0.139 |                0.179 |            2.974 |
| 150 |               0.214 |                0.305 |            6.369 |
| 200 |               0.215 |                0.305 |            8.131 |

results for unsorted shuffled sizes=[60, 90, 20, 60, 200]

|   n |   qsort-fixed-pivot |   qsort-random-pivot |   selection-sort |
|-----|---------------------|----------------------|------------------|
|  60 |               0.053 |                0.179 |            1.289 |
|  90 |               0.083 |                0.104 |            5.898 | 
|  20 |               0.028 |                0.039 |            0.443 | 
|  60 |               0.076 |                0.121 |            4.419 |  
| 200 |               0.184 |                0.259 |           25.517 | 

results from unshuffled unsorted sizes=[180,30, 200, 110, 130, 70, 220, 210]

|   n |   qsort-fixed-pivot |   qsort-random-pivot |   selection-sort |
|-----|---------------------|----------------------|------------------|
| 180 |               1.925 |                0.526 |           14.916 | 
|  30 |               0.074 |                0.061 |            5.668 |
| 200 |               2.258 |                0.424 |           24.413 | 
| 110 |               0.650 |                0.227 |            3.581 |
| 130 |               1.237 |                2.775 |           13.614 | 
|  70 |               0.157 |                0.092 |            8.382 | 
| 220 |               1.673 |                0.453 |           22.088 |
| 210 |               2.418 |                0.301 |           20.272 |

results from unshuffled sorted sizes=[30, 70, 110, 130, 180, 200, 210, 220]

|   n |   qsort-fixed-pivot |   qsort-random-pivot |   selection-sort |
|-----|---------------------|----------------------|------------------|
|  30 |               0.201 |                0.090 |            1.744 |
|  70 |               0.910 |                0.290 |            2.435 | 
| 110 |               0.913 |                0.222 |            3.717 | 
| 130 |               0.980 |                0.281 |           10.641 |    
| 180 |               1.290 |                0.308 |           17.264 |  
| 200 |               1.838 |                0.368 |            9.904 |  
| 210 |               3.666 |                0.464 |           26.954 |
| 220 |               2.666 |                0.416 |           14.787 | 

results from shuffled reverse sorted sizes=[120, 50, 30, 10]

|   n |   qsort-fixed-pivot |   qsort-random-pivot |   selection-sort |
|-----|---------------------|----------------------|------------------|
| 120 |               0.162 |                0.178 |            3.650 | 
|  50 |               0.086 |                0.093 |            0.744 | 
|  30 |               0.036 |                0.048 |            0.508 |  
|  10 |               0.008 |                0.011 |            0.093 | 

results from shuffled unsorted sizes=[50, 30, 120, 10]

|   n |   qsort-fixed-pivot |   qsort-random-pivot |   selection-sort |
|-----|---------------------|----------------------|------------------|
|  50 |               0.081 |                0.185 |            2.393 |
|  30 |               0.037 |                0.055 |            0.977 |
| 120 |               0.157 |                0.270 |           12.449 |
|  10 |               0.015 |                0.020 |            0.167 |

For the quick sort fixed pivot algorithm it has a wost case run time of O(n^2) when the list is alredy sorted. When the order is shuffled for a quick sort fixed pivot algorithm its run time is a O(n log n). The input needs to be shuffled for quick sort fixed pivot algoritms to be practical.

For quick sort random pivot the run time is O(n log n). Overall this algoruitm is the most consistent and reliable

As discussed in class selection sort is easy to implemet and it always runs at an inneffient run time of O(n^2), so it should be avoided especially with large lists




- **1c.**
on a shuffled and sorted algorithm of sizes=[20, 60, 90, 150, 200]

|   n |   qsort-fixed-pivot |   qsort-random-pivot |   selection-sort |   tim_sort |
|-----|---------------------|----------------------|------------------|------------|
|  20 |               0.021 |                0.028 |            0.240 |      0.003 |
|  60 |               0.095 |                0.083 |            1.133 |      0.004 |
|  90 |               0.094 |                0.166 |            1.848 |      0.007 |
| 150 |               0.181 |                0.350 |            4.449 |      0.011 |
| 200 |               0.252 |                0.422 |           22.514 |      0.022 |

time sort is signifcantly faster