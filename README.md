
Submission for Shane Fitzpatrick and Michael Guyon

1.
|        Graph file       |           MIS file           | Is an MIS? |
| ----------------------- | ---------------------------- | ---------- |
| small_edges.csv         | small_edges_MIS.csv          | Yes        |
| small_edges.csv         | small_edges_non_MIS.csv      | No         |
| line_100_edges.csv      | line_100_MIS_test_1.csv      | Yes        |
| line_100_edges.csv      | line_100_MIS_test_2.csv      | No         |
| twitter_10000_edges.csv | twitter_10000_MIS_test_1.csv | Yes        |
| twitter_10000_edges.csv | twitter_10000_MIS_test_2.csv | Yes        |

2.
|        Graph file       |  # of iterations |    Runtime  |
| ----------------------- |------------------|-------------|
| small_edges.csv         | 1                | 1s          |
| line_100_edges.csv      | 3                | 1s          |
| twitter_100_edges.csv   | 2                | 1s          |
| twitter_1000_edges.csv  | 3                | 1s          |
| twitter_10000_edges.csv | 4                | 3s          |

3. **(3 points)**  
a. For 3x4 cores the output is as follows:  
# of remaining verticies is 6949798
# of remaining verticies is 33232
# of remaining verticies is 374
# of remaining verticies is 0

# of loops is 4 loops
==================================
Luby's algorithm completed in 788s.
==================================

b. Run `LubyMIS` on `twitter_original_edges.csv` with 4x2 cores and then 2x2 cores. Compare the running times between the 3 jobs with varying core specifications that you submitted in **3a** and **3b**.


