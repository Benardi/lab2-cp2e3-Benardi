[![Build Status](https://img.shields.io/badge/R%3E%3D-3.3.3-6666ff.svg)](https://cran.r-project.org/doc/FAQ/R-FAQ.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# EDA Spotify 

Exploratory data analysis with interactive visualizations on data from Spotify about Jackson do Pandeiro.

## Data

 The data used in this project has been download via the package [spotifyr](https://github.com/charlie86/spotifyr), a wrapper for the Spotify API. The code used to  gather the data can be found in the `code/` directory.

The attributes of each track are described [in the Spotify API documentation](https://beta.developer.spotify.com/documentation/web-api/reference/object-model/#audio-features-object). 

### Important 

To use the API you'll have to log in and get an *id* and a *secret* for your code [in the Spotify developer's webpage](https://developer.spotify.com/my-applications/#!/applications). Once you have both the *secret* and the *id* edit `code/chaves-do-spotify.csv`. Notice that this file and the keys shouldn't be uploaded to github, and for this reason have been added to `.gitignore`. 

### Prerequisites

* `R >= 3.3.3`
* highcharter
* tidyverse
* spotifyr
* stringr
* scales
* plotly
* dplyr
* here


## Execution

The R notebooks reside in the *notebooks* directory, and ideally should be run under the Rstudio IDE.

## Authors

* **Benardi Nunes** - *Exploratory Data Analysis* - [Benardi](https://github.com/Benardi)
* **Nazareno** - *Data Acquisition* - [Nazareno](https://github.com/nazareno)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

