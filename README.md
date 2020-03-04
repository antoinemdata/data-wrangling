# Udacity Data Wrangling

## Introduction

This project was to mix .csv .tsv and json data (I've extracted data from WeRateDog Twitter account to get the favorite and retweet counts.

## Data Wrangling

Lots of changes were made to get Quality and Tidiness data better:
1) One column instead of 4 dogs nickname columns
2) Removing of useless columns: retweet/reply to and rows without retweet and favorite counts.
3) Transforming data types into useful types (for example the data was getting into datetime)
4) Creating a rating value by dividing the rating numerator by the rating denominator
5) Extracting URL address and anchoring text from the Source variable
6) Keeping only one URL in the expanded URLs variable
7) Cleaning and optimizing the dog names variable
8) Getting only the first prediction that concerned a dog
9) Dropping useless columns

## Results

With that optimizations, I could understand the most popular dog nicknames and race dogs. I could also know what the best day of the week and month to tweet were.
