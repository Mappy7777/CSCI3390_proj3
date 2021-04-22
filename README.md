
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

3.
a. For 3x4 cores the output is as follows:

number of remaining verticies is 6949798

number of remaining verticies is 33232

number of remaining verticies is 374

number of remaining verticies is 0

number of loops is 4 loops

Luby's algorithm completed in 788s.


b. 

4x2: Luby's algorithm completed in 1156s.

2x2: Luby's algorithm completed in 2899s.

Lowering the number of cores significantly reduced the speed at which the algorithim was able to be completed in.


