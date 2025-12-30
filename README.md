# What You're Aiming For

To develop practical skills in file handling using Python by learning how to efficiently manage and manipulate file input/output operations on real-world datasets. The aim is to master the essential techniques for opening, reading, writing, and closing files within Python, ensuring effective data access and resource management in software development or data analysis tasks.

---

## Instructions

This ➡️ dataset (https://drive.google.com/file/d/16RjrvW2NG8Rt0AbblsflA8iJdxSXfl5C/view) contains loan information, including loan ID, customer gender, location, region, total price for each loan, etc.

1. Begin by importing the necessary libraries, **NumPy**.
2. Use the `open()` function to open the CSV file and assign the result to a variable.
3. Use a NumPy array to perform basic statistical analysis on the data, such as finding the **mean**, **median**, and **standard deviation** of the loan amounts.

---

## Notes

* Be sure to close the file after you have finished reading it using the `open()` function.
* Use the `delimiter` parameter in the `genfromtxt()` function to specify that the values in the file are separated by commas.
* You can use the NumPy functions `mean()`, `median()`, and `std()` to compute the required statistics.
