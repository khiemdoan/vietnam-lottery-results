# Vietnam Lottery (XSMB) Analysis

Using GitHub Action to automatically fetch and analyze results of the Vietnam lottery daily.

Download:

* [Full data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb.csv)
* [1-year data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb_1_year.csv)
* [2-year data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb_2_year.csv)
* [3-year data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb_3_year.csv)
* [5-year data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb_5_year.csv)

| Lotery      | Loto |
| :-----------: | :-----------: |
| <table><tr><td>Date</td><td>25-09-2023</td></tr><tr><td>Special</td><td>68779</td></tr><tr><td>First</td><td>71548</td></tr><tr><td>Second</td><td>82470, 84221</td></tr><tr><td rowspan="2">Third</td><td>03065, 37527, 36975</td></tr><tr><td>08761, 59916, 52871</td></tr><tr><td>Fourth</td><td>9605, 6005, 9627, 8751</td></tr><tr><td rowspan="2">Fifth</td><td>2897, 5156, 0016</td></tr><tr><td>2707, 3603, 9705</td></tr><tr><td>Sixth</td><td>665, 493, 022</td></tr><tr><td>Seventh</td><td>83, 14, 68, 77</td></tr></table> | <table><tr><td>First</td><td>Last</td></tr><tr><td>0</td><td>3, 5, 5, 5, 7</td></tr><tr><td>1</td><td>4, 6, 6</td></tr><tr><td>2</td><td>1, 2, 7, 7</td></tr><tr><td>3</td><td>-</td></tr><tr><td>4</td><td>8</td></tr><tr><td>5</td><td>1, 6</td></tr><tr><td>6</td><td>1, 5, 5, 8</td></tr><tr><td>7</td><td>0, 1, 5, 7, 9</td></tr><tr><td>8</td><td>3</td></tr><tr><td>9</td><td>3, 7</td></tr></table> |


<h2>Analysis of special prices</h2>

<h3>Amount of day from last appearing</h3>

![Delta](images/special_delta.jpg)

<h3>Top 10 amount of day from last appearing</h3>

![Delta top 10](images/special_delta_top_10.jpg)

<h2>Analysis of one-year results</h2>

Max: 122. Min: 77.

Mean: 97.47. Standard deviation: 9.64.

<h3>Detail</h3>

![Detail](images/heatmap.jpg)

<h3>Top 10</h3>

![Top 10](images/top-10.jpg)

<h3>Distribution</h3>

![Distribution](images/distribution.jpg)

<h2>Amount of day from last appearing</h2>

![Delta](images/delta.jpg)

<h3>Top 10 amount of day from last appearing</h3>

![Delta top 10](images/delta_top_10.jpg)