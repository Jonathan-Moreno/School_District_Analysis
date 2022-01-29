# School_District_Analysis #

## Project Overview
Analysis of student standerdized test results for math and reading across 15 different high schools, with the exception of Thomas High School's 9th grade scores.

## Results

* District Summary:
  * ![Final District Summary](https://user-images.githubusercontent.com/96406929/151678589-0ca24508-b243-40a6-b116-b6e3bd3fdd99.png)
  * Removing Thomas High School's 9th grade results had a very minor impact the district summary by decreasing average scores and passing percentages 
  * Original results: ![Original District Summary](https://user-images.githubusercontent.com/96406929/151678748-aa757e12-7877-4448-9e8a-bdf9d7e81a00.png)

* School Summary:
  * ![Final School Summary](https://user-images.githubusercontent.com/96406929/151678771-67e1cf05-8f33-4059-a586-820efd0f11e8.png)
  * Removing Thomas High School's 9th grade results again had a minor impact on their % Passing Math, % Passing Reading and % Overall Passing
  * THS original results: ![Screen Shot 2022-01-29 at 2 11 31 PM](https://user-images.githubusercontent.com/96406929/151679185-403244d5-c4bb-461a-b08a-a884295487fa.png)

* Top 5 Performing Schools:
  * ![Screen Shot 2022-01-29 at 2 14 32 PM](https://user-images.githubusercontent.com/96406929/151679251-403843eb-2ef5-48c8-ae94-ecefa3013bc2.png)
  * The top 5 schools remained the same

* Bottom 5 Performing Schools:
  *![Screen Shot 2022-01-29 at 2 16 14 PM](https://user-images.githubusercontent.com/96406929/151679278-b1520901-d415-4aaf-bef3-9fd513f10f48.png)
  * Bottom 5 schools remained the same

* Math Scores by Grade:
  * ![Final math scores by Grade](https://user-images.githubusercontent.com/96406929/151679314-58ad21dd-b8a9-40b5-84ba-816153dbe21a.png)
  * Thomas High School's 9th grade math results have been replaced with NaN values

* Reading Scores by Grade:
  * ![Final reading scores by Grade](https://user-images.githubusercontent.com/96406929/151679345-0e8f767c-e5ef-462c-a47f-100e5fcfe1fe.png)
  * Thomas High School's 9th grade reading results have been replaced with NaN values

* Scores by School Spending:
  * ![Final Scores by School spending](https://user-images.githubusercontent.com/96406929/151679366-6327049b-ea9d-4464-976f-f1f039e2dde1.png)
  * Removing Thomas High Schools 9th grade results affected the percentages for bins $585 - $629 & $630 - $644
  * Original results: ![Original Scores by School Spending](https://user-images.githubusercontent.com/96406929/151679413-5bd76e8e-b05a-4dbd-8c11-7bc0d6b8dcfb.png)

* Scores by School Size:
  * ![Final scores by group size](https://user-images.githubusercontent.com/96406929/151679421-db830135-948c-4e1d-a70d-43dd93f9bff3.png)
  * There was no change to these results

*Scores by School Type:
  * ![Final scores by school type](https://user-images.githubusercontent.com/96406929/151679443-111f2ff1-8ce8-4443-a611-11bf3df97deb.png)
  * There was no change to these results

## Resources 
* Data Source: schools_complete.csv, students_complete.csv
* Software: Jupyter Notebook 6.4.5, Python 3.6.1

## Summary
Following the replacement of Thomas High School's 9th grade results with NaNs; there was a very minor impact in the district summary and school summary by decreasing average scores and passing percentages, although there was a noticable difference in the scores by school spending, specifically in bins $585 - $629 & $630 - $644. 

