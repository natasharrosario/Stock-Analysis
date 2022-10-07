# Stock Analysis Using VBA

## Overview of Project

### Purpose

The purpose of this challenge was to refactor VBA code I had created to analyze green energy stock data from 2017 and 2018. This was done so that the dataset could be expanded to include the entire stock market over a wider number of years and still be executed quickly and efficiently.  

## Results

### Stock Performance Between 2017 and 2018

The results of this analysis show that these green stocks earned a greater return in 2017 than in 2018. It is difficult to pinpoint the specific factors that contributed to this drop, but the data is reflective of the plunge the stock market took as a whole in 2018, particularly in the second half <sup>1</sup>. The images from the data analysis below show positive returns in green, and negative returns in red. As you can see, green stocks were generally successful in 2017, but unfortunately, the opposite is true for 2018.

<img width="274" alt="Screen Shot 2022-10-05 at 6 54 48 PM" src="https://user-images.githubusercontent.com/113553238/194182082-8503d539-45b8-4cd0-8fde-a0489b981aa3.png">     <img width="273" alt="Screen Shot 2022-10-05 at 6 55 00 PM" src="https://user-images.githubusercontent.com/113553238/194182100-0eb04bfd-1433-43d0-849e-0b46577f1935.png">

### Execution Times Between the Refactored and Original Scripts

The execution times for the analyses of both years with the refactored code are shown in the images below. While the code took ever so slightly longer to run that in the original script, the code is much more concise and logical. The entire analysis is done in a single subroutine rather than two, and the variables used to represent the data, as well as the comments used to navigate the loops are clearer, more intuitive and easier to follow. This makes it easier for the code to be applied to data from the entire stock market as opposed to just the initial twelve stocks, and reduces the risk of errors and bugs.

<img width="508" alt="2017" src="https://user-images.githubusercontent.com/113553238/194639645-15edd802-3d06-4914-9380-b58f95497888.png">
<img width="517" alt="2018" src="https://user-images.githubusercontent.com/113553238/194639654-efe97566-11e9-42c5-a521-efbce3aaeb65.png">

## Summary

### Advantages and Disadvantages of Refactoring Code

The benefits of refactoring code are abundant - not only can it improve the overall performance of the code, but it makes the code easier to read and maintain, and allows the code to be applied to different datasets and utilized by different developers. However, refactoring code can be time-consuming. The code will need to be continuously tested in order to ensure it runs successfully, and imprecise refactoring can lead to new errors in the code. Nevertheless, the refactoring process will ultimately keep your code clean and enable it to run efficiently over a longer period of time.

## References

1. *S&P Dow Jones Indices*. (2018). [ebook] SPDJ.com, pp.1,4. Available at: <http://us.spindices.com/indices/equity/sp-500> [Accessed 3 October 2022].
