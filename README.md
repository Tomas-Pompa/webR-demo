# GAMU: Presentation of webR Functionalities

This is an interactive **HTML + webR** app that runs R code directly in your browser.

### Features

* Generate synthetic datasets with a chosen sample size `N`.
* Plot data with **ggplot2**.
* Fit linear regression models (`Width ~ Size * Type`).
* Visualize fitted regression lines.
* Upload your own `.csv` file and analyze it.

### CSV Upload

For testing, you can use the example datasets included in this repo:

* `data1.csv`
* `data2.csv`

### How to Run

* **Locally**: download/clone the repo and open `index.html` in a modern browser.
* **Online**: if enabled via GitHub Pages, visit:

  ```
  https://tomas-pompa.github.io/webR-demo/
  ```

### Notes

* The app uses **webR** (`ggplot2`, `dplyr`).
* Everything runs client-side, no server needed.
