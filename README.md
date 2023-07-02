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
| <table><tr><td>Date</td><td>02-07-2023</td></tr><tr><td>Special</td><td>57123</td></tr><tr><td>First</td><td>20479</td></tr><tr><td>Second</td><td>94195, 90632</td></tr><tr><td rowspan="2">Third</td><td>09599, 24595, 62714</td></tr><tr><td>10302, 29610, 84396</td></tr><tr><td>Fourth</td><td>0499, 8769, 9271, 1209</td></tr><tr><td rowspan="2">Fifth</td><td>9426, 1181, 7561</td></tr><tr><td>1683, 4179, 0165</td></tr><tr><td>Sixth</td><td>999, 275, 227</td></tr><tr><td>Seventh</td><td>21, 23, 12, 96</td></tr></table> | <table><tr><td>First</td><td>Last</td></tr><tr><td>0</td><td>2, 9</td></tr><tr><td>1</td><td>0, 2, 4</td></tr><tr><td>2</td><td>1, 3, 3, 6, 7</td></tr><tr><td>3</td><td>2</td></tr><tr><td>4</td><td>-</td></tr><tr><td>5</td><td>-</td></tr><tr><td>6</td><td>1, 5, 9</td></tr><tr><td>7</td><td>1, 5, 9, 9</td></tr><tr><td>8</td><td>1, 3</td></tr><tr><td>9</td><td>5, 5, 6, 6, 9, 9, 9</td></tr></table> |


<h2>Analysis of special prices</h2>

<h3>Amount of day from last appearing</h3>

![Delta](images/special_delta.jpg)

<h3>Top 10 amount of day from last appearing</h3>

![Delta top 10](images/special_delta_top_10.jpg)

<h2>Analysis of one-year results</h2>

Max: 127. Min: 76.

Mean: 97.47. Standard deviation: 9.93.

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