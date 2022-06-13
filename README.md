<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  </a>

<h3 align="center">Sentiment Analysis</h3>

  <p align="center">
    Detecting the polarity of a given text
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li>
    <a href="#files">Files</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

The general idea of the project is to build an algorithm that reads some commentaries and concludes whether the sentiment of the text is positive, neutral or negative.

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

This module is programmed in Python 3.7.9. 

* [Python](https://python.org/)
* [Pandas](https://pandas.pydata.org/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

An adequate conda environment is needed in order to start using this project. We suggest the following simple steps to achieve it.

### Prerequisites

* python
* conda/miniconda
  
### Installation

There are some general library requirements for the project and some which are specific to individual methods. You don't have to worry about them, they are all in the requirements file.

1. Create a conda environment.

   ```sh
   conda create -n env_name python=3.7.9
   ```

2. Activate the created environment and install the requirements.

   ```sh
   conda activate env_name
   python -m pip install -r requirements.txt
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

Note: the following instructions must be executed in the corresponding conda environment and in the root folder of the project.

1. Provide an input file (you can contact me if you need one) and have it in the correct directory. 

2. Run the notebooks separately, in the order you desire.

## Files

You can find two files:

- ##### sentiment-analysis-logistic-regression.ipynb
 
Interactive notebook to train and test the sentiment analysis model using Logistic Regression. 

- ##### sentiment-analysis-naive-bayes.ipynb
 
Interactive notebook to train and test the sentiment analysis model using Naïve Bayes.

Note: Although the input dataset file is not included because it's from private property, contains all the commentaries and its scores.

<p align="right">(<a href="#top">back to top</a>)</p>

