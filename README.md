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
| <table><tr><td>Date</td><td>05-01-2024</td></tr><tr><td>Special</td><td>38267</td></tr><tr><td>First</td><td>08715</td></tr><tr><td>Second</td><td>71363, 28859</td></tr><tr><td rowspan="2">Third</td><td>50469, 00804, 01569</td></tr><tr><td>47304, 36547, 91458</td></tr><tr><td>Fourth</td><td>5367, 6717, 9652, 1153</td></tr><tr><td rowspan="2">Fifth</td><td>9201, 2426, 2161</td></tr><tr><td>8950, 6793, 5932</td></tr><tr><td>Sixth</td><td>011, 537, 441</td></tr><tr><td>Seventh</td><td>96, 63, 69, 45</td></tr></table> | <table><tr><td>First</td><td>Last</td></tr><tr><td>0</td><td>1, 4, 4</td></tr><tr><td>1</td><td>1, 5, 7</td></tr><tr><td>2</td><td>6</td></tr><tr><td>3</td><td>2, 7</td></tr><tr><td>4</td><td>1, 5, 7</td></tr><tr><td>5</td><td>0, 2, 3, 8, 9</td></tr><tr><td>6</td><td>1, 3, 3, 7, 7, 9, 9, 9</td></tr><tr><td>7</td><td>-</td></tr><tr><td>8</td><td>-</td></tr><tr><td>9</td><td>3, 6</td></tr></table> |


<h2>Analysis of special prices</h2>

<h3>Amount of day from last appearing</h3>

![Delta](images/special_delta.jpg)

<h3>Top 10 amount of day from last appearing</h3>

![Delta top 10](images/special_delta_top_10.jpg)

<h2>Analysis of one-year results</h2>

Max: 126. Min: 78.

Mean: 97.47. Standard deviation: 9.37.

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