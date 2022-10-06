# Stock Analysis Using VBA

## Overview of Project

### Purpose

The purpose of this challenge was to refractor VBA code I had created to analyze green energy stock data from 2017 and 2018. This was done so that the dataset could be expanded to include the entire stock market over a wider number of years and still be executed quickly and efficiently.  

##Results

### Stock Performance Between 2017 and 2018

The results of this analysis show that these green stocks earned a greater return in 2017 than in 2018. It is difficult to pinpoint the specific factors that contributed to this drop, but the data is reflective of the the plunge the stock market took as a whole in 2018, particularly in the second half <sup>1</sup>. The images from the data analysis below show positive returns in green, and negative returns in red. As you can see, green stocks were generally successful in 2017, but unfortunately, the opposite is true for 2018.

<img width="274" alt="Screen Shot 2022-10-05 at 6 54 48 PM" src="https://user-images.githubusercontent.com/113553238/194182082-8503d539-45b8-4cd0-8fde-a0489b981aa3.png">     <img width="273" alt="Screen Shot 2022-10-05 at 6 55 00 PM" src="https://user-images.githubusercontent.com/113553238/194182100-0eb04bfd-1433-43d0-849e-0b46577f1935.png">

### Execution Times Between the Refractored and Original Scripts

The execution times for the analyses of both years with the refractored code are shown in the images below. While the code took ever so slightly longer to run that in the original script, the code is much more concisse and logical. The enitre analysis is done in a single subroutine rather than two, and the variables used to represent the data, as well as the comments used to navigate the loops are clearer, more intuitive and easier to follow. This makes it easier for the code to be applied to data from the entire stock market as opposed to just the initial twelve stocks, and reduces the risk of errors and bugs.

<img width="511" alt="2017" src="https://user-images.githubusercontent.com/113553238/194184457-b96a4198-e2cb-4cbc-9eb0-9f5099fcb710.png">     <img width="530" alt="2018" src="https://user-images.githubusercontent.com/113553238/194184500-03076fe3-9f3a-404a-b45f-f9e2fa182785.png">

##Summary

### Advantages and Disadvantages of Refractoring Code

The benefits of refractoring code are adundant - not only can it improve the overall performance of the code, but it makes the code easier to read and maintain, and allows the code to be applied to different datasets and utilized by different developers. However, refractoring code can be time-consuming. The code will need to be continuously tested in order to ensure it runs successfully, and imprecise refractoring can lead to new errors in the code. Ultimately, the refractoring process will keep your code clean and enable it to run efficiently over a longer period of time.

## References

      2018. *S&P Dow Jones Indices*. [ebook] SPDJ.com, pp.1,4. Available at: <http://us.spindices.com/indices/equity/sp-500> [Accessed 3 October 2022].
