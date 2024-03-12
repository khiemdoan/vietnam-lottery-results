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
| <table><tr><td>Date</td><td>12-03-2024</td></tr><tr><td>Special</td><td>00212</td></tr><tr><td>First</td><td>02044</td></tr><tr><td>Second</td><td>54494, 32692</td></tr><tr><td rowspan="2">Third</td><td>37525, 42210, 18702</td></tr><tr><td>87251, 33797, 01356</td></tr><tr><td>Fourth</td><td>3464, 3362, 1268, 3795</td></tr><tr><td rowspan="2">Fifth</td><td>6389, 7534, 7475</td></tr><tr><td>0291, 4719, 1601</td></tr><tr><td>Sixth</td><td>593, 102, 749</td></tr><tr><td>Seventh</td><td>76, 92, 64, 78</td></tr></table> | <table><tr><td>First</td><td>Last</td></tr><tr><td>0</td><td>1, 2, 2</td></tr><tr><td>1</td><td>0, 2, 9</td></tr><tr><td>2</td><td>5</td></tr><tr><td>3</td><td>4</td></tr><tr><td>4</td><td>4, 9</td></tr><tr><td>5</td><td>1, 6</td></tr><tr><td>6</td><td>2, 4, 4, 8</td></tr><tr><td>7</td><td>5, 6, 8</td></tr><tr><td>8</td><td>9</td></tr><tr><td>9</td><td>1, 2, 2, 3, 4, 5, 7</td></tr></table> |


<h2>Analysis of special prices</h2>

<h3>Amount of day from last appearing</h3>

![Delta](images/special_delta.jpg)

<h3>Top 10 amount of day from last appearing</h3>

![Delta top 10](images/special_delta_top_10.jpg)

<h2>Analysis of one-year results</h2>

Max: 119. Min: 79.

Mean: 97.74. Standard deviation: 8.84.

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