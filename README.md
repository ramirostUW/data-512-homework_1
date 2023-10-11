# Data 512 Aut 2023 HW 1 :  Professionalism & Reproducibility

## What Is This?

This repository contains my work for the first Homework Assignment of Data 512, which I am taking in Autumn of 2023 and the University of Washington. The goal of this assignment is to produce work that follows a good standard of reproducibility, defined for the purposes of this assignment as meaning that enough context is provided for the code to be run with the same inputs I used to achieve the same outputs. 

The sample project we are to work on for this assignment involves querying Wikipedia's PageView API for view data for articles on Academy-Award winning movies from 2015 to 2023. The three Jupyter Notebooks in this repository contain code and documentation on my work for this assignment. 

## How to use

The directions and sample code I was provided are in the provided_files directory of this repository. They are not needed for the code to work, and are only provided to give complete context.

In order to run the code, you will first need to have the CSV in this repository in the same folder as the Step 1, Step 2, and Step 3 Notebooks (it is only needed for Step 1 to run). Step 1 will produce all of the files in the raw_data directory, which contains responses from PageView API requests with no modification. Step 2 will need the raw_data directory to be fully populated, and will produce the files in the refined_data directory, which contains three JSON files that each contain a compilation of a subset of the PageView data. Step 3 will need the refined_data directory to be fully populated, and will produce vizualizations directory, containing time series graphs depicting the data. After running their respective steps, the three directories should contain the files already provided exactly as they are. 

## Permissions and Licensing

This project, in Step 1, uses code made by my instructor for DATA 512 under  Creative Commons license. All original code is made available to to you under the terms described in the LICENSE file of this repository. 